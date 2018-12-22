<template>
    <el-row>
        <el-col :span="12"><img src="../../assets/og_Ms_logo.png" style="width:50%"></el-col>
        <el-col :span="12">
            <form class="row" role="search">
                <input type="text" class="form-control" placeholder="Search">
                <button type="submit" class="btn btn-default">提交</button>
            </form></el-col>
    </el-row>
</template>

<script>
    export default {
        name: "logo"
    }
</script>

<style scoped>
    .el-row {
        margin-bottom: 20px;
    &:last-child {
         margin-bottom: 0;
     }
    }
    .el-col {
        border-radius: 4px;
    }
</style>