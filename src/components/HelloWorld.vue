<template>
    <div>
    <el-row id="bg">
        <el-col :span="16" :offset="4">
            <el-container>
            <el-header>
                <logo></logo>
                <daohang></daohang>
            </el-header>
                <el-main><router-view/></el-main>
        </el-container>

        </el-col>
    </el-row>

    <el-row id="foot">
        <el-col :span="16" :offset="4">
            <foot></foot>

        </el-col>
    </el-row>
    </div>
</template>

<script>
import daohang from '../components/header/nav.vue'
import logo from '../components/header/logo.vue'
import foot from '../components/footer/foot.vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
   daohang,
   logo,
   foot
   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.el-row {
    margin-bottom: 0px;
}
.el-col {
    border-radius: 4px;
}
.grid-content {
    border-radius: 4px;
    min-height: 36px;
}
.row-bg {
    padding: 10px 0;

}
.el-header, .el-footer{
    color: #333;
    text-align: center;

}
.el-main {
    color: #333;
    text-align: center;
    margin-top: 10%;
}
#bg{
    background: url("../assets/ogMs_bg.jpg");
    background-position: 50% 50%;
}
#foot{
    background: orange
}
</style>
