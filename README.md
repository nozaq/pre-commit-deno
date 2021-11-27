# pre-commit-deno

[pre-commit](https://pre-commit.com/) git hooks for [Deno](https://deno.land/) projects.

## Using pre-commit-deno with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/nozaq/pre-commit-deno
    rev: v0.1.0  # Use the ref you want to point at
    hooks:
    -   id: deno-fmt
    -   id: deno-lint
    # -   id: ...
```

## Hooks available

### `deno-fmt-check`

Checks if all JavaScript, TypeScript, Markdown and JSON files are formatted.

### `deno-fmt`

Auto-format all JavaScript, TypeScript, Markdown and JSON files.

### `deno-lint`

Lint all JavaScript and TypeScript source code files.

### `deno-test`

Run tests.
