<template>
  <div class="post-meta px-2">
      <div class="meta card border-0">
          <ul class="list-inline seen border-bottom p-2">
            <li class="list-inline-item"><b-avatar rounded="lg" size="40" badge badge-offset="-0.5em">
              <template #badge><b-icon icon="star-fill"></b-icon></template>
            </b-avatar>
            </li>
            <li class="list-inline-item"><b-avatar  rounded="lg" size="40" badge-variant="info" badge-offset="-0.5em" text="BV" variant="primary">
              <template #badge><b-icon icon="star-fill"></b-icon></template>
           </b-avatar></li>
            <li class="list-inline-item"><b-avatar rounded="lg" size="40"  src="https://placekitten.com/300/300" variant="info"></b-avatar></li>
            <li class="list-inline-item"><b-avatar rounded="lg" size="40"  text="OK" variant="danger"></b-avatar></li>
            <li class="list-inline-item"><b-avatar rounded="lg" size="40"  variant="warning"></b-avatar></li>
            <li class="list-inline-item"><b-avatar rounded="lg" size="40"  src="https://placekitten.com/320/320" variant="dark"></b-avatar></li>
            <li class="list-inline-item"><b-avatar rounded="lg" size="40"  text="+24"></b-avatar></li>
          </ul>
          <ul class="comments list-unstyled">
              <Comment />
              <Comment />
              <Comment />
              <Comment />
              <Comment />
              
             
          </ul>
      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>