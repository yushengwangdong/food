<template>
  <div>
    <div class="right_user_recording">
      <div class="us_Record">
        <div id="Record_p" class="Record_p">
          <div class="title_name">
            <span class="name left">浏览历史</span>
            <span class="pageState right"></span>
          </div>
          
            <div class="bd slide">
              <el-carousel arrow="always">
                <ul>
                  
                  <li class="clone">
                    
                    <div class="p_width">
                      <el-carousel-item v-for="(item,idx) in tupian" :key="idx" class="pic">
                      <nuxt-link to>
                        <img :src="item.url">
                      </nuxt-link>
                      <div class="title">
                        <nuxt-link to>{{item.name}}</nuxt-link>
                      </div>
                      
                      <div class="Purchase_info">
                        <span class="p_Price">{{item.price}}</span>
                        <nuxt-link to class="Purchase">立即购买</nuxt-link>
                      </div>
                      </el-carousel-item>
                    </div>
                   
                  </li>
                   
                </ul>
              </el-carousel>
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
      tupian: [
        {
          url:
            "https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=1266593103,675503867&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=2429769380,2043935483&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=4279761023,3810140304&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1694871593,1386256631&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3578061646,2737580032&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3578061646,2737580032&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=2953177262,2417584225&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2302686985,1950680679&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        },
        {
          url:
            "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=3705315266,3404394267&fm=26&gp=0.jpg",
          name: "金龙鱼 东北大米 蟹稻共生 盘锦大米5KG",
          price: "￥32.50"
        }
      ]
    };
  }
};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
