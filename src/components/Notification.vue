<template>
    <div class="ui">
        <Counter/>
        <button class="ui button" @click="addNotification"> Add </button>
    </div>
</template>


<script lang="ts">
    import Counter from './Counter/Counter.vue'
    export default {
        components: {Counter }
    }
</script>