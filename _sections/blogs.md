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
        <ul class="w3-ul w3-blue w3-center w3-hover-opacity-off">
          <li class="w3-large">
            <a href="{{ item.url }}"> {{item.title}} </a>
          </li>
        </ul>
      </div>
{% endfor %}
</div>

