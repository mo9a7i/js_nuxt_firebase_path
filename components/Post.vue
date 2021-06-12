<template>
  <div class="post-content">
        <div class="post p-2" v-if="post.type == 'moment'">{{ post.content }}</div>
        <div class="post p-2" v-else-if="post.type == 'location'">{{ post.content }}</div>
        <div class="post p-2" v-else-if="post.type == 'media'"><ContentMedia :post="post" /></div>
        <div class="post p-2" v-else-if="post.type == 'sleep'">{{ post.content }}</div>
        <div class="post p-2" v-else-if="post.type == 'music'">{{ post.content }}</div>
        <div class="post p-2" v-else>Don't know what bullshit is dis broda</div>
  </div>
</template>

<script>
export default {
    props: ['post'],
}
</script>

<style>

</style>