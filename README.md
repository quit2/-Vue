## android和ios webview 如何调用vuejs中methods事件
> created里面添加
window.functionName=this.functionName;

## 动态设置title
- webpack: "vue-wechat-title": "^2.0.4"
- 路由配置：

        {
          path: '/shop-manage',
          component: ShopManage,
          meta: {
            title: '商品管理'
          },
          children: [
            {
              path: ':id',
              component: GoodDetail,
              meta: {
                title: '商品详情'
              }
            }
          ]
        }

就ok了

## 改变路径  router/index.js
路径设置： mode: 'history'

## better-scroll
https://ustbhuangyi.github.io/better-scroll/doc/
