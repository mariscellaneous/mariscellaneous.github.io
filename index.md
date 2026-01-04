---
layout: single
author_profile: true
header:
  image: "/assets/images/HeaderPhoto.jpg"
---
<section class="science" aria-labelledby="science-title">

  <div class="science-list">
    <!-- 2024 — Talk -->
    <article class="science-card">
      <h3 class="science-title">
        A first look at airborne-derived firn compaction across the Greenland Ice Sheet
        <span class="science-year">(2024)</span>
      </h3>

      <p class="science-meta">
        <span class="science-type">Presentation</span>
      </p>

      <div class="video-wrap">
        <iframe
          src="https://www.youtube.com/embed/ecFOUm--tyQ?si=pguwp6-0cAVbOFoE"
          title="A first look at airborne-derived firn compaction across the Greenland Ice Sheet (2024)"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen>
        </iframe>
      </div>
    </article>

    <!-- 2024 — Publication -->
    <article class="science-card">
      <h3 class="science-title">
        A physics-based Antarctic melt detection technique: combining Advanced Microwave Scanning Radiometer 2, radiative-transfer modeling, and firn modeling
        <span class="science-year">(2024)</span>
      </h3>

      <p class="science-meta">
        <span class="science-type">Publication</span>
        <span class="science-sep">•</span>
        <span class="science-journal">The Cryosphere</span>
        <span class="science-sep">•</span>
        <a class="science-doi" href="https://doi.org/10.5194/tc-18-3613-2024" target="_blank" rel="noopener noreferrer">
          https://doi.org/10.5194/tc-18-3613-2024
        </a>
      </p>

      <p class="science-summary">
        In this paper, we pioneer a novel, physics based method using the Snow Radiative Transfer model to determine melt on ice sheets and ice shelves in the Antarctic.
        Check out our work in The Cryosphere!
      </p>

      <a class="science-link" href="https://tc.copernicus.org/articles/18/3613/2024/tc-18-3613-2024.html" target="_blank" rel="noopener noreferrer">
        Read publication
      </a>
    </article>

    <!-- 2020 — Talk -->
    <article class="science-card">
      <h3 class="science-title">
        Larsen C surface properties: A radiative transfer approach
        <span class="science-year">(2020)</span>
      </h3>

      <p class="science-meta">
        <span class="science-type">Presentation</span>
      </p>

      <div class="video-wrap">
        <iframe
          src="https://www.youtube.com/embed/te0eO6Xaf9s?si=uxVbMafcIk8MMyFs&amp;start=2501"
          title="Larsen C surface properties: A radiative transfer approach (2020)"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen>
        </iframe>
      </div>
    </article>

    <!-- 2019 — Publication -->
    <article class="science-card">
      <h3 class="science-title">
        Significant Spatial Variability in Radar-Derived West Antarctic Accumulation Linked to Surface Winds and Topography
        <span class="science-year">(2019)</span>
      </h3>

      <p class="science-meta">
        <span class="science-type">Publication</span>
        <span class="science-sep">•</span>
        <span class="science-journal">Geophysical Research Letters</span>
        <span class="science-sep">•</span>
        <a class="science-doi" href="https://doi.org/10.1029/2019GL085363" target="_blank" rel="noopener noreferrer">
          https://doi.org/10.1029/2019GL085363
        </a>
      </p>

      <p class="science-summary">
        Interested in fine-scale, relative variations in snow accumulation? Look no further than our airborne product published in GRL!
      </p>

      <a class="science-link" href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019GL085363" target="_blank" rel="noopener noreferrer">
        Read publication
      </a>
    </article>
  </div>

  <style>
    .science {
      max-width: 980px;
      margin: 0 auto;
      padding: 1.25rem 1rem;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
      color: #111827;
    }

    .science h2 {
      font-size: clamp(1.5rem, 1.2rem + 1vw, 2rem);
      line-height: 1.2;
      margin: 0 0 1rem;
      letter-spacing: -0.02em;
    }

    /* Always stacked */
    .science-list {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
    }

    .science-card {
      max-width: 860px;
      width: 100%;
      margin: 0 auto;
      background: #b9c7e2;
      border: 1px solid #e5e7eb;
      border-radius: 14px;
      padding: 1rem;
      box-shadow: 0 1px 2px rgba(0, 0, 0, 0.04);
    }

    .science-title {
      font-size: 1.05rem;
      line-height: 1.35;
      margin: 0 0 0.5rem;
      font-weight: 650;
    }

    .science-year {
      font-weight: 600;
      color: #6b7280;
      margin-left: 0.25rem;
      white-space: nowrap;
    }

    .science-meta {
      margin: 0 0 0.75rem;
      color: #374151;
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .science-type {
      font-weight: 600;
      color: #111827;
    }

    .science-journal {
      font-weight: 600;
    }

    .science-sep {
      margin: 0 0.4rem;
      color: #9ca3af;
    }

    .science-doi {
      color: #111827;
      text-decoration: underline;
      text-underline-offset: 2px;
    }

    .science-summary {
      margin: 0 0 0.75rem;
      color: #111827;
      line-height: 1.55;
    }

    .science-link {
      display: inline-block;
      font-weight: 600;
      color: #111827;
      border: 1px solid #e5e7eb;
      padding: 0.5rem 0.75rem;
      border-radius: 999px;
      text-decoration: none;
      background: #f9fafb;
    }

    .science-link:hover {
      background: #f3f4f6;
    }

    /* Responsive video sizing */
    .video-wrap {
      aspect-ratio: 16 / 9;
      width: 100%;
      border-radius: 12px;
      overflow: hidden;
      background: #f3f4f6;
    }

    .video-wrap iframe {
      width: 100%;
      height: 100%;
      border: 0;
      display: block;
    }
  </style>
</section>
