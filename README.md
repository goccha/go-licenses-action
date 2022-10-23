# go-licenses-action

## Inputs

### `allowed_licenses`

allow only specific license names.

### `disallowed_types`

disallowed license types

### `ignore`

specify package path prefixes to be ignored.

### `vendor`

vendor directory enable/disable

## Example usage

```yaml
steps:
  - name: Check OSS Licenses
    uses: goccha/go-licenses-action@latest
    with:
      allowed_licenses: MIT,Apache-2.0
      ignore: golang.org/x
```
