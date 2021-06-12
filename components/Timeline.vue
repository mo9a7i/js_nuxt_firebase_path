<template>
  <div class="timeline">
      <div v-if="posts">
          <div v-for="post in posts" :key="post.id">
              <Post :post="post" />
              <PostMeta :postMeta="post.meta" />
          </div>
      </div>
      <div v-else>Nothing Here Broda</div>
  </div>
</template>

<script>
export default {
    data(){
        return {
            posts: [
                {
                    id: 5,
                    content: "Hello THere Broda",
                    type: "moment",
                    author: {
                        id: 5,
                        name: "mo9a7i",
                        display_picture_thmb_url: ''
                    },

                    meta: {
                        created_at: '6-9-2021 12:40:23',
                        
                        seen: [1,2,3,4,5,6],
                        comments: [{
                            content: 'hahahahhahaha',
                            author: 3,
                            created_at: '6-9-2021 12:40:23'
                        }],
                        emotions: [
                            {
                                type: 'heart',
                                author: 2
                            },
                        ],
                    }
                },
                {
                    id: 1,
                    content: "Hello THere Broda",
                    type: "media",
                    media_thumb_url: "https://i.pinimg.com/564x/46/64/01/466401fc0a634def18688603f4362f8f.jpg"
                },
                {
                    id: 7,
                    content: "Hello THere Broda",
                    type: "sleep"
                },
                {
                    id: 3,
                    content: "Hello THere Broda",
                    type: "music"
                },
                {
                    id: 2,
                    content: "Hello THere Broda",
                    type: "location"
                },
            ]
        }
    }
}
</script>

<style>

</style>