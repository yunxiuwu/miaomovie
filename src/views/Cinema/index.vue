<template>
    <div>
        <Header title="喵喵影院"></Header>
        <TabBar></TabBar>
    </div>
</template>

<script>
    import Header from "../../components/Header/index";
    import TabBar from "../../components/TabBar/index";
    export default {
        name:'cinema',
        components: {TabBar, Header}
    }
</script>

<style scoped>

</style>