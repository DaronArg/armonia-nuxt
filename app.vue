<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
<script>
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
onMounted(() => {initFlowbite()})

</script>