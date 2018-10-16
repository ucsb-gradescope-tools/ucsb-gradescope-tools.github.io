---
layout: default
---


<div id="info" data-role="collapsible" data-collapsed="false">
<h2>Topics</h2>
<table>
{% for item in site.topics %}
<tr><td><a href="{{item.url}}"  data-ajax="false">{{item.title }}</a></td><td>{{item.desc}}</td></tr>
{% endfor %}
</table>
</div>