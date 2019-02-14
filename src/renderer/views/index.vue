<template>
    <div>
        <el-container>
            <el-header class="container-header">
                <header-view/>
            </el-header>
            <el-main class="container-main">
                <main-view/>
            </el-main>
        </el-container>
    </div>
</template>

<script>
    import HeaderView from './Home/Header'
    import MainView from './Home/Main'
    export default {
      components: {HeaderView, MainView},
      name: 'index'
    }
</script>

<style scoped lang="scss">
    .container-header{
        overflow: hidden;
    }
    .container-main{
        overflow: hidden;
    }
</style>