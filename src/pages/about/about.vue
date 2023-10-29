<template>
  <view class="page-common">
    <user-bar />
    <menu-item-text class="page-title" icon-src="../../images/menu-dices/about-dice.svg" btn-color="#FFFFFF">关于</menu-item-text>
    <text class="rule-text">
      开发工具：微信开发者工具
    </text>
    <text class="rule-text">
      原型设计：figma
    </text>
    <text class="rule-text">
      图标素材：figma community、iconfont
    </text>
    <text class="rule-text">
      开发者：福州大学计算机软工k班underdog
    </text>
    <view class="flex-fill" />
    <view class="navigator-area">
      <navigator open-type="navigateBack">
        <image class="navigator-back" src="../../images/navigator-btn/back-btn.svg" />
      </navigator>
    </view>
  </view>
</template>

<script setup>
import userBar from '../../components/common/user-bar.vue'
import menuItemText from '../../components/common/menu-item-text.vue'
import '../../style/common.css'
import './about.css'
</script>
