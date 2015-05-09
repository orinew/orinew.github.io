---
layout: post
title: Orinew's Blog
keywords: begining
description: 
---
{% include codepiano/setup %}


<div class="row-fluid typo">
  <div class="span9" >
    {% assign posts_list = site.posts %}  
    {% include codepiano/timeline %}
  </div>
  <div id="time-list-nav" class="span3">
    <ul id="time-list-ul" class="nav nav-tabs nav-stacked time-list affix">
      {% include codepiano/time_list %}
      {% assign posts_list = nil %}
    </ul>
  </div>
</div>