<template>
  <div>
     <div class="left_style">
    <div class="menu_style">
      <div class="user_title">
        <nuxt-link to="/user">用户中心</nuxt-link>
      </div>
      <div class="user_Head">
        <div class="user_portrait">
          <nuxt-link to class="btn_link"></nuxt-link>
          <img src="~/assets/images/people.png">
          <div class="background_img"></div>
        </div>
        <div class="user_name">
          <p>
            <span class="name">化海天堂</span>
            <nuxt-link to>[修改密码]</nuxt-link>
          </p>
          <p>访问时间：2016-1-21 10:23</p>
        </div>
      </div>
      <div class="sideMen">
        <!--菜单列表图层-->
        <dl class="accountSideOption1" >
          <dt class="transaction_manage" @click="isShow1 =! isShow1">
            <em class="icon_1"></em>订单管理
          </dt>
          <dd v-show="isShow1">
            <ul>
              <li>
                <nuxt-link to>我的订单</nuxt-link>
              </li>
              <li>
                <nuxt-link to>收货地址</nuxt-link>
              </li>
              <li>
                <nuxt-link to>产品预订</nuxt-link>
              </li>
            </ul>
          </dd>
        </dl>
        <dl class="accountSideOption1">
          <dt class="transaction_manage" @click="isShow2 =! isShow2">
            <em class="icon_2"></em>会员管理
          </dt>
          <dd v-show="isShow2">
            <ul>
              <li>
                <nuxt-link to>用户信息</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的收藏</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的留言</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的标签</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的推荐</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的评论</nuxt-link>
              </li>
            </ul>
          </dd>
        </dl>
        <dl class="accountSideOption1">
          <dt class="transaction_manage" @click="isShow3 =! isShow3">
            <em class="icon_3"></em>账户管理
          </dt>
          <dd v-show="isShow3">
            <ul>
              <li>
                <nuxt-link to>账户余额</nuxt-link>
              </li>
              <li>
                <nuxt-link to>消费记录</nuxt-link>
              </li>
              <li>
                <nuxt-link to>跟踪包裹</nuxt-link>
              </li>
              <li>
                <nuxt-link to>资金管理</nuxt-link>
              </li>
            </ul>
          </dd>
        </dl>
        <dl class="accountSideOption1">
          <dt class="transaction_manage" @click="isShow4 =! isShow4">
            <em class="icon_4"></em>分销管理
          </dt>
          <dd v-show="isShow4">
            <ul>
              <li>
                <nuxt-link to>店铺管理</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的盟友</nuxt-link>
              </li>
              <li>
                <nuxt-link to>我的佣金</nuxt-link>
              </li>
              <li>
                <nuxt-link to>申请提现</nuxt-link>
              </li>
            </ul>
          </dd>
        </dl>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {

data() {
  return {
    isShow1:false,
    isShow2:false,
    isShow3:false,
    isShow4:false
  }
},
methods: {
  
},

};
</script>



<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
