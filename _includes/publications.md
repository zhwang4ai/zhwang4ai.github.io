<h2 id="technical-reports" style="margin: 2px 0px -15px;">Technical Reports</h2>
<p style="margin: 20px 0 -10px;"><small>As a contributor of the ByteDance Seed team.</small></p>

<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.technical_reports %}
{% include pub_item.html link=link %}
{% endfor %}
</ol>
</div>

<h2 id="publications" style="margin: 2px 0px -15px;">Selected Publications</h2>
<p style="margin: 20px 0 -10px;"><small>(* denotes equal contribution. For the full publication list, please see my <a href="{{ site.google_scholar }}" target="_blank">Google Scholar</a>.)</small></p>

<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.selected %}
{% include pub_item.html link=link %}
{% endfor %}
</ol>
</div>

{% comment %}
Other Publications is hidden. Data is kept in _data/publications.yml under `others`.

<h2 id="other-publications" style="margin: 2px 0px -15px;">Other Publications</h2>

<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.others %}
{% include pub_item.html link=link %}
{% endfor %}
</ol>
</div>
{% endcomment %}
