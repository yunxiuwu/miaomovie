<template>
    <div id="main">
        <Header title="我的喵喵" />
        <TabBar />
    </div>
</template>

<script>
    import Header from "../../components/Header/index";
    import TabBar from "../../components/Tabbar/index";
    export default {
        name: 'Mine',
        components: {TabBar, Header},
    }
</script>

<style scoped>

</style>