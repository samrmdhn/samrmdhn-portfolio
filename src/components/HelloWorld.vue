<template>
  <div>
    <b-container fluid style="height: 100vh">
      <b-row class="text-left">
        <b-col lg="12" style="font-size: 4rem; padding-left: 5rem; font-style: italic;">
        <div><span style="font-size: 3.5rem">Syams.Syair.Ramadhan's </span><i>{<span style="font-family: Calisto MT; color: #d3ff52">Portfolio</span>}</i></div>
        <div> <span style="color: #d3ff52">⟶</span><span style="font-size: 3.5rem"> 22.yrs.old ☺ </span> <div class="lingkaran"></div> <i><span style="font-family: Calisto MT">Fresh.Graduate ☼ </span></i></div>
        <div><span style="font-size: 3.5rem">Front.End.Developer ✺ </span><i><span style="font-family: Calisto MT">Node.js</span></i> <i><span>&</span></i> Vue.js</div>
        <div><i><span style="font-family: Calisto MT">Based.in.Bandung</span></i><img style="height: 60px; width: 60px; margin-left: 10px; margin-bottom: 10px;" src="../assets/FW-SHAPE-04.png" alt=""></div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.lingkaran{
  height: 41px;
  width: 41px;
  border-radius: 50%;
  background-color: #d3ff52;
  display: inline-block;
}

</style>
