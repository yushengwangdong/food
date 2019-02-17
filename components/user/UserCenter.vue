<template>
  <div>
    <!--用户中心样式-->
    <div class="user_style clearfix">
      <div class="user_center clearfix">
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
              <dl class="accountSideOption1">
                <dt class="transaction_manage">
                  <em class="icon_1"></em>订单管理
                </dt>
                <dd>
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
                <dt class="transaction_manage">
                  <em class="icon_2"></em>会员管理
                </dt>
                <dd>
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
                <dt class="transaction_manage">
                  <em class="icon_3"></em>账户管理
                </dt>
                <dd>
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
                <dt class="transaction_manage">
                  <em class="icon_4"></em>分销管理
                </dt>
                <dd>
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
          <!--浏览记录样式-->
          <div class="us_Records">
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
          </div>
        </div>
        <div class="right_style">
          <div class="info_content">
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
            <!--样式-->
            <div class="user_info_p_s clearfix">
              <!--订单记录-->
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
              <!--右侧记录样式-->
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
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!--收藏商品-->
            <div class="Collections_p">
              <div class="slideGroups">
                <div class="parHd">
                  <ul>
                    <li>收藏的商品</li>
                    <li>收藏的店铺</li>
                  </ul>
                </div>
                <div class="parBd">
                  <div class="Collect_Products">
                    <nuxt-link class="sPrev" to>&lt;</nuxt-link>
                    <ul>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_29.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li s>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_19.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_37.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_24.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_33.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_29.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_18.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_17.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_16.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_12.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_8.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_11.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="p_Price">￥32.50</div>
                      </li>
                    </ul>
                    <nuxt-link class="more" to>更多收藏</nuxt-link>
                  </div>
                  <div class="Collect_Products">
                    <ul>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_29.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li s>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_19.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_37.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_24.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_33.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_29.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_18.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_17.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_16.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>金龙鱼 东北大米 蟹稻共生 盘锦大米5KG</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_12.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>三只松鼠旗舰店</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_8.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>三只松鼠旗舰店</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                      <li>
                        <div class="pic">
                          <nuxt-link to>
                            <img src="~/assets/images/p_11.jpg">
                          </nuxt-link>
                        </div>
                        <div class="title">
                          <nuxt-link to>店铺名称是什么</nuxt-link>
                        </div>
                        <div class="shop_name">
                          <span>收藏：234</span>
                          <nuxt-link to>进入店铺</nuxt-link>
                        </div>
                      </li>
                    </ul>
                    <nuxt-link class="sNext" to>&gt;</nuxt-link>
                    <nuxt-link class="more" to>更多收藏</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
            <!--结束-->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import "@/assets/css/common.css";
@import "@/assets/css/style.css";
@import "@/assets/css/user_style.css";
</style>
