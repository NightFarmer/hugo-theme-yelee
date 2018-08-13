# hugo-theme-yelee

![](http://orh51lve9.bkt.clouddn.com/theme-yelee-hugo.png)  
基于hugo框架的主题，界面元素移植自hexo框架的[yelee](https://github.com/MOxFIVE/hexo-theme-yelee)  
效果：[NightFarmer'blog](https://www.nightfarmer.top/)

# 特性
- 日期归档
- 友链
- 关于我
- 标签云
- 文章目录
- 图片点击查看
- 代码高亮
- 背景图片切换
- 本站访问数量统计
- 支持畅言评论

# 安装
```
cd themes
git clone https://github.com/NightFarmer/hugo-theme-yelee.git
```

# 配置
这里使用json格式的config，你也可以依照下列配置改成你习惯的toml格式。
```json
{
  "disablePathToLower": true,
  "params": {
    "author": "NightFarmer",
    "title": "",
    "subtitle": "理论指导实践，实践深化理论",
    "description": "Tesla's Awesome Hugo Site",
    "root_url": "/",
    "avatar": "img/avatar.png",
    "tagcloud": true,
    "aboutme": "我就是我，是不一样的烟火",
    "friends": {
      "百度": "http://www.baidu.com",
      "GitHub": "http://www.baidu.com"
    },
    "subnav": {
      "Email": "mailto:nightfarmer@163.com",
      "GitHub": "https://github.com/NightFarmer"
    },
    "menu": [
      {
        "label": "主页",
        "link": "/"
      },
      {
        "label": "所有文章",
        "link": "/post/"
      },
      {
        "label": "标签云",
        "link": "/tags/"
      },
      {
        "label": "关于我",
        "link": "/about/"
      }
    ],
    "visit_counter": {
      "on": true,
      "site_visit": "本站到访数",
      "page_visit": "本页阅读量"
    },
    "background_image": 5,
    "fancybox": true,
    "open_in_new": true,
    "animate": false,
    "changyan": {
      "appid": "畅言appid",
      "conf": "畅言conf"
    }
  }
}

```
