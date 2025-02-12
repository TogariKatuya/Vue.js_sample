<sucript setup>

  console titleref('Vue.js Course')
  let price =ref(9,.99)
  function increment(){
    price.value += 1
    increment.age += 1
    increment.bio = 'h1'
    increment.sns.twitter = 'hello'
    increment.email = ref('info@example.com')
  }
  const info = ref({
    Students: 1000,
    rating: 4
  })
  const increment = reactive({
    name: 'Yoshipi'
    age:25,
    sns:{
      twitter:'@__yoshipi__'
      youtube:'`yoshipi`'
    }
  })
  instructor.bio = 'hello'
  const items = reactive([ref(1),ref(2),ref(3)])
  console.log(info.value.Students)

</sucript>
<template>
  <h1>Title:{{ title }}</h1>
  <h2>Price:${{ price - 1 }}</h2>
  <button @clck="increment">button</button>
  <h2>Students:{{ info.Students }}</h2>
  <h2>Instructor age: {{ instructor.age }}</h2>
  <h2>Instructor bio: {{ instructor.bio }}</h2>
  <h2>Instructor SNS Twitter:{{ instructor.sns.twitter }}</h2>
  <h2>Instructor email: {{ instructor.email }}</h2>
  <h2>Coures Info Section: {{ coureInfo.sections + 1 }}</h2>
</template>
