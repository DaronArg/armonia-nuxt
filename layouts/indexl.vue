<template>
    <div class="flex h-screen flex-col">

        <Navbar></Navbar>
        <main class="">
            
            <NuxtPage></NuxtPage>
        </main>
    </div>

</template>
<script>
import Navbar from './Navbar.vue';
export default{
    name: "indexLayout",
    components:{
        Navbar
    },
    setup(){

    }
}
</script>