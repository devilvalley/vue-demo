<template>
   <el-menu
                :default-active="activeIndex2"
                class="el-menu-demo"
                mode="horizontal"
                @select="handleSelect"
                text-color="#fff"
                background-color="#545c64"
                active-text-color="#ffd04b">
            <el-menu-item index="1"><router-link to="/">Home</router-link></el-menu-item>
            <el-submenu index="2">
                <template slot="title"><router-link to="/about">About</router-link></template>
                <el-menu-item index="2-1">选项1</el-menu-item>
                <el-menu-item index="2-2">选项2</el-menu-item>
                <el-menu-item index="2-3">选项3</el-menu-item>
                <el-submenu index="2-4">
                    <template slot="title">选项4</template>
                    <el-menu-item index="2-4-1">选项1</el-menu-item>
                    <el-menu-item index="2-4-2">选项2</el-menu-item>
                    <el-menu-item index="2-4-3">选项3</el-menu-item>
                </el-submenu>
            </el-submenu>
            <el-menu-item index="3">Solutions</el-menu-item>
            <el-menu-item index="4"><a href="https://www.ele.me" target="_blank">Case Studies</a></el-menu-item>
            <el-menu-item index="5">Get a Quoto</el-menu-item>
        </el-menu>


</template>

<script>
export default {
    name: "daohang",
    data() {
        return {
            activeIndex: '1',
            activeIndex2: '1'
        };
    },
    methods: {
        handleSelect(key, keyPath) {
            console.log(key, keyPath);
        }
    }
}
</script>

<style scoped>

</style>