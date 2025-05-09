<script setup>

</script>

<template>
  <div id="app">
    <div class="header">
      <div>
        <div class="left-content">
          总装十号线体~总装六班
        </div>
        <div class="center-title">
          长虹新网智能终端工厂
        </div>
        <div class="right-date">
          2025-04-29 14:05:10 星期二
        </div>
      </div>
    </div>
    <div class="chart-content-wrap">
      <div class="left-chart">
        <div class="left-top">
          <div class="title-content">
            <div class="ver-line"></div>
            <span class="title" data-v-09e07f67="">人员介绍</span>
            <div class="small-point"></div>
          </div>
          <div class="slot-content">
            <div class="manager-item">
              <div class="bg-image-common">
<!--                <img src="http://10.51.36.212:8888/je/document/preview?fileKey=wjVB6BA6QFQSKUYhWBj"-->
<!--                     style="width: 48px;height: 48px;-->
<!--                     border: 1px solid #bbbbbb;-->
<!--                     box-shadow: 0 0 3px 3px #bbb;-->
<!--                     border-radius: 50%;-->
<!--                     vertical-align: middle;-->
<!--                     background-position: center;" />-->
<!--                <el-avatar src="http://10.51.36.212:8888/je/document/preview?fileKey=wjVB6BA6QFQSKUYhWBj" />-->
              </div>
            </div>
            <div class="manager-item"></div>
            <div class="manager-item"></div>
          </div>
        </div>
      </div>
      <div class="middle-chart">

      </div>
      <div class="right-chart">

      </div>
    </div>
  </div>
</template>

<style scoped>

#app {
  background-color: #001432;
  height: 100vh;
  display: block;
  min-width: 1280px;
}

.header {
  height: 80px;
  width: 100%;
  line-height: 80px;
  margin-bottom: 20px;
  background-image: url("./assets/img/nw-team-header.bbd92888.png");
  background-size: 100% 100%;
  display: block;
}

.left-content {
  font-weight: 700;
  font-size: 20px;
  color: #24e5ff;
  display: inline-block;
  width: calc(30% - 40px);
  padding: 0 20px;
}

.center-title {
  display: inline-block;
  width: 40%;
  text-align: center;
  font-size: 30px;
  font-weight: 700;
  letter-spacing: 3px;
  vertical-align: top;
  height: 100%;
  color: #fff;;
}

.right-date {
  display: inline-block;
  text-align: right;
  font-size: 20px;
  font-weight: 700;
  color: #24e5ff;
  width: calc(30% - 40px);
  padding: 0 20px;
}

.chart-content-wrap {
  display: block;
  height: calc(100% - 100px);
  padding: 0 20px;
}

.left-chart {
  display: inline-block;
  vertical-align: top;
  width: calc(25% - 10px);
  height: 100%;
}

.middle-chart {
  display: inline-block;
  vertical-align: top;
  width: calc(50% - 20px);
  height: 100%;
  margin: 0 20px;
}

.right-chart {
  display: inline-block;
  vertical-align: top;
  width: calc(25% - 10px);
  height: 100%;
}

.left-top {
  height: calc(50% - 10px);
  margin-bottom: 20px;
}

.title-content {
  position: relative;
  height: 20px;
  line-height: 20px;
  width: calc(100% - 20px);
  padding-bottom: 10px;
  margin-bottom: 10px;
  border-bottom: 1px solid rgba(255, 255, 255, .2);
}

.ver-line {
  display: inline-block;
  height: 20px;
  width: 3px;
  border-radius: 2px;
  background-color: #24e5ff;
  margin-right: 10px;
  vertical-align: middle;
}

.title {
  font-size: 16px;
  margin: 0 auto;
  width: 150px;
  color: #fff;
  font-weight: 700;
  vertical-align: middle;
}

.small-point {
  position: absolute;
  right: -20px;
  bottom: -5px;
  height: 10px;
  width: 10px;
  border-radius: 50%;
  background-color: #fff3;
}

.slot-content {
  height: calc(100% - 40px);
  text-align: left;
  color: #fff;
}

.manager-item {
  height: calc(33.33% - 28px);
  margin-bottom: 12px;
  border-radius: 4px;
  padding: 10px 10px 10px 20px;
  background: rgba(15, 45, 122, .5);
}

.bg-image-common {
  width: 48px;
  height: 48px;
  background-image: url("http://10.51.36.212:8888/je/document/preview?fileKey=wjVB6BA6QFQSKUYhWBj");
}
</style>
