{% if page.previous == "" %}
{% assign prev_link = "**< Previous** " %}
{% else %}
{% assign prev_url = page.previous | append:"/" %}
{% assign prev_link = "[**< Previous**](" | append:site.url | append:"/" | append:prev_url | append:") " %}
{% endif %}

{% if page.next == "" %}
{% assign next_link = "**Next >** " %}
{% else %}
{% assign next_url = page.next | append:"/" %}
{% assign next_link = "[**Next >**](" | append:site.url | append:"/" | append:next_url | append:") " %}
{% endif %}

{% if page.top == "" %}
{% assign top_link = "**^ Top** " %}
{% else %}
{% assign top_url = page.top | append:"/" %}
{% assign top_link = "[**^ Top**](" | append:site.url | append:"/" | append:top_url | append:") " %}
{% endif %}
{{ prev_link }} || {{ top_link }} || [**Home**]({{ site.url }}/kiselev-geometry-1/) || {{ next_link }}