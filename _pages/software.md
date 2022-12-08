---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

## Software


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Sapicore: A PyTorch-based framework for neuromorphic modeling</b></h4>
<a href="https://pypi.org/project/sapicore/#description" target="_blank"><button class="btn btn-primary btn-sm">PyPi: Sapicore</button></a>
<!--<a href="https://github.com/sbryngelson/PyQBMMlib" target="_blank"><button class="btn btn-primary btn-sm">GIT: PyQBMMLIB</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-SoftX-20.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> -->

<b>Author:</b>
<i> Matthew Einhorn, Ayon Borthakur, Thomas Cleland</i>

Sapicore was developed as a project of the Computational Physiology Laboratory at Cornell University. It is a framework that provides high level abstractions to help write neuromorphic models using pytorch. Sapicore itself does not contain any concrete models, instead each model may have its own repo that implements the Sapicore components used by the model.
