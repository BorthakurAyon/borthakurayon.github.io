---
title: "Talks & Posters"
layout: gridlay
sitemap: false
permalink: /talks & posters/
---

<style>
.btn{
    margin-bottom:5px;
    padding-top:1px;
    padding-bottom:1px;
    padding-left:15px;
    padding-right:15px;
}
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
<!--### Invited talks
{% bibliography --query @incollection[keywords ^= invited] %}
</div>-->

<div class="jumbotron">
### Selected Talks & Posters
{% bibliography --query @incollection[keywords != invited] %}
</div>

