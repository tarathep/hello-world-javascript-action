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
uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'
```

## Create a JavaScript action

https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action

As an alternative, you can use a tool called `@vercel/ncc` to compile your code and modules into one file used for distribution.


