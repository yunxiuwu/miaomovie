<template>
    <div id="main">
        <Header title="喵喵电影"></Header>
        <TabBar></TabBar>
    </div>

</template>

<script>

    import Header from "../../components/Header/index";
    import TabBar from "../../components/TabBar/index";
    export default {
        name:'Movie',
        components: {TabBar, Header},

    }
</script>

<style scoped>

</style>