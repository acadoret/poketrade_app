<template>
    <div class="ui counter">
        {{ count }}
        <div class="ui button counter_button" @click="increment">+</div>
    </div>
</template>
<script>
    import store from '../../store/NotificationStore'
    export default{
        data(){
            return {
                state: store.state 
            }
        },
        computed: {
            count(){
                return this.state.count
            }
        },
        methods: {
            increment() {
                store.increment()
            }
        }
    }
</script>
<!--style src="counter.css"></style-->