<template>
  <div>
    <Post :data="data" />
    <Post />
    <Post />
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
        data : Array
    }
}
</script>

<style>

</style>