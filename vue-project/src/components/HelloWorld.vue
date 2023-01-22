<template>
  <div class="greetings">
      Todo list goes here.
  </div>
</template>

<Script>
export default {
  name: 'todo-list',
  data (){
      return {
          msg: 'welcome to your Vue.js App'
      }
  }
}
</Script>

<style>
h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0;
}

a {
  color: #42b983;
}
</style>
