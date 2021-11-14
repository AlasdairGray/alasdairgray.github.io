---
---
# Publications

I have published {% bibliography_count --file conferences.bib --file journals.bib %} papers in peer reviewed conferences and journals. Below you will find a complete listing of all my contributions ({% bibliography_count %}) to conferences, journals, workshops, proceedings, and technical recommendations, as well as my PhD Thesis.

You can also find my publications on the following academic repositories.
<div class="social-icons">
    <a href="http://www.informatik.uni-trier.de/~ley/db/indices/a-tree/g/Gray:Alasdair_J=_G=.html" title="DBLP: Alasdair J G Gray" target="_blank"><i class="ai ai-dblp"></i></a>
    <a href="https://scholar.google.co.uk/citations?user=3XRqgLcAAAAJ&hl=en" title="Google Scholar: Alasdair J G Gray" target="_blank"><i class="ai ai-google-scholar"></i></a>
    <a href="https://orcid.org/0000-0002-5711-4872" title="ORCID: Alasdair J G Gray" target="_blank"><i class="fab fa-orcid"></i></a>
    <a href="https://www.scopus.com/authid/detail.uri?authorId=25521946600" title="Scopus: Alasdair J G Gray" target="_blank"><i class="ai ai-scopus"></i></a>
    <a href="http://dl.acm.org/author_page.cfm?id=81381602959" title="ACM Digital Libray: Alasdair J G Gray" target="_blank"><i class="ai ai-acm"></i></a>
</div>

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
