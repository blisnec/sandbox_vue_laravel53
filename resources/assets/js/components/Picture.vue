<template>
    <img class="profile-picture" :src="source">
</template>
<script>
    export default {
        data() {
            return {
                source: 'http://loremflickr.com/80/80'
            };
        }
    }
</script>
<style>
    .profile-picture {
        border: 3px solid #fff;
        border-radius: 50%;
        float: right;
        width: 80px;
    }
</style>