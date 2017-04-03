# A small destructing test

Why does `require('./index')` return `{}`?

## Test Command
```
node index
```

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

![A screenshot of results](https://requires.discord.gold/9dcf0e.png)