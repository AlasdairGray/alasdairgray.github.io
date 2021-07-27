---
---
# Publications

I have published {% bibliography_count --file conferences.bib --file journals.bib %} papers in peer reviewed conferences and journals. Below you will find a complete listing of all my contributions ({% bibliography_count %}) to conferences, journals, workshops, proceedings, and technical recommendations, as well as my PhD Thesis.

You can also find my publications on:
- [DBLP](http://www.informatik.uni-trier.de/~ley/db/indices/a-tree/g/Gray:Alasdair_J=_G=.html)
- [Google Scholar](https://scholar.google.co.uk/citations?user=3XRqgLcAAAAJ&hl=en)
- [ORCID (0000-0002-5711-4872)](http://orcid.org/0000-0002-5711-4872)
- [Scopus](https://www.scopus.com/authid/detail.uri?authorId=25521946600)
- [ACM Digital Library](http://dl.acm.org/author_page.cfm?id=81381602959)

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
