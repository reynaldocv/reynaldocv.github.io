---
id: "projects"
title:  "Projects"
short:  "Projects"
icon: fa-copyright
sort_by_number: 5
---
<div class="w3-row-padding" style="margin:0 -16px">
{% for item in site.data.projects %}    
      <div class="w3-third">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-large w3-padding-8">{{item.title}}</li>
          <li class="w3-padding-16">{{item.description}}</li>
          <li class="w3-padding-16">{{item.software}}</li>                   
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Sign Up</button>
          </li>
        </ul>
      </div>
{% endfor %}
    </div>

<img src="/w3images/bandmember.jpg" alt="Avatar" class="w3-left w3-black w3-circle w3-margin-right" style="width:80px">
<p><span class="w3-large w3-margin-right">Chris Fox.</span> CEO at Mighty Schools.</p>
<p>John Doe saved us from a web disaster.</p><br>    
<img src="/w3images/avatar_g2.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
<p><span class="w3-large w3-margin-right">Rebecca Flex.</span> CEO at Company.</p>
<p>No one is better than John Doe.</p>


    > [!CAUTION]
    > Advises about risks or negative outcomes of certain actions.




1. Here's a thing
    ```
    with.some(code)
    ```
    > [!NOTE] 
    > The variable code is defined in foo.bar
1. Next, frogblast the vent cores
