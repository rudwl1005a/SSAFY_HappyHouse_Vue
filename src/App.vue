<template>
    <div id="app">
        <side-bar></side-bar>
        <router-view/>
    </div>
</template>

<script>
import SideBar from "@/views/Sidebar.vue";

export default {
    name: "app",
    components: { SideBar },
    data() {
        return {

        }
    },
    methods: {

    }
};
</script>

<style>

</style>
