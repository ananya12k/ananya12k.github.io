---
layout: default
title: "Ananya Kulkarni's Academic Website"
---

<div class="sidebar">
  <img src="{{ site.avatar }}" alt="Profile Picture" class="profile-img">
  <h1>{{ site.title }}</h1>
  <p>{{ site.description }}</p>
  <ul class="social-links">
    {% for link in site.social_links %}
      <li>
        <a href="{{ link.link }}" target="_blank">
          <i class="{{ link.icon }}"></i> {{ link.name }}
        </a>
      </li>
    {% endfor %}
  </ul>
</div>

<div class="main-content">
  <h2>Welcome to My Academic Website</h2>
  <p>I'm Ananya Kulkarni, a passionate researcher and developer. Here, you can explore my research, projects, and publications. Use the navigation bar above to browse through my work.</p>
  
  <h3>Featured Projects</h3>
  <ul>
    <li><strong>Car Detection in Low Visibility Conditions</strong>: A solution to detect cars in adverse weather conditions.</li>
    <li><strong>Amazon ML Challenge</strong>: Participated and created a machine learning model for entity extraction from product images.</li>
  </ul>

  <h3>Recent Publications</h3>
  <ul>
    <li><strong>Paper Title 1</strong>: Description of the research work.</li>
    <li><strong>Paper Title 2</strong>: Description of another research work.</li>
  </ul>

  <p>For more details, visit the <a href="/publications">Publications</a> section.</p>
</div>
