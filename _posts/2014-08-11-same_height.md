---
layout: default
title: 等高左中右结构
---

##{{ page.title }}

利用chrome或者Firefox的开发者工具在线编辑下方的“左、中、右”结构，会发现他们是自适应等高的：  
<style>
.wrap{width:706px;margin:auto;overflow:hidden;}
.col-a,.col-b,.col-c{float:left;padding-bottom:1000px;margin-bottom:-1000px;}
.col-a,.col-c{width:100px;}
.col-a{background:#999;}
.col-c{background:#aaa;}
.col-b{width:500px;background:#ccc;}
</style>
 
<div class="wrap">
    <div class="col-a">
        左<br>
        左<br>
        左<br>
    </div>
    <div class="col-b">中</div>
    <div class="col-c">右</div>
</div>



日期：{{ page.date | date_to_string }}  

