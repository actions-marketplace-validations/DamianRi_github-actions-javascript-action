# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
- name: Github Actions Javascript Action by damianri
  uses: DamianRi/github-actions-javascript-action@v1
  with:
    who-to-greet: 'Rick Genial'
```