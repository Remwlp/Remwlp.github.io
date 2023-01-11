---
title: test图库
date: 2023-01-11 17:16:50
updated:
comments:
description:
keywords:
top_img: '/image/cover.jpg'
mathjax:
katex:
aside:
aplayer:
highlight_shrink:
---

## 简单测试
### 真的简单测试


{% gallery %}
![](https://i.loli.net/2019/12/25/mh19anwBSWIkGlH.jpg)
![](https://i.loli.net/2019/12/25/2tu9JC8ewpBFagv.jpg)
{% endgallery %}

hello

## 提示块
{% note simple %}
默认 提示块标签
{% endnote %}

{% note default simple %}
default 提示块标签
{% endnote %}

{% note primary simple %}
primary 提示块标签
{% endnote %}

{% note success simple %}
success 提示块标签
{% endnote %}

{% note info simple %}
info 提示块标签
{% endnote %}

{% note warning simple %}
warning 提示块标签
{% endnote %}

{% note danger simple %}
danger 提示块标签
{% endnote %}


## tab表
{% tabs test1 %}
<!-- tab -->
**This is Tab 1.**
<!-- endtab -->

<!-- tab -->
**This is Tab 2.**
<!-- endtab -->

<!-- tab -->
**This is Tab 3.**
<!-- endtab -->
{% endtabs %}


## 高亮文字
臣亮言：{% label 先帝 %}创业未半，而{% label 中道崩殂 blue %}。今天下三分，{% label 益州疲敝 pink %}，此诚{% label 危急存亡之秋 red %}也！然侍衞之臣，不懈于内；{% label 忠志之士 purple %}，忘身于外者，盖追先帝之殊遇，欲报之于陛下也。诚宜开张圣听，以光先帝遗德，恢弘志士之气；不宜妄自菲薄，引喻失义，以塞忠谏之路也。
宫中、府中，俱为一体；陟罚臧否，不宜异同。若有{% label 作奸 orange %}、{% label 犯科 green %}，及为忠善者，宜付有司，论其刑赏，以昭陛下平明之治；不宜偏私，使内外异法也。


## 时间线
{% timeline 2022 %}
<!-- timeline 01-02 -->
这是测试页面
<!-- endtimeline -->
{% endtimeline %}

## 友链
{% flink %}
- class_name: 友情链接
  class_desc: 
  link_list:
    - name: 果壳儿
      link: https://gkder.ucas.ac.cn/
      avatar: https://gkder.ucas.ac.cn/assets/logo-gxt0kdw0.png
      descr: 正经国科大论坛
    
    - name: 小V罢了
      link: https://youtube.com/@AmaneKanata
      avatar: https://yt3.ggpht.com/TlH8nz5O9UYo5JZ_5fo4JfXdT18N0Ck27wWrulni-c1g5bwes0tVmFiSKICzI1SW7itaTkk9GA=s88-c-k-c0x00ffffff-no-rj
      descr: Kanataso

- class_name: 网站
  class_desc: 值得推荐的网站
  link_list:
    - name: Youtube
      link: https://youtube.com/@AmaneKanata
      avatar: https://i.loli.net/2020/05/14/9ZkGg8v3azHJfM1.png
      descr: 值得一看的vtuber
{% endflink %}
