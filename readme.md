# A small destructing test

Why does `require('./index')` return `{}`?

## Expected Output

```js
Hello!
{
    B: {},
    C: "Hello!"
}
Hello!
```

## Actual Output

```js
undefined
{}
Hello!
```