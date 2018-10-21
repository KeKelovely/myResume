<template>
  <div class="header">
    <div class="education">
      <div class="header-title">
        <div class="icon"><font-awesome-icon :icon="['fas', 'bookmark']" /></div>
        <div class='title'>教育经历</div>
      </div>
      <div class="header-content">
      <ul>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>2015.09 ~ 2017.03 武汉大学 资源与环境科学学院 地图制图系</strong> |  主修：算法数据结构 计算机制图</span>
        </li>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>2017.03 至今 武汉大学 新闻与传播学院 传播学  </strong> | 主修：网络传播 交互设计 产品策划 产品运营</span>  
        </li>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>学习成绩：专业排名1 / 53 | GPA：3.85 / 4.0 | 平均分： 90.0 / 100 </strong></span>  
        </li>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>获得荣誉：获1次国家奖学金，1次乙等奖学金，1次丙等奖学金</strong></span>  
        </li>     
      </ul>
      </div>      
    </div>
    <div class="work">
      <div class="header-title">
        <div class="icon"><font-awesome-icon :icon="['fas', 'bookmark']" /></div>
        <div class='title'>实习经历</div>
      </div>      
        <div class="header-content">
          <ul>
            <li>
              <font-awesome-icon :icon="['fas', 'circle']" />
              <span><strong>2016.04 ~ 2017.10 | 腾讯MIG应用宝 | 内容运营 </strong></span>
            </li>
            <li>
              <span>负责为应用宝上APP产品撰写其介绍页的推广文案，以线上兼职的方式与应用宝产品经理对接，期间累计为112款APP产出135篇文案，涵盖生活、理财、社交等方面，如美丽说、饿了么、花呗等</span>  
            </li>
            <li>
              <span>由于缺乏经验，实习初期事倍功半，文案通过率不足50%。经过反思总结，而后更注重表达产品如何满足用户痛点与核心需求，文案的通过率提高到90%以上，共计10+篇文章被推荐到应用宝首页</span>  
            </li>
            <li>
              <span>在实习中接触到腾讯产品运营流程，培养起了对互联网产品的热爱。这一经历也促成了我在大二时转入与产品岗位联系更密切的传播学专业。</span>  
            </li>     
          </ul>
        </div>
    </div>
    <div class="experience">
      <div class="header-title">
        <div class="icon"><font-awesome-icon :icon="['fas', 'bookmark']" /></div>
        <div class='title'>校园经历</div>
      </div>
      <div class="header-content">
          <ul>
            <li>
              <font-awesome-icon :icon="['fas', 'circle']" />
              <span><strong>华中科技大学 冰岩作坊 暑期夏令营 | 产品组实习</strong></span>
            </li>
            <li>
              <span>参加华科冰岩作坊2017暑期夏令营并顺利通过面试，在7分月内参与了直播类产品分析、H5策划、微信支付宝产品体验、《互读》/《小船》产品策划方案等任务。</span>
              <br>
              <span>共完成3份产品体验分析报告、2份产品策划案、4份用户调研报告、3篇读书笔记及7篇产品推广文案，并与产品组同学交流反馈，找出自身不足加以改进。</span>
              <br>
              <span>实习成果受到冰岩作坊产品组前辈的肯定，顺利收获冰岩作坊春季招新的绿色通道资格。</span>   
            </li> 
            <li>
              <font-awesome-icon :icon="['fas', 'circle']" />
              <span><strong>院系辩论队 副队长</strong></span>
            </li>
            <li>
              <span>在共计40多场的辩论赛中，培养磨练自身的逻辑思辨能力，学会将复杂问题化繁为简，直击核心的方法论，并能与队员高效地交流、合作，带领队伍多次在校内各级辩论赛事中取得优异成绩。</span>  
            </li>
            <li>
              <font-awesome-icon :icon="['fas', 'circle']" />
              <span><strong>院系学生会 微信公众号运营成员</strong></span>
            </li>
            <li>
              <span>在负责资环学生会公众号运营期间，借助微信平台的分析功能，评估每一类型推文的热门程度，结合对本院学生的访谈调研，设计出“专业前景分享”、“吃货大作战”等推送栏目，创作出一系列具有吸引力的文案，在学生会任期结束时累计推动公众号关注人数增长近50%。</span>  
            </li> 
          </ul>
        </div>   
    </div>
    <div class="love">
      <div class="header-title">
        <div class="icon"><font-awesome-icon :icon="['fas', 'bookmark']" /></div>
        <div class='title'>兴趣 / 技能</div>
      </div>
      <div class="header-content">
      <ul>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>前端开发</strong></span>
          <br>
          <span>熟悉HTML/CSS/JavaScript基础知识，了解Server端的NodeJS开发、Webpack/Gulp前端自动化工具、React/Vue前端框架的使用，了解前后端交互的原理及过程。掌握一定的数据结构、算法设计等知识。</span>
          <br>
          <span>「个人博客」：使用Hexo模板搭建的个人网站：https://kekelovely.me</span>
          <br>
          <span>「网页简历」：使用Vue+Less构建的静态简历页面，并导出成PDF格式（就是这份简历）</span>
          <br>
          <span>「弹幕组件」：使用Vue-cli+Canvas开发的原生弹幕组件，支持颜色、字体、大小等自定义属性</span>
        </li>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>产品设计</strong></span>
          <br>
          <span>在冰岩作坊实习与专业课学习过程中，掌握了PhotoShop、Axure的使用，设计了App通用登录注册页面UI图、互助工具产品《小船》、校园二手交易《趣买》及《蜂鸟专送》App（改进）的产品原型</span>
        </li>
        <li>
          <font-awesome-icon :icon="['fas', 'circle']" />
          <span><strong>社会实践</strong></span>
          <br>
          <span>参加《种太阳工作室关注留守儿童暑期夏令营》活动，主要负责摄影记录及微信公众号文章的撰写</span>
        </li> 
      </ul>
      </div>               
    </div>
  </div>
</template>

<script>
export default {
  name: 'headerBar',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.header {
  .header-title {
    position: relative;
    color: rgb(40, 182, 246);
    display: flex;
    margin: 10px;
    .icon {
      font-size: 35px;
      margin: 10px;
    }
    .title {
      font-size: 28px;
      margin: 13px 10px;
    }
    &::before {
      content: '';
      position: absolute;
      width: 400px;
      height: 5px;
      background-color: rgb(40, 182, 246);
      top: 60px;
      left: 5px;
    }
  }
  .header-content {
    ul {
      list-style: none;
      padding: 0 15px;
      margin: -1px 0px;
      li {
        padding: 5px 0;
        color: rgba(40, 182, 246, .5);
        font-size: 12px;
        span {
          margin: 0 7px;
          color: rgba(0, 0, 0, .8);
          font-size: 16px;
          line-height: 26px;
          font-family: PingFang TC,Avenir Next,Helvetica,Arial,Hiragino Sans GB,Microsoft YaHei,sans-serif;
        }
      }
    }
  }
}
</style>
