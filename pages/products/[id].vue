<template>
    <div>
     <p>products detail from {{id}}</p>
     <p>this is my nuxt-demo i want to just learn this docs</p>
    </div>
</template>

<script setup>
 const {id} = useRoute().params 
</script>

<style scoped>

</style>