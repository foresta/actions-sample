# Sample of GitHub Actions

This action is Sample of GitHub Actions.
It prints "Hello" + username to the log.

## Inputs

### `username`

**Required** This is username. Default `"Hoge"`

## Outputs

### `time`

The time this action is executed.

## Example usage

```yml
uses: foresta/actions-sample@v1
with:
  username: 'foresta'
```
