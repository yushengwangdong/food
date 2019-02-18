<template>
  <div>
    <div class="Collections_p">
      <div class="slideGroups">
        <div class="parHd">
          <ul>
            <li>收藏的商品</li>
            <li>收藏的店铺</li>
          </ul>
        </div>
  
        <div class="parBd" style="width:980px">
          <el-carousel class="Collect_Products" type="card" :interval="4000"  arrow="always">
            <ul>
            <el-carousel-item v-for="(item,idx) in collect" :key="idx">
              <li style="width:167px" >
                <div class="pic">
                  <nuxt-link to="">
                      <img :src="item.url">
                  </nuxt-link>
                </div>
                <div class="title">
                  <nuxt-link to="">{{item.name}}</nuxt-link>
                </div>
                <div class="p_Price">{{item.price}}</div>
              </li>
              </el-carousel-item>
            </ul>
            <nuxt-link class="more" to="">更多收藏</nuxt-link>
          </el-carousel>
          <!-- <div class="Collect_Products">
            
            <ul>
              <li>
                <div class="pic">
                  <a href>
                    <img src="Products/P_29.jpg">
                  </a>
                </div>
                <div class="title">
                  <a href="#">金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</a>
                </div>
                <div class="shop_name">
                  <span>收藏：234</span>
                  <a href="#">进入店铺</a>
                </div>
              </li>
            </ul>
            
            <a href="#" class="more">更多收藏</a>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            collect:[
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
        }
    },
};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
