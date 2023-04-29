---
layout: page
title: "Statements"
permalink: /statements/
---

Our recent statements will appear here.


<div class = "row my-8">
  <div class = "col-15">
    <h6 class = "my-1 text-black-tint-2"> {{ "%4 %-27 %2020" }} </h6>
    <a class="my-0 article-link" href="{{ [(https://www.dailyprincetonian.com/article/2023/04/princeton-workers-pay-conditions-cost-of-living-wages) 
                                       }}">{{ The invisible and ignored struggles of Princeton’s service workers }}</a>
    <p>{{ Testing }}</p>
  </div>
</div>
  


<div class="row my-5">
  {% for post in site.posts %}
    <div class="col-12">
      <h6 class="my-0 text-black-tint-2">{{ post.date | date: "%b %-d, %Y" }}</h6>
      <a class="my-0 article-link" href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.short_description }}</p>
    </div>
  {% endfor %}
</div>

