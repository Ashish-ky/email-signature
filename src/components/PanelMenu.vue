<template>
  <div>
    <ul>
      <li><i class="bi bi-briefcase-fill"></i></li>
      <li><i class="bi bi-justify-left"></i></li>
      <li><i class="bi bi-brush-fill"></i></li>
      <li><i class="bi bi-images"></i></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'PanelMenu',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0px;
}
li {
  display: block;
  width: 70px;
  height: 70px;
  margin: 1px 0px;
  background-color: rgb(69, 102, 102) ;
}
i {
  color: #fff;
  font-size: 25px;
  line-height: 70px;
}
</style>
