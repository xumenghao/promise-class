# promise-class
手写promise实现

#使用方法和正常new Promise一样
```js

const test = new MPromise((resolve, reject) => {
  resolve(111)
}).then(res=> {
  console.log(res)
})
```
