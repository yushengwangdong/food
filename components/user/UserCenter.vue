<template>
  <div>
    <!--用户中心样式-->
    <div class="user_style clearfix">
      <div class="user_center clearfix">

          <usernav></usernav>
          <!--浏览记录样式-->
          <!-- <div class="us_Records">
            <div id="Record_ps" class="Record_p">
              <div class="title_name">
                <span class="name left">浏览历史</span>
                <span class="pageState right"></span>
              </div>
              <div class="hd">
                <nuxt-link to>&lt;</nuxt-link>
                <nuxt-link to>&lt;</nuxt-link>
              </div>
              <div class="bd">
                <ul>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_1.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_12.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_23.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_4.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_5.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_8.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_1.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_6.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="p_width">
                      <div class="pic">
                        <nuxt-link to>
                          <img src="~/assets/images/p_11.jpg">
                        </nuxt-link>
                      </div>
                      <div class="title">
                        <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                      </div>
                      <div class="Purchase_info">
                        <span class="p_Price">￥32.50</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div> -->
        <div class="right_style">
          <div class="info_content">
            <userboard></userboard>
            <!--样式-->
            <div class="user_info_p_s clearfix">
              <!--订单记录-->
              <userrecord></userrecord>
              <!--右侧记录样式-->
              <userhistory></userhistory>
            </div>
            <!--收藏商品-->
            <usercollect></usercollect>
            <!--结束-->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import usernav from '@/components/user/UserNav.vue';
import userboard from '@/components/user/UserBoard.vue';
import userrecord from '@/components/user/UserRecord.vue';
import userhistory from '@/components/user/UserHistory.vue';
import usercollect from '@/components/user/UserCollect.vue';
export default {
    components:{
        usernav,
        userboard,
        userrecord,
        userhistory,
        usercollect
    }
};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
