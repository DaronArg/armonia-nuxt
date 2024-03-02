<template>
  <Home></Home>
</template>

<script>
definePageMeta({
  layout: 'indexl'
})
import Home from "./home/index.vue"

export default {
    name: "Index",
    components: {
        Home
    },
    setup(){

    }
    
}
</script>