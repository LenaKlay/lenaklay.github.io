---
layout: home
profile_picture:
  src: /assets/img/profile-pic.JPG
  alt: website picture
---

<p>
  [ Site en cours de création ]
</p>

<p>
  I am ...
</p>

<h2>Research</h2>

<p>
  ...
</p>

<h2>Timeline</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logos/mnhn.png' | https://www.mnhn.fr/fr }}" alt="MNHN">
    </div>
    <div class="timeline-content">
      <strong>2025–present</strong>
      <p>Postdoctoral researcher — Muséum national d'Histoire naturelle</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logos/ubo.png' | https://www.univ-brest.fr/fr }}" alt="UBO">
    </div>
    <div class="timeline-content">
      <strong>2024–2025</strong>
      <p>Postdoctoral researcher — UBO</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logos/sorbonne.png' | https://iees-paris.fr/ }}" alt="sorbonne">
    </div>
    <div class="timeline-content">
      <strong>2020–2023</strong>
      <p>PhD — Sorbonne Université</p>
    </div>
  </div>

  

</div>


<style>
.timeline {
  margin: 2rem 0;
}

.timeline-item {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.timeline-logo {
  width: 70px;
  height: 70px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.timeline-logo img {
  max-width: 60px;
  max-height: 60px;
  object-fit: contain;
}

.timeline-content strong {
  display: block;
  margin-bottom: 0.3rem;
}

.timeline-content p {
  margin: 0;
}
</style>
