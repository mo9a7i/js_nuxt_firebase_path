<template>
  <div class="content-media">
    <b-aspect class="media" aspect="4:3" :style="{ backgroundImage: 'url(' + post.media_thumb_url  }">
        <header class="d-flex justify-content-between px-2">
            <b-avatar square class="avatar" rounded="lg" size="50"></b-avatar>
           <div> <div class="seen p-1 px-3 text-center rounded-pill"><b-icon-globe /> 250K</div></div>
        </header>
        
      </b-aspect>
          
  </div>
</template>

<script>
export default {
    props: ['post'],
}
</script>

<style>

</style>