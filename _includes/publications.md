<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  {%- if link.image -%}
  <div class="col-sm-3 abbr" style="position:relative; padding-right:15px; padding-left:15px;">
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width:100%; height:auto;">
    {%- if link.conference_short -%}
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {%- endif -%}
  </div>
  <div class="col-sm-9" style="position:relative; padding-right:15px; padding-left:20px;">
  {%- else -%}
  <div class="col-sm-12" style="position:relative; padding-right:15px; padding-left:0px;">
  {%- endif -%}
    <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
    <div class="author">{{ link.authors }}</div>
    <div class="periodical"><em>{{ link.conference }}</em></div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.research %}
      <span class="btn btn-sm z-depth-0 research-badge" role="button" style="font-size:12px;">{{ link.research }}</span>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="#" class="btn btn-sm z-depth-0 bibtex-btn" role="button" style="font-size:12px;" onclick="toggleBibtex(this); return false;">BibTex</a> 
      <div class="hidden bibtex-content" style="margin-top: 10px;">
        <pre>{{ link.bibtex }}</pre>
      </div>
      {% endif %}
      {% if link.notes %} 
      <div class="notes"><strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong></div>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
