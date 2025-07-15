<div class="projects-grid">
  {% for p in site.data.projects %}
    <div class="project-card">
      <a href="{{ p.url }}">
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}">
        <h3>{{ p.title }}</h3>
        <p>{{ p.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>
