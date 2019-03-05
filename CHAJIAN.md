#插件




gitbook支持许多插件，用户可以从[NPM](https://www.npmjs.com/)上搜索gitbook相关的插件

gitbook的插件信息会保存在`book.json`文件里


以下是本书用到的插件：

gitbook-plugin-donate(打赏按钮):[https://www.npmjs.com/package/gitbook-plugin-donate](https://www.npmjs.com/package/gitbook-plugin-donate)

gitbook-plugin-github-buttons(GitHub按钮):[https://www.npmjs.com/package/gitbook-plugin-github-buttons](https://www.npmjs.com/package/gitbook-plugin-github-buttons)

gitbook-plugin-edit-link(GitHub编辑按钮):[https://www.npmjs.com/package/gitbook-plugin-edit-link](https://www.npmjs.com/package/gitbook-plugin-edit-link)



###以下是book.json中供参考的代码

```
  {
     "title":"编写gitbook电子书简单引导",
     "description":"gitbook简单电子书",
     "author":"wangshuaishuai",
     "language":"zh-hans",

     "plugins":[
         "donate",
         "github-button@2.1.0",
         "edit-link"
     ],

     "pluginsConfig":{
       "donate":{
           "wechat":"https://xxx.com/xxx/xxxx.jpg",
           "alipay":"https://xxx.com/xxx/xxxx.jpg",
           "title":""
           "button":"打赏",
           "alipayText":"支付宝打赏",
           "wechatText":"微信打赏"
       },
       "github-buttons":{
          "repo":"githubname/githubcangku"
            "types":[
            "star"
            ],
            "size":"small"
       },
       "edit-link":{
       "base":"你仓库电子书页面地址"，
       "label":"Edit this page"
       }
     },
     
   }

  ```
 ###GGGGG
