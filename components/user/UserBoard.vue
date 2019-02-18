<template>
    <div>
        <div class="Notice">
              <span>系统最新公告:</span>为了更好地服务于【每日鲜】的会员朋友及读者 发表意见。
            </div>
            <div class="user_info">
              <ul class>
                <li class="Balance">
                  <nuxt-link to>
                    <img src="~/assets/images/user_img_05.png">
                    <h4>余额：￥54.00</h4>
                  </nuxt-link>
                </li>
                <li class="Order_form">
                  <nuxt-link to>
                    <img src="~/assets/images/user_img_04.png">
                    <h4>订单：(5)</h4>
                  </nuxt-link>
                </li>
                <li class="grade">
                  <nuxt-link to>
                    <img src="~/assets/images/user_img_08.png">
                    <h4>3</h4>
                  </nuxt-link>
                </li>
                <li class="Favorable">
                  <nuxt-link to>
                    <img src="~/assets/images/user_img_07.png">
                    <h4>钻石会员</h4>
                  </nuxt-link>
                </li>
                <li class="integral">
                  <nuxt-link to>
                    <img src="~/assets/images/user_img_06.png">
                    <h4>234分</h4>
                  </nuxt-link>
                </li>
              </ul>
            </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
