<template>
  <div>
    <div class="right_user_recording">
      <div class="us_Record">
        <div id="Record_p" class="Record_p">
          <div class="title_name">
            <span class="name left">浏览历史</span>
            <span class="pageState right">
              <span>1</span>/9
            </span>
          </div>
          <div class="hd">
            <a class="next">&lt;</a>
            <a class="prev">&gt;</a>
            <nuxt-link class="next" to>&lt;</nuxt-link>
            <nuxt-link class="prev" to>&gt;</nuxt-link>
          </div>
          <div class="bd">
            <ul>
              <li class="clone">
                <div class="p_width" v-for="(item,idx) in tupian" :key="idx">
                  <div class="pic">
                    <nuxt-link to>
                      <img :src="item.url">
                    </nuxt-link>
                  </div>
                  <div class="title">
                    <nuxt-link to>{{item.name}}</nuxt-link>
                  </div>
                  <div class="Purchase_info">
                    <span class="p_Price">{{item.price}}</span>
                    <nuxt-link to class="Purchase">立即购买</nuxt-link>
                  </div>
                </div>
              </li>
              <!-- <li>
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
              <li class="clone">
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
              </li> -->
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tupian:[
        {
          url:'https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=1266593103,675503867&fm=26&gp=0.jpg', 
          name:'金龙鱼 东北大米 蟹稻共生 盘锦大米5KG',
          price:'￥32.50'
        },
        // {
        //   url:'https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=2429769380,2043935483&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=4279761023,3810140304&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1694871593,1386256631&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3578061646,2737580032&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3578061646,2737580032&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=2953177262,2417584225&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2302686985,1950680679&fm=26&gp=0.jpg'
        // },
        // {
        //   url:'https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=3705315266,3404394267&fm=26&gp=0.jpg'
        // }
      ]
    }
  },
};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
