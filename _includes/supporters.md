<div class="member-list">
  <div>
  {% for sponsor in include.data %}
    <a class="member-logo" href="{{ supporter.url }}" rel="supporter" target="_blank">
      <img src="{{ supporter.image }}" alt="{{ supporter.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
