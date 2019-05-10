<template>
  <div class="dashboard-container">
    <iframe :src="map" style="width:100%;height:900px" />
  </div>
</template>

<script>
// import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  data() {
    return {
      map: '../../../static/1.html'
    }
  }
}
</script>

<style lang="scss" scoped
>
.dashboard {
  width: 100%;
  height: 100%;
  // &-container {
  //   margin: 30px;
  // }
  // &-text {
  //   font-size: 30px;
  //   line-height: 46px;
  // }
}
.navbar {
  background-color: black;
}
</style>
