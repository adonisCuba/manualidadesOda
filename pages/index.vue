<template>
<div>
  <the-header/>
  <div class="container mx-auto m-1">
    <div class="bg-gray-200 h-72 rounded-xl">
      <div class="h-72 rounded-xl shadow-lg transform rotate-1 bg-gradient-to-br from-purple-500 to-indigo-500">
        
      </div>
    </div>
  </div>
</div>
</template>

<script>
import TheHeader from '~/components/TheHeader.vue'
export default {
  components: { TheHeader },
  layout: "empty"
}
</script>
