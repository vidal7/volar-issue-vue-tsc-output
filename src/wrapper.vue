<template>
    <dummy :message="wrapperMessage" />
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import dummy from './dummy.vue';

    export default defineComponent({
        components: {
            dummy
        },
        data() {
            return {
                wrapperMessage: 0
            }
        }
    });
</script>
