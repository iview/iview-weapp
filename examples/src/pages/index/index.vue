<template>
  <div>
    <scoll-view></scoll-view>
    <i-panel title="布局">
      <i-cell-group>
        <i-cell title="Layout 栅格布局" is-link="true" url="/pages/layout/main"></i-cell>
        <i-cell title="Grid 宫格" is-link="true" url="/pages/grid/main"></i-cell>
        <i-cell title="Panel 面板" is-link="true" url="/pages/panel/main"></i-cell>
        <i-cell title="List 列表" is-link="true" url="/pages/list/main"></i-cell>
        <i-cell title="Card 卡片" is-link="true" url="/pages/card/main"></i-cell>
      </i-cell-group>
    </i-panel>
    <i-panel title="基础组件">
      <i-cell-group>
        <i-cell title="Button 按钮" is-link="true" url="/pages/button/main"></i-cell>
        <i-cell title="Color 色彩" is-link="true" url="/pages/color/main"></i-cell>
        <i-cell title="Icon 图标" is-link="true" url="/pages/icon/main"></i-cell>
      </i-cell-group>
    </i-panel>
    <i-panel title="导航">
      <i-cell-group>
        <i-cell title="TabBar 标签栏" is-link="true" url="/pages/tab-bar/main"></i-cell>
        <i-cell title="Tabs 标签页" is-link="true" url="/pages/tabs/main"></i-cell>
        <i-cell title="Drawer 抽屉" is-link="true" url="/pages/drawer/main"></i-cell>
        <i-cell title="Page 分页" is-link="true" url="/pages/page/main"></i-cell>
        <i-cell title="Steps 步骤条" is-link="true" url="/pages/steps/main"></i-cell>
        <i-cell title="NoticeBar 通告栏" is-link="true" url="/pages/notice-bar/main"></i-cell>
        <i-cell title="Index 索引选择器" is-link="true" url="/pages/index-list/main"></i-cell>
        <i-cell title="Sticky 吸顶容器" is-link="true" url="/pages/sticky/main"></i-cell>
      </i-cell-group>
    </i-panel>
    <i-panel title="操作反馈">
      <i-cell-group>
        <i-cell title="ActionSheet 动作面板" is-link="true" url="/pages/action-sheet/main"></i-cell>
        <i-cell title="Toast 轻提示" is-link="true" url="/pages/toast/main"></i-cell>
        <i-cell title="Modal 对话框" is-link="true" url="/pages/modal/main"></i-cell>
        <i-cell title="Message 全局提醒" is-link="true" url="/pages/message/main"></i-cell>
        <i-cell title="Spin 加载中" is-link="true" url="/pages/spin/main"></i-cell>
        <i-cell title="Swipeout 滑动菜单" is-link="true" url="/pages/swipeout/main"></i-cell>
      </i-cell-group>
    </i-panel>
    <i-panel title="视图">
      <i-cell-group>
        <i-cell title="Badge 徽章" is-link="true" url="/pages/badge/main"></i-cell>
        <i-cell title="Alert 警告提示" is-link="true" url="/pages/alert/main"></i-cell>
        <i-cell title="Tag 标签" is-link="true" url="/pages/tag/main"></i-cell>
        <i-cell title="Progress 进度条" is-link="true" url="/pages/progress/main"></i-cell>
        <i-cell title="Avatar 头像" is-link="true" url="/pages/avatar/main"></i-cell>
        <i-cell title="CountDown 倒计时" is-link="true" url="/pages/count-down/main"></i-cell>
        <i-cell title="Divider 分隔符" is-link="true" url="/pages/divider/main"></i-cell>
        <i-cell title="Collapse 折叠面板" is-link="true" url="/pages/collapse/main"></i-cell>
        <i-cell title="LoadMore 页底提示" is-link="true" url="/pages/load-more/main"></i-cell>
      </i-cell-group>
    </i-panel>
    <i-panel title="表单">
      <i-cell-group>
        <i-cell title="Input 输入框" is-link="true" url="/pages/input/main"></i-cell>
        <i-cell title="Radio 单选" is-link="true" url="/pages/radio/main"></i-cell>
        <i-cell title="Checkbox 复选" is-link="true" url="/pages/checkbox/main"></i-cell>
        <i-cell title="Switch 开关" is-link="true" url="/pages/switch/main"></i-cell>
        <i-cell title="Rate 评分" is-link="true" url="/pages/rate/main"></i-cell>
        <i-cell title="InputNumber 数字输入框" is-link="true" url="/pages/input-number/main"></i-cell>
      </i-cell-group>
    </i-panel>
  </div>
</template>

<script>
import panel from '../../components/panel/panel'
import cellGroup from '../../components/cell-group/cell-group'
import cell from '../../components/cell/cell'
export default {
  components: {
    'i-panel': panel,
    'i-cell-group': cellGroup,
    'i-cell': cell
  }
}
</script>

<style scoped>
.userinfo {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.userinfo-avatar {
  width: 128rpx;
  height: 128rpx;
  margin: 20rpx;
  border-radius: 50%;
}

.userinfo-nickname {
  color: #aaa;
}

.usermotto {
  margin-top: 150px;
}

.form-control {
  display: block;
  padding: 0 12px;
  margin-bottom: 5px;
  border: 1px solid #ccc;
}
.all{
  width:7.5rem;
  height:1rem;
  background-color:blue;
}
.all:after{
  display:block;
  content:'';
  clear:both;
}
.left{
  float:left;
  width:3rem;
  height:1rem;
  background-color:red;
}

.right{
  float:left;
  width:4.5rem;
  height:1rem;
  background-color:green;
}
</style>
