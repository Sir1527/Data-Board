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
              <div class="vertical-middle manager-info">
                <div class="img">
                  <el-avatar :size="48" src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png" />
                </div>
                <div style="margin-left: 15px;display: inline-block;vertical-align: middle;">
                  <div class="name">冯新贤</div>
                  <div class="flag">IE</div>
                </div>
              </div>
              <div class="vertical-middle ver-line1"></div>
              <div class="vertical-middle manager-desc">负责DVB产品、音箱项目产品工艺文件制作和产品定额。</div>
            </div>
            <div class="manager-item">
              <div class="vertical-middle manager-info">
                <div class="img">
                  <el-avatar :size="48" src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png" />
                </div>
                <div style="margin-left: 15px;display: inline-block;vertical-align: middle;">
                  <div class="name">李海燕</div>
                  <div class="flag">线长</div>
                </div>
              </div>
              <div class="vertical-middle ver-line1"></div>
              <div class="vertical-middle manager-desc">总装六班、九班线长，负责日常生产和人员管理。</div>
            </div>
            <div class="manager-item">
              <div class="vertical-middle manager-info">
                <div class="img">
                  <el-avatar :size="48" src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png" />
                </div>
                <div style="margin-left: 15px;display: inline-block;vertical-align: middle;">
                  <div class="name">梁海兵</div>
                  <div class="flag">工艺</div>
                </div>
              </div>
              <div class="vertical-middle ver-line1"></div>
              <div class="vertical-middle manager-desc">助理工程师。音箱项目产品主管工程师，负责产品技术问题和提效。</div>
            </div>
          </div>
        </div>
        <div class="left-bottom">
          <div class="block-border">
            <div class="title-content">
              <div class="ver-line"></div>
              <span class="title" data-v-09e07f67="">批次库存（E4B6）</span>
              <div class="small-point"></div>
            </div>
            <div class="slot-content">
              <div class="order-count">
                <div>批次总数:</div>
              </div>
            </div>
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

.vertical-middle {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}

.manager-info {
  width: calc(45% - 10px);
  display: inline-block;
  vertical-align: top;
}

.img {
  width: 48px;
  height: 48px;
  border: 1px solid #bbbbbb;
  box-shadow: 0 0 3px 3px #bbb;
  border-radius: 50%;
  display: inline-block;
  vertical-align: middle;
}

.name {
  color: #24e5ff;
  margin-bottom: 4px;
}

.flag {
  font-size: 14px;
}

.ver-line1 {
  display: inline-block;
  height: 120%;
  width: 1px;
  margin: 0 10px;
  background: linear-gradient(0deg, transparent, #1540adff 50%, transparent);
}

.manager-desc {
  display: inline-block;
  width: calc(55% - 15px);
  color: #fff;
  font-size: 12px;
  vertical-align: top;
}

.left-bottom {
  height: calc(50% - 10px);
}

.order-count {
  height: 40px;
  line-height: 40px;
}
</style>
