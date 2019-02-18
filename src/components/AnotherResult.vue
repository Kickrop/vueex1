<template>
    <dIv>
        <p>Counter is: {{ doubleCounter }}</p>
        <p>Number of clicks: {{ stringCounter }}</p>
    </dIv>
</template>

<script>
import { mapGetters } from 'vuex';
    export default {
        // computed: {
        //     counter() {
        //         return this.$store.getters.doubleCounter;
        //     },
        //     clicks() {
        //         return this.$store.getters.stringCounter;
        //     }
        // }
        computed: 
            ///{}...mapGetters([
         mapGetters([
            'doubleCounter',
            'stringCounter'
        ])
        
    }
</script>