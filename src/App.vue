<sucript>
  let a = 1
  let b = 2
  let c = a + b
  a=4
  console.log(c)
  const title = 'Vue.js Course'

 let price = ref(9.99)
console.log(price)
function increment(){
  price.value += 1
  console.log(price)
  console.log(info.value)
}

</sucript>
<template>
  <h1>Title:{{ title }}</h1>
  <h2>Price:${{ price - 1 }}</h2>
  <button @clck="increment">button</button>
  <h2>Students:{{}}</h2>
</template>
