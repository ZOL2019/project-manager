<template>
    <div>
        <el-container>
            <el-header class="header">
                <div class="text-left logo-title">
                    <div class="text-left logo">
                        <img src="" alt="LOGO">
                    </div>
                    <div class="text-left title">ZOL-PJ-Manager</div>
                </div>
                <div class="text-left menu-operate">
                    menu
                </div>
            </el-header>
        </el-container>
    </div>
</template>

<script>
    export default {
      name: 'Header'
    }
</script>

<style scoped lang="scss">
    @import '../../../../static/css/common.css';
    $header_width: 1200px;
    $header_height: 60px;
    $logo_title: 300px;
    $menu_operate: 900px;
    .header{
        text-align: center;
        margin: 0 auto;
        padding: 0;
        width: $header_width;
    }
    .logo-title{
        width: $logo_title;
        height: $header_height;
        line-height: $header_height;
        display: block;
        .logo{
            width: 60px;
        }
        .title{
            width: 240px;
        }
    }
    .menu-operate{
        width: $menu_operate;
        height: $header_height;
        line-height: $header_height;
        display: block;
    }
</style>