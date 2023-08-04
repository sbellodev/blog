---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: portfolio
title: "Santi Bello"
---
  
![profile image]({{ site.baseurl }}/assets/img/perfil.jpg){: .profile-img .text-center #index}

## SANTI BELLO
{: .font-endless .text-right}
## SOFTWARE DEVELOPER 
{: .font-endless .text-right .span}
## AT [NEWTONLAB SPACE][exp6] 
{: .font-endless .text-right .size-medium}

<br/>
<br/>

{% for post in site.posts %}
[{{ post.title }}]({{ '/blog' | append: post.url }}) - {{ post.date | date: "%D" }}
{: .date}
{% endfor %}

[exp6]: https://newtonlabspace.com/