{% if page.previous == "" %}
{% assign prev_link = "<<**Previous** | " %}
{% else %}
{% assign prev_url = page.previous | append:"/" %}
{% assign prev_link = "<<[**Previous**](" | append:site.url | append:"/" | append:prev_url | append:") | " %}
{% endif %}
{{ prev_link }} [**Home**]({{ site.url }}/kiselev-geometry-1/)

##Chapter: {{ page.chapter }}

Solutions to the **selected** exercises from chapter _{{ page.chapter }}_ are explained below.