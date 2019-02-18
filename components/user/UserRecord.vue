<template>
    <div>
        <div class="left_user_cont">
                <div class="us_Orders left clearfix">
                  <div class="Orders_name">
                    <div class="title_name">
                      <div class="Records">购买记录</div>
                      <div class="right select">只记录你最近30天的购买记录</div>
                    </div>
                  </div>
                  <table>
                    <thead>
                      <tr>
                        <th>产品名称</th>
                        <th>数量</th>
                        <th>状态</th>
                        <th>操作</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td class="img_link">
                          <nuxt-link class="img" to>
                            <img src="~/assets/images/p_58.jpg" width="80" height="80">
                          </nuxt-link>
                          <nuxt-link
                            class="title"
                            to
                          >雅诗兰黛（Estee Lauder）弹性紧实柔肤眼霜15ml(又名弹性紧实眼霜)（提拉紧致 保湿补水 淡化细纹）</nuxt-link>
                        </td>
                        <td>2</td>
                        <td>完成</td>
                        <td>
                          <nuxt-link class="View" to>查看</nuxt-link>
                        </td>
                      </tr>
                      <tr>
                        <td class="img_link">
                          <nuxt-link class="img" title="山东红富士苹果" to>
                            <img src="~/assets/images/p_2.jpg" width="80" height="80">
                          </nuxt-link>

                          <i class="icon-copy"></i>

                          <nuxt-link class="img" title="进口澳洲苹果" to>
                            <img src="~/assets/images/p_3.jpg" width="80" height="80">
                          </nuxt-link>
                          <i class="icon-copy"></i>
                          <nuxt-link class="img" title="进口水果" to>
                            <img src="~/assets/images/p_4.jpg" width="80" height="80">
                          </nuxt-link>
                        </td>
                        <td>2</td>
                        <td>完成</td>
                        <td>
                          <nuxt-link class="View" to>查看</nuxt-link>
                        </td>
                      </tr>
                      <tr>
                        <td class="img_link">
                          <nuxt-link class="img" title="山东红富士苹果" to>
                            <img src="~/assets/images/p_2.jpg" width="80" height="80">
                          </nuxt-link>
                          <i class="icon-copy"></i>
                          <nuxt-link class="img" title="进口水果" to>
                            <img src="~/assets/images/p_24.jpg" width="80" height="80">
                          </nuxt-link>
                        </td>
                        <td>2</td>
                        <td>完成</td>
                        <td>
                          <nuxt-link class="View" to>查看</nuxt-link>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                  <div class="us_jls">共2条记录</div>
                </div>
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
