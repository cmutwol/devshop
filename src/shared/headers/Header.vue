<template>
    <div>
        <Scroll v-if="scroll"/>
        <Default v-else/>
    </div>
</template>

<script>
import Scroll from "./components/Scroll.vue";
import Default from "./components/Default.vue";
    export default {
        data() {
            return {
                scroll: true
            }
        },
        components: {
            Scroll,
            Default
        }
    }
</script>