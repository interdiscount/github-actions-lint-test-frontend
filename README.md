# Lints and test frontend
Lints and tests a frontend application.

## Inputs

### `interdiscount-coop-user-pw`

**Required** Coop user password to access private GitHub npm registry.

## Example usage

```
uses: interdiscount/github-actions-lint-test-frontend@v1
with:
  interdiscount-coop-user-pw: ${{ secrets.INTERDISCOUNT_COOP_USER_PW }}
```
