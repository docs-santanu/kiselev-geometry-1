{% if page.previous == "" %}
[**Previous**] | 
{% else %}
{% assign prev_url = page.previous | append:"/" %}
[**Previous**]({{ site.url }}/{{ prev_url }}) | 
{% endif %}
[**Home**]({{ site.url }}/kiselev-geometry-1/)

##Chapter: {{ page.chapter }}

Solutions to the **selected** exercises from chapter _{{ page.chapter }}_ are explained below.