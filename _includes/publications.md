<div class="publications-heading">
  <h2 id="publications">Publications</h2>
  <button type="button" class="show-publications-button" aria-expanded="false" aria-controls="publications-list" data-show-text="Show all" data-hide-text="Show selected">Show all</button>
</div>

<div class="publications" id="publications-list">
<ol class="bibliography">

{% for link in site.data.publications.main %}
{% if link.selected %}
{% include publication_item.html link=link %}
{% else %}
{% include publication_item.html link=link extra_class="secondary-publication" %}
{% endif %}
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
