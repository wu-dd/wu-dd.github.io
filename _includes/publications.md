<div class="publications-heading">
  <h2 id="publications">Publications</h2>
  <button type="button" class="show-publications-button" aria-expanded="false" aria-controls="publications-list" data-show-text="Show all" data-hide-text="Show selected">Show all</button>
</div>

<div class="publications" id="publications-list">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li{% unless link.selected %} class="secondary-publication"{% endunless %}>
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
    <div class="title"><a href="{{ link.pdf }}" target="_blank" style="text-decoration:none;">{{ link.title }}</a></div>
    <div class="author">{{ link.authors }}</div>
    <div class="periodical"><em>{{ link.conference }}</em></div>
    <div class="links">
      {% if link.research %}
      <span class="research-badge" style="display:inline-block; font-size:12px; color:#828282; border:1px solid #828282; background:#ffffff; padding:0.0rem 0.1rem; cursor:default; text-decoration:none;">{{ link.research }}</span>
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
<br>
</li>

{% endfor %}

</ol>
</div>

<script>
  (function() {
    var button = document.querySelector('.show-publications-button');
    var publications = document.getElementById('publications-list');

    if (!button || !publications) {
      return;
    }

    button.addEventListener('click', function() {
      var expanded = publications.classList.toggle('show-all-publications');
      button.setAttribute('aria-expanded', expanded);
      button.textContent = expanded ? button.dataset.hideText : button.dataset.showText;
    });
  })();
</script>
