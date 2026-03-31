---
id: "education"
short: "Education"
title: "Education"
icon: fa-graduation-cap
sort_by_number: 1 
---

{% for item in site.data.educations %}  
- <table style="border:0px" class="w3-table-all">
    <tr>
      <td> {{item.university}} 
        (<a href="{{item.university_url}}">{{item.university_short}}</a>)
      </td>
      <td style='text-align:right'>{{item.city}}</td>
    </tr>
    <tr>
      <td><b>{{item.degree}} </b></td>      
      <td style='text-align:right'>{{item.start}} - {{item.end}}</td>
    </tr>
    <tr>
      <td><b>{{item.thesis_label}}</b> <a href="{{item.thesis_url}}">{{item.thesis}}</a></td>      
      <td style='text-align:right'><b>{{item.adviser_label}}</b> 
      <a href="{{item.adviser_url}}">{{item.adviser}}</a></td>
    </tr>   
  </table>     
{% endfor %}
