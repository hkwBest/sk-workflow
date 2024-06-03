<template>
    <Setting></Setting>
</template>

<script>
import Setting from './setting.vue';
export default {
    components: {
        Setting
    },
    mounted() {
        console.log(process.env.BASE_URL);
    },
    methods: {}
};
</script>
