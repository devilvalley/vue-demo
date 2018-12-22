<template>
  <div class="home">
    <el-carousel :interval="4000" type="card" height="200px">
      <el-carousel-item >
        <img src="../assets/ogMs_banner.jpg">
      </el-carousel-item>
      <el-carousel-item >
        <img src="../assets/ogMs_banner.jpg">
      </el-carousel-item>
      <el-carousel-item >
        <img src="../assets/ogMs_banner.jpg">
      </el-carousel-item>
    </el-carousel>
    <el-row>
      <el-col :span="8"> <div id="1">
        <h4>Welcome to the Orange Monster</h4>
        <h4><small>Cras et est ac orci convallis lacinia ut vita</small></h4>
        <p>Class aptent taciti sociosqu ad litora torquent per conubia nostra,per inceptos himenaeos.Phasellus fe
          ugiat,lacus sed adipiscing venenatis,<span class="text-primary" >est odio pharetra mi,</span>
          eu molestie orci urna id lacus.Pellentesque solicitudin pulvinar est quis aliquam.</p>
        <p>Cras ac tellus justo,et tincidunt nibh.Pellentesque habitant morbi tristique senectus et malesuada
          fames ac turpis egestas.<span class="text-primary" >Morbi porta vulputate </span>lorem,quis dignissim eros feugiat sit
          amet!Donec suscipit portitor leo vel iac ulis.</p>
        <p>Class aptent tacili sociosqu litora torquent per conubia nostra,per inceptos himenaeos.
          Phasellus feugiat,lacus sed adipiscing vennenatis,est odio pharetra mi,eu molestie orciurna
          id lacus.Pellentesque solicitudin pulvinar est quis aliquam</p>
        <button type="button" class="btn btn-primary">Click Me</button>
      </div></el-col>
      <el-col :span="8"><div id="2">
        <img src="../assets/ogMs_feat1.png" alt="">
        <img src="../assets/ogMs_feat2.png" alt="">
      </div></el-col>
      <el-col :span="8"><div id="3">
        <h4 class="text-warning">Pellentesque habitant morbi</h4>
        <p>tristique senectus et netus et malesuada fames ac turpis egestas.Duis arcu enim,ultrices nec mollis.
          commodo,<span class="text-primary" >lobortis quis neque.</span>Duis consequat diam eu ipsum volupat
          pulvinar.Quisque venenatis laoreet ligula vel ultrices.</p>
        <p>Aliquam quis eros elit,eget facilisis elit.Quisque sodales,nunc sed sodales blandit,metus justo gravida
          eros,at facilisis <span class="text-primary" >lorem mi ac augue.</span>Nullam sed turpis orci,at
          dapibus metus.Suspendisse sed venenatis ipsum.Aliquam erat volutpat.</p>
        <h4 class="text-warning">onec ornare volutpat molestie</h4>
        <p>Etiam tortor urna,ultricies id ultrices id;faucibus sit ameturna.Mauris accumsan,risus sit amet rhoncus euismod,
          velit enim <span class="text-primary" >ullamcorper odio</span>,feugiat semper erat sapien sit amet justo.
          Fusce suismod dictum pretium.Sed venenatis felis eu ante feugiat pretium?</p>
        <p>Aliquam quis eros elit,eget facilisis elit.Quisque sodales,nunc sed sodales blandit,metus justo gravida eros,
          at facilisis lorem mi ac augue.</p>
      </div></el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {

  }
}
</script>

<style  scoped>
h4{
  color:white;
  font-size: 14px
}
p{
color: white;
font-size: 7px;
line-height: 11px;
}
#2 img{
  width: 100%;
  height: auto;
  border: 2px solid white;
  margin: 5px
}
button{
  width: 45%;
  font-size: 10px;
  border-radius: 15px
}
#1,#2,#3{
  padding:5px;
}
#1{
  background-color: rgba(0,0,0,0.5)
}
</style>