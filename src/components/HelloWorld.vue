<template>
  <h1>{{ msg }}</h1>
  <button class="rounded-lg px-5 py-3 my-4 text-white bg-green-500 active:bg-green-700 focus:outline-none" @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
