---
id: "blogs"
title: "Blogs"
short: "Blogs"
icon: fa-book
sort_by_number: 6 
---
<div class="w3-row-padding">
{% for item in site.data.blogs %}    
      <div class="w3-half projects">
            <a href="{{ item.url }}"> {{item.title}} </a>        
      </div>
{% endfor %}
</div>

