---
layout: post
title:  "CSS3 Tooltip"
date:  2015-05-11
categories: course_in_imooc
featured_image: /images/imooc.jpg
---

##CSS3 动画属性

---

###CSS3使用注意事项

**< meta > 标签**

- 使IE采用最新渲染模式，以支持CSS3效果


        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">


- 移动端处理：页面宽度=设备宽度，缩放为1，不放大


        <meta name="viewport" content="width=device-width,inital-scale=1">


###transform属性

- <span>功能</span>：向元素应用2D或者3D转换

- <span>语法</span>：transform: none | transform-function 

- <span>参数</span>：

        translate3d(x,y,z) //定义3D转化
    
        rotate3d(x,y,z,angle) //定义3D旋转
    
        scale3d(x,y,z,flex) //定义3D缩放

###transition属性

- <span>功能</span>：在一定时间区间内平滑地过度指定的属性值

- <span>语法</span>：transform: property duration timing-function delay 

- <span>参数</span>：

        property //规定设置过度效果的CSS属性名称
    
        duration //规定完成过度效果需要多少时间（秒或毫秒）
    
        timing-function //规定速度效果的速度曲线

        transition-delay //定义过度效果何时开始

###:after与:before用法

- <span>:after选择器</span>：在被选元素的内容后面插入内容

- <span>:before选择器</span>：在被选元素的内容前面插入内容

- <span>说明</span>： 需要使用content属性来指定要插入内容 

- <span>浏览器兼容</span>：对IE8及更早版本的:after，必须声明<!DOCTYPE>