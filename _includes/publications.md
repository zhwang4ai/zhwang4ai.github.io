<h2 id="publications" style="margin: 2px 0px -15px;">Selected Publications</h2>
<p style="margin: 20px 0 -10px;"><small>(* denotes equal contribution)</small></p>

<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.selected %}
{% include pub_item.html link=link %}
{% endfor %}
</ol>
</div>

<h2 id="other-publications" style="margin: 2px 0px -15px;">Other Publications</h2>

<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.others %}
{% include pub_item.html link=link %}
{% endfor %}
</ol>
</div>
