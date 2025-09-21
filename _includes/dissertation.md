<h2 id="dissertation" style="margin: 0px 0px -15px;">PhD Dissertation</h2>

<div class="publications">
<ol class="bibliography" style="margin-top: 0; margin-bottom: 0px;">

{% for link in site.data.dissertation.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px; margin-bottom: -20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="periodical"><em>{{ link.journal }}</em>
      </div>
  </div>
</div>
</li>


{% endfor %}

</ol>
</div>

