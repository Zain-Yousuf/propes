<template>
    <div>
<h1>My name is Zain</h1>
<!-- <h1>{{name}}</h1> -->
<h3 v-for="user in users" :key="user.name">{{user.name}}</h3>
    </div>
</template>

<script>
    export default {
        name:'chaild',
        props:['users']
    }
</script>

<style lang="scss" scoped>

</style>