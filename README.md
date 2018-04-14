订阅阅读器测试项目


一、项目概述

  1.本项目是一个基于Web的RSS反馈阅读应用程序的测试项目；
  
  2.项目采用Jasmine实现测试。测试内容包括应用程序底层业务逻辑、事件处理和DOM操作；
  
  3.编写测试时一项重要的技能，优秀的测试能够快速分析出新代码是否对代码库中的现有功能造成破坏，免去手动测试工作。
  
  
二、项目运行方式

  直接在浏览器中运行index.html即可。
  

三、项目说明

  1.项目使用了JQuery库，模板引擎为Handlebars，并包含google的jsapi以供使用；
  
  2.Jasmine测试用例覆盖了数据数组allFeeds，菜单栏，数据源feed的加载与更新等；
  
  3.用户可通过观察页面Jasmine提示信息，来确认是否所有的spec成功执行。
  
   ![image](https://github.com/dingbf/udacity-project02/blob/master/jasmine-info.png)
