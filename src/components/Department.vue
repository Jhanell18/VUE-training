<template>
  <div class="flex justify-center h-screen">
    <div class="p-3 flex justify-start flex-col w-1/2 m-0 ">
      <div class="p-10 px-10 flex flex-col items-start bg-gray-300 border-collapse border border-black-80">
      <label for="fname"> Department </label>
      <input class="p-1 border-collapse border border-black-900" type="text" >
    </div>
    <div class="p-2 px-5 flex flex-col items-end bg-gray-200">
      <button class="p-1 my-2 bg-pink-400 text-white rounded-md focus:outline-none focus:ring-2 ring-blue-200 ring-offset-2">Create Department</button>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Department',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
