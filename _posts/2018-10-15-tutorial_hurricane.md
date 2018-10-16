---
layout: post
title:  "Tutorial - Data Wrangling, Visualization and Inference with Social Data"
subtitle: "Learning how to use python to answer questions about the effect of Hurricane Maria in Puerto Rico"
author: "Ian Flores Siaca"
date:   2018-10-15
background: '/img/posts/puerto_rico_death_choropleth.png'
---
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

<div class="container">
	<ul class="nav nav-tabs">
	<li class="nav-item">
          	<a class="nav-link active" href="#1" data-toggle="tab">Getting and Cleaning Census Data</a></li>
	<li>
		<a class="nav-link" href="#2" data-toggle="tab">Getting and Cleaning Mortality Data</a></li>
	<li>
		<a class="nav-link" href="#3" data-toggle="tab">Mapping Mortality Rates</a></li>
	<li>
		<a class="nav-link" href="#4" data-toggle="tab">Notebook 04</a></li>
	</ul>

	<div class="tab-content ">
		<div class="tab-pane active" id="1">
			{% include tutorials/hurricane_maria/notebook_01.html %}

		</div>
		<div class="tab-pane" id="2">
			{% include tutorials/hurricane_maria/notebook_02.html %}
		</div>
        	<div class="tab-pane" id="3">
			{% include tutorials/hurricane_maria/notebook_03.html %}		
		</div>
	        <div class="tab-pane" id="4">
        		{% include tutorials/hurricane_maria/notebook_04.html %}
		</div>
	</div>
</div>
