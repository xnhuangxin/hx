<template>
  <div class="container">
    <div class="col-md-4 col-md-offset-4 mycontent">
      <h1 class="page-title">实习经历</h1>
        <span class="leader-icon"></span>
        <h2 class="work-title">四川全美 <span class="text-muted">前端工程师</span></h2>
        <p class="teach-time ">2017.09 - 2018.12</p>
        <ul class="work-detail">
          <li>负责公司产品的前端页面制作</li>
          <li>优化代码兼容性</li>
          <li>前端交互和网页美化</li>
        </ul>
      </div>
      <div class="learn-class my-ani">
        <span class="leader-icon"></span>
        <h2 class="work-title">四川全美 <span class="text-muted">前端工程师</span></h2>
        <p class="teach-time ">2017.09 - 2018.12</p>
        <ul class="work-detail">
          <li>负责公司产品的前端页面制作</li>
          <li>优化代码兼容性</li>
          <li>前端交互和网页美化</li>
        </ul>
      </div>
      <div class="get-reward my-ani">
        <span class="leader-icon"></span>
        <h2 class="work-title">四川全美 <span class="text-muted">前端工程师</span></h2>
        <p class="teach-time ">2017.09 - 2018.12</p>
        <ul class="work-detail">
          <li>负责公司产品的前端页面制作</li>
          <li>优化代码兼容性</li>
          <li>前端交互和网页美化</li>
        </ul>
      </div>
    </div>
  </div>
  
   </div>

</template>

<script>

  export default {
    name: 'Index',
    components: {
 
    },
    data() {
 
    },
    created() {
    
    },
    beforeDestroy() {
     
    },
    mounted() {
      
    },
    methods: {
      
    },
    
  }
  
</script>
<style>
  h1, h2, h3, p {
  margin: 2px;
}
.leader-icon {
  width: 35px;
  height: 35px;
  border: 5px solid #6CA6CD;
  border-radius: 50%;
  position: absolute;
  left: -60px;
  top: 0px;
}
.leader-icon::before {
  content: '';
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #333333;
  position: absolute;
  top: 9px;
  left: 9px;
}
.leader-icon::after {
  content: '';
  width: 5px;
  height: 330%;
  background: #333333;
  position: absolute;
  top: 40px;
  left: 10px;
}
.leader2::after {
  height: 350%;
}
.my-ani {
  position: relative;
  left: 60px;
  width: 100%;
  margin-top: 80px;
  margin-left: 0;
}
.active .my-ani {
  margin: 3px;
}
.work-title span {
  font-size: 20px;
}
.work-detail {
  font-size: 15px;
  margin-left: 30px;
}
</style>
