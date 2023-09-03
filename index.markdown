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
Soy un desarrollador con más de 2 años de experiencia en el mundo del desarrollo de software.
En este espacio, compartiré mis conocimientos y experiencias: Te llevaré detrás de escena de mis <span>proyectos</span>, exploraremos <span>desafíos técnicos</span>, y aprenderemos juntos cómo resolver problemas del día a día.
<br/>

{% for post in site.posts %}
[{{ post.title }}]({{ '/blog' | append: post.url }}) - {{ post.date | date: "%D" }}
{: .date}
{% endfor %}

[exp6]: https://newtonlabspace.com/