[[JavaScript]] [[TypeScript]] [[Unicode]]


```ts
// 大文字
for(let code=65; code<=91; code++) {
    console.log(`${code} ${String.fromCodePoint(code)}`)
}

// 小文字
for(let code=97; code<=122; code++) {
    console.log(`${code} ${String.fromCodePoint(code)}`)
}
```
