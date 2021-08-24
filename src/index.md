---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 简历主题,Hexo主题,简历模板
description: 
# 简历标题
resume_title: FAFUCS-大学四年攻略-计算机方向
# 应聘者姓名
name: CS-strategy
avatar: https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/avatar/avatar.png
# 联系方式
contact:
  - icon: fas fa-globe-asia
    text: efafucs.com
    url: https://efafucs.com/dist/index.html
  # 邮箱
  - icon: fas fa-envelope
    text: luyuhong_fafu@163.com
    url:
# PDF下载链接
---

<!-- {% raw %}
<center>
<a href='/'>简体中文</a> | <a href='/zh-cn/'>English</a>
</center>
{% endraw %} -->


## 前言
<font size = 4 font-family= Microsoft YaHei>
&emsp;&emsp;经过大学四年，踩了许多坑，越来越有感觉有一个<font color=red>明确的计划</font>和<font color=red>消除信息差</font>是决定大学四年发展好坏的决定性因素，因此找到了都出身于农大的各方向的人才写了这篇攻略，希望学弟学妹们可以更好的发展。<br>

&emsp;&emsp;由于大部分写者是毕业0~3年的同学和少部分高年级的同学，水平有限，因此以下攻略的观念仅代表各作者的个人观念，希望读者辩证地看待本文的内容。

&emsp;&emsp;由于内容较多，推荐<font color=red>电脑端阅读</font>，全文4w字，阅读大概25分钟
</font>




## <i class="fas fa-flag"></i> 开始使用

由于本主题与普通 Hexo 主题有较大区别，建议请直接下载本站的源码，参考源码进行改写。

- 本站源码：https://github.com/xaoxuu/resume-docs
- 主题源码：https://github.com/xaoxuu/hexo-theme-resume

也可以创建全新的博客，通过 `npm` 命令安装：

```bash
npm i hexo-theme-resume
```

然后删除多余的依赖包（重要），打开 `package.json` 复制并全部替换为以下内容：

```json
{
  "name": "hexo-site",
  "private": true,
  "hexo": {
    "version": "5.0.0"
  },
  "scripts": {
    "start": "hexo server",
    "build": "node pre-deploy.js && hexo clean && hexo generate",
    "deploy": "npm run build && hexo deploy"
  },
  "engines": {
    "node": ">=8.9.0"
  },
  "dependencies": {
    "hexo": "^5.0.0",
    "hexo-all-minifier": "^0.5.3",
    "hexo-autonofollow": "^1.0.1",
    "hexo-deployer-git": "^2.1.0",
    "hexo-fs": "^3.1.0",
    "hexo-lazyload-image": "^1.0.9",
    "hexo-offline": "^1.0.0",
    "hexo-renderer-ejs": "^1.0.0",
    "hexo-renderer-marked": "^3.0.0",
    "hexo-renderer-stylus": "^1.1.0",
    "hexo-server": "^1.0.0"
  }
}
```

然后输入 `npm i` 安装依赖包。

## <i class="fas fa-user-graduate"></i> 教育背景

**XX大学 X学院 X系 X专业 X年毕业**


## <i class="fas fa-user-tie"></i> 工作经验


#### 2000年 ~ 至今：XX公司

- 主要负责XXX
- 也负责XXX


#### 1900年 ~ 2000年：XX公司

- 主要负责XXX
- 也负责XXX

#### 1800年 ~ 1900年：XX公司

- 主要负责XXX
- 也负责XXX


## <i class="fas fa-award"></i> 精选项目


{% raw %}
<btns rounded>
<a href='https://apps.apple.com/cn/app/heart-mate-pro-hrm-utility/id1463348922?ls=1'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/heartmate/icon.png'>
  心率管家
</a>
<a href='https://apps.apple.com/cn/app/c%E5%85%BB%E8%80%81/id1458315594'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-cyanglao/icon.png'>
  C养老
</a>
<a href='https://apps.apple.com/cn/app/c-life%E5%85%BB%E8%80%81/id1393937890'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-clife/icon.png'>
  C-Life养老
</a>
<a href='https://apps.apple.com/cn/app/linksmart/id1109303355'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-linksmart/icon.png'>
  LinkSmart
</a>
<a href='https://apps.apple.com/cn/app/hitfit/id1207738581'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-hitfit/icon.png'>
  HitFit
</a>
<a href='https://apps.apple.com/cn/app/%E8%85%95%E8%83%BD%E5%8A%A9%E6%89%8B/id1138242219'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-fiyta/icon.png'>
  飞亚达腕能助手
</a>
</btns><br>
{% endraw %}


### A项目

#### 2000/01 ~ 2019/01：于XX公司开发，团队项目，维护至今

啦啦啦

### B项目

#### 1900/01 ~ 2000/01：于XX公司开发

啦啦啦

### C项目

#### 1800/01 ~ 1900/01：于XX公司开发

啦啦啦

## <i class="fab fa-github"></i> 开源贡献


### Volantis

#### 2017 ~ 至今，一个简约的卡片式Hexo博客主题

- 完全自由的模块化、易于定制化设计
- 移动端优化
- 源码：https://github.com/xaoxuu/hexo-theme-volantis
- 官网：https://volantis.js.org/

### ProHUD

#### 2019/08 ~ 至今，易于定制、接口简单的HUD库

- 使用Swift5编写。
- 包含顶部通知横幅、弹窗、底部操作表三种使用场景的UI控件。
- 易于配置UI从而满足公司各业务线的UI要求，接口调用简单明了。
- 源码：https://github.com/xaoxuu/ProHUD

<fancybox>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot01.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot02.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot03.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot04.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot05.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot06.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot07.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot08.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot09.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot10.png'>
</fancybox>

## <i class="fas fa-phone-alt"></i> 与我联系

目前状态为：在职，考虑换工作，100年内可到岗。

<i class="fas fa-envelope fa-fw"></i> your email
<i class="fas fa-phone-alt fa-fw"></i> 1xxxxxxxxxx


## 主题配置

```yaml
cdn:
  # These base libraries cannot be deleted
  jquery: https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js
  vue: https://cdn.jsdelivr.net/npm/vue@2.5.21/dist/vue.min.js
  # When these CDN resources are deleted, local resources are loaded.
  common: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/common.js
  escape: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/css.escape.js
  smooth_scroll: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/smooth-scroll.min.js
  css: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/css/style.min.css
  # Optional plug-in: image zoom
  fancybox:
    css: https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.css
    js: https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.js

# robots meta tag
robots: noindex,nofollow

# the footer of your site
copyright: '[Copyright © 2017-2020 Mr. X](https://xaoxuu.com)'
```

## 评论

{% raw %}
<script src="https://utteranc.es/client.js"
        repo="xaoxuu/hexo-theme-resume"
        issue-number="18"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
{% endraw %}
