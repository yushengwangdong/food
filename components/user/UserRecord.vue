<template>
  <div>
    <div class="left_user_cont">
      <div class="us_Orders left clearfix" >
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
          <tbody v-for="(item,idx) in list" :key="idx">
            <tr >
              <td class="img_link">
                <nuxt-link class="img" to>
                  <img :src="item.url" width="80" height="80">
                </nuxt-link>
                <nuxt-link class="title" to>{{item.name}}</nuxt-link>
              </td>
              <td>{{item.mount}}</td>
              <td>{{item.status}}</td>
              <td>
                <nuxt-link class="View" to>查看</nuxt-link>
              </td>
            </tr>
          </tbody>
        </table>
        <div class="us_jls">共{{list.length}}条记录</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      list: [
        {
          url: "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1272135895,2701617378&fm=26&gp=0.jpg",
          name:
            "雅诗兰黛（Estee Lauder）弹性紧实柔肤眼霜15ml(又名弹性紧实眼霜)（提拉紧致 保湿补水 淡化细纹）",
          mount: "2",
          status: "完成"
        },
        {
          url: "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1272135895,2701617378&fm=26&gp=0.jpg",
          name:
            "雅诗兰黛（Estee Lauder）弹性紧实柔肤眼霜15ml(又名弹性紧实眼霜)（提拉紧致 保湿补水 淡化细纹）",
          mount: "2",
          status: "完成"
        },
        {
          url: "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1272135895,2701617378&fm=26&gp=0.jpg",
          name:
            "雅诗兰黛（Estee Lauder）弹性紧实柔肤眼霜15ml(又名弹性紧实眼霜)（提拉紧致 保湿补水 淡化细纹）",
          mount: "2",
          status: "完成"
        }
      ],
      
    };
  },
  methods: {}
};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
