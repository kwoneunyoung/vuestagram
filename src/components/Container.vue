<template>
  <div>
    <Post :data="data[index]" v-for="(item, index) in data" :key="index"/>
  </div>
</template>

<script>
import Post from './Post.vue'

export default {
    name : 'Container',
    components : {
      Post
    },
    props : {
      data : Object
    }
}
</script>

<style>

</style>