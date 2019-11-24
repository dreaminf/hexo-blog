---
title: NodeJS安装和配置环境
date: 2019-11-18 21:59:19
tags: NodeJS
---

## 下载

参照[官方网站](http://nodejs.cn/download/) 下载地址
{% img pic-names /images/node_install/node_site.png  700  500  "官方下载地址 '官方下载地址'" %}

## 安装

>+ windows 安装
>
---
>> *按照安装界面一步一步安装即可，注意配置环境变量的地方及设置安装目录的地方，如果C盘够大，或者不怕后期C盘空间小了之后，重装麻烦 就直接默认安装即可*
{% img pic-names /images/node_install/node1.png  500  400  "安装第一步 '安装第一步'" %}
{% img pic-names /images/node_install/node2.png  500  400  "安装第二步 '安装第二步'" %}
{% img pic-names /images/node_install/node3.png  500  400  "安装第三步 '安装第三步'" %}
{% img pic-names /images/node_install/node4.png  500  400  "安装第四步 '安装第四步'" %}
*检查安装是否成功*
{% img pic-names /images/node_install/node5.png  500  400  "安装第五步 '安装第五步'" %}

```nodejs
npm root -g #全局的node_module路径
```

---
>
>+ Linux 安装

## windwos 配置

### 在安装目录下 创建 node_global  和 node_caches 两个文件夹
 *默认这两个文件夹在用户目录下*

{% img pic-names /images/node_install/node6.png  500  400  "安装第六步 '安装第六步'" %}

```nodejs
npm config set prefix "file dir"
npm config set caches "file dir"

```

{% img pic-names /images/node_install/node7.png  500  400  "安装第七步 '安装第七步'" %}

### 配置环境变量  *系统环境变量* path

{% img pic-names /images/node_install/node8.png  500  400  "安装第8步 '安装第8步'" %}

{% img pic-names /images/node_install/node5.png  500  400  "安装第9步 '安装第9步'" %}

## 常见问题
