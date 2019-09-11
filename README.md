GULU这是一个UI组件

[![Build Status](https://travis-ci.org/chenximan/gulu.svg?branch=master)](https://travis-ci.org/chenximan/gulu)

介绍
这是我在学习Vue过程中做的一个UI组件，希望对你有用。
开始使用
1.添加CSS样式

   使用本框架前，请在CSS中开启border-box

   ```$xslt
   *,*::before,*::after{box-sizing: border-box;}
   ```
   IE8 以上浏览器支持此样式
   你还需要设置默认颜色等变量后续会改为SCSS变量。
   ```$xslt
     html {
               --button-height: 32px;
               --font-size: 14px;
               --button-bg: white;
               --button-active-bg: #eee;
               --border-radius: 4px;
               --color: #333;
               --border-color: #999;
               --border-color-hover: #666;
           }
   ```
   IE15 以上浏览器支持此样式
 
 2.安装 gulu
    ```$xslt
    npm i --save chenximan
    ```
 3.引入gulu
    ```$xslt
    import {Button, ButtonGroup, Icon} from 'chenximan'
    import 'frank-test-1-1/dist/index.css'

    export default {
      name: 'app',
      components: {
        'g-button': Button,
        'g-icon': Icon
      }
    }
    ```
 
##文档

##提问

##变更记录

##联系方式

##贡献代码




作者：我

