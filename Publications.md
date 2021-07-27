---
---
# Publications

<!-- Get current year -->
{% assign currentYear = 'now' | date: "%Y" %}
<!-- For each year from now until 2002, print publications from that year -->
{% for focusYear in (2002..currentYear)  reversed %}
<!-- Only print years with publications -->
<!-- 
    Following code to capture the count came from 
    https://github.com/inukshuk/jekyll-scholar/issues/310#issuecomment-654578621 
-->
{%- capture pubCount -%}
{%- bibliography_count --query @*[year={{focusYear}}] -%}
{%- endcapture -%}

{% if pubCount != "0" %}
## {{ focusYear }}
{% bibliography --query @*[year={{focusYear}}] %}
{% endif %}

{% endfor %}
