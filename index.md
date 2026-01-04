---
layout: single
author_profile: true
header:
  image: "/assets/images/background_image.jpg"
---
<section class="science">
  <!-- Scientific Publication -->
  <section class="publications" aria-labelledby="pubs-title">
    <h2 id="pubs-title">Scientific Publication</h2>

    <div class="pub-list">
      <!-- Paper 1 -->
      <article class="pub-card">
        <h3 class="pub-title">
          A physics-based Antarctic melt detection technique: combining Advanced Microwave Scanning Radiometer 2, radiative-transfer modeling, and firn modeling
          <span class="pub-year">(2024)</span>
        </h3>

        <p class="pub-meta">
          <span class="pub-journal">The Cryosphere</span>
          <span class="pub-sep">•</span>
          <a class="pub-doi" href="https://doi.org/10.5194/tc-18-3613-2024" target="_blank" rel="noopener noreferrer">
            https://doi.org/10.5194/tc-18-3613-2024
          </a>
        </p>

        <p class="pub-summary">
          In this paper, we pioneer a novel, physics based method using the Snow Radiative Transfer model to determine melt on ice sheets and ice shelves in the Antarctic.
          Check out our work in The Cryosphere!
        </p>

        <a class="pub-link" href="https://tc.copernicus.org/articles/18/3613/2024/tc-18-3613-2024.html" target="_blank" rel="noopener noreferrer">
          Read publication
        </a>
      </article>

      <!-- Paper 2 -->
      <article class="pub-card">
        <h3 class="pub-title">
          Significant Spatial Variability in Radar-Derived West Antarctic Accumulation Linked to Surface Winds and Topography
          <span class="pub-year">(2019)</span>
        </h3>

        <p class="pub-meta">
          <span class="pub-journal">Geophysical Research Letters</span>
          <span class="pub-sep">•</span>
          <a class="pub-doi" href="https://doi.org/10.1029/2019GL085363" target="_blank" rel="noopener noreferrer">
            https://doi.org/10.1029/2019GL085363
          </a>
        </p>

        <p class="pub-summary">
          Interested in fine-scale, relative variations in snow accumulation? Look no further than our airborne product published in GRL!
        </p>

        <a class="pub-link" href="https://ntrs.nasa.gov/citations/20200001040" target="_blank" rel="noopener noreferrer">
          Read publication
        </a>
      </article>
    </div>
  </section>

  <!-- Scientific Presentations -->
  <section class="talks" aria-labelledby="talks-title">
    <h2 id="talks-title">Scientific Presentations</h2>

    <div class="talk-list">
      <article class="talk-card">
        <h3 class="talk-title">
          A first look at airborne-derived firn compaction across the Greenland Ice Sheet
          <span class="talk-year">(2024)</span>
        </h3>

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

      <article class="talk-card">
        <h3 class="talk-title">
          Larsen C surface properties: A radiative transfer approach
          <span class="talk-year">(2020)</span>
        </h3>

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
    </div>
  </section>

  <style>
    /* Shared container */
    .science {
      max-width: 980px;
      margin: 0 auto;
      padding: 1.25rem 1rem;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
      color: #111827;
    }

    /* Section headings */
    .science h2 {
      font-size: clamp(1.5rem, 1.2rem + 1vw, 2rem);
      line-height: 1.2;
      margin: 0 0 1rem;
      letter-spacing: -0.02em;
    }

    /* Space between the two sections */
    .publications {
      margin-bottom: 1.5rem;
    }

    /* Lists (always stacked) */
    .pub-list,
    .talk-list {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
    }

    /* Cards */
    .pub-card,
    .talk-card {
      max-width: 860px;
      width: 100%;
      margin: 0 auto;
      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 14px;
      padding: 1rem;
      box-shadow: 0 1px 2px rgba(0, 0, 0, 0.04);
    }

    /* Titles */
    .pub-title,
    .talk-title {
      font-size: 1.05rem;
      line-height: 1.35;
      margin: 0 0 0.75rem;
      font-weight: 650;
    }

    .pub-year,
    .talk-year {
      font-weight: 600;
      color: #6b7280;
      margin-left: 0.25rem;
      white-space: nowrap;
    }

    /* Publication meta */
    .pub-meta {
      margin: 0 0 0.75rem;
      color: #374151;
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .pub-journal {
      font-weight: 600;
    }

    .pub-sep {
      margin: 0 0.4rem;
      color: #9ca3af;
    }

    .pub-doi {
      color: #111827;
      text-decoration: underline;
      text-underline-offset: 2px;
    }

    .pub-summary {
      margin: 0 0 0.75rem;
      color: #111827;
      line-height: 1.55;
    }

    .pub-link {
      display: inline-block;
      font-weight: 600;
      color: #111827;
      border: 1px solid #e5e7eb;
      padding: 0.5rem 0.75rem;
      border-radius: 999px;
      text-decoration: none;
      background: #f9fafb;
    }

    .pub-link:hover {
      background: #f3f4f6;
    }

    /* Video embeds */
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
