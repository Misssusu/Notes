# 1
## 2

```html
    <style>
    
    </style> 
```

> dqw wqd qw 

~~_**`html`**_~~ 和 `css`

## 块作用域let
```js
if(true){
 var fruit = "apple";
}
console.log(fruit);
//apple
if(true){
 let fruit = "apple";
}
console.log(fruit);
//fruit is not defined
```
## 恒量const
```js
const fruit = "apple";
console.log(fruit);
//apple
const fruit = "apple";
const fruit = "banana"
console.log(fruit);
//Duplicate declaration "fruit"
```
## 解构数组
```js
//解构就是分解一个东西的结构
//ECMAScript旧写法
function breakfast(){
    return ['cake','milk','apple']
}
var temp = breakfast()
dessert = temp[0]
drink = temp[1]
fruit = temp[2]
console.log(dessert,drink,fruit)
//ECMAScript6新写法
function breakfast(){
    return ['cake','milk','apple']
}
let [dessert,drink,fruit] = breakfast()
console.log(dessert,drink,fruit)
```
