<template>
  <div class="side">
    <div class="title">
      <span class="name">「张可」</span>
      <br>
      <br>
      <span>个人简历</span>
    </div>
    <div class="info">
      <h2>基本信息</h2>
      <span>
        <font-awesome-icon :icon="['fas', 'user']" />
        姓名：张可
      </span>
      <br>
      <span>
        <font-awesome-icon :icon="['fas', 'smile']" />
        性别：男
      </span>
      <br>
      <span>
        <font-awesome-icon :icon="['fas', 'phone']" />
        电话：18502705485
      </span>
      <br>
      <span>
      	<font-awesome-icon :icon="['fab', 'weixin']" />
      	微信： zk250max
      </span>
      <br>
      <span>
      	<font-awesome-icon :icon="['fab', 'github']" />
      	个人博客：kekelovely.me
      </span>
      <br>
      <span>
        <font-awesome-icon :icon="['fas', 'envelope']" />
        邮箱：kekelovelyst@foxmail.com
      </span>
      <br>
    </div>
    <div class="info">
      <h2>实习信息</h2>
      <span>
        <font-awesome-icon :icon="['fas', 'cube']" />
        应聘岗位：产品实习生    	
      </span>
      <br>
      <span>
      	<font-awesome-icon :icon="['fas', 'briefcase']" />
        每周保证到岗天数：5+
      </span>
      <br>
      <span>
        <font-awesome-icon :icon="['fas', 'clock']" />
        实习时间：
        <br>
        2019年1月 ~ 2019年6月底
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sideBar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.side {
  background-color: rgba(40, 182, 246, 1);
  height: 100%;
  .title {
  	margin: 0 auto;
  	padding: 30px;
  	text-align: center;
  	color: rgba(255, 255, 255, .85);
  	.name {
  		font-size: 30px;
  	}
  	span {
  		font-size: 24px;
  	}
  }
  .info {
    margin: 0 auto;
    padding: 30px;
    color: rgba(255, 255, 255, .85);
    h2 {
      font-weight: normal;
      font-size: 22px;
    }
    span {
      font-size: 15px;
      line-height: 30px;
    }
  }
}
</style>
