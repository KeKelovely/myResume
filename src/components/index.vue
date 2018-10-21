<template>
  <div class="index">
  	<div class="index-content">
      <div class="siderBar">
        <sider-bar></sider-bar>
      </div>
      <div class="main">
        <div class="header">
          <header-bar></header-bar>
        </div>
      </div> 		
  	</div>
  </div>
</template>

<script>
import siderBar from './sideBar.vue'
import mainContent from './mainContent.vue'
import headerBar from './headerBar.vue'

export default {
  name: 'index',
  components: {
    siderBar,
    headerBar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
* {
  margin: 0;
  padding: 0;
  list-style: none;
}
.index {
	position: relative;
	margin: 0 auto;
  width: 1020px;
  height: 1450px;
}
.index-content {
  position: relative;
  margin: 0 auto;
  display: flex;
  padding: 0;
  height: 100%;
  border-style: solid;
  border-width: 15px;
  border-color: rgba(0, 0, 0, .1);
  .siderBar {
    flex: 1;
  }
  .main {
    flex: 3;
    .header {
      margin: 15px 0 0 0;
    }
  }  
}
</style>