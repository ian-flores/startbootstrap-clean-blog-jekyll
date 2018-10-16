---
layout: post
title:  "Tutorial - Data Wrangling, Visualization and Inference with Social Data"
subtitle: "Learning how to use python to answer questions about the effect of Hurricane Maria in Puerto Rico"
author: "Ian Flores Siaca"
date:   2018-10-15
background: '/img/posts/puerto_rico_death_choropleth.png'
---

This tutorial is based on the blog post in this webpage: [https://www.bayesianpolitik.me/2018/10/16/analysis_hurricane.html](https://www.bayesianpolitik.me/2018/10/16/analysis_hurricane.html)

> DISCLAIMER: I'm trying this new thing of the tutorials for the analyses I will be making now on as blog posts. It would be nice/helpful if I could get feedback. All kinds of feedbacks are welcomed. Feel free to use the Contact tab to contact me. 

Notebook Content: 

* #1) Getting and Cleaning Census Data
	* How to get data from the census
	* How to extract and manipulate data coming from a single table
* #2) Getting and Cleaning Mortality Data
	* Cleaning data
	* Dealing with strings in Spanish
	* Grouping, summarizing, and splitting by different variables
* #3) Mapping Mortality Rates
	* Creating maps in Python
	* Joining data from different sources
	* Dealing with spatial data in Python
* #4) Estimating Mortality Rates in Puerto Rico
	* Bayesian Estimation with `PyMC3`
	* How to draw conclusions from data
	
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
		<a class="nav-link" href="#4" data-toggle="tab">Estimating Mortality Rates in Puerto Rico</a></li>
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
