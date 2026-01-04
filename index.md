---
layout: single
author_profile: true
header:
  image: "/assets/images/background_image.jpg"
---

<section class="talks" aria-labelledby="talks-title">
  <h2 id="talks-title">Scientific Presentations</h2>

  <div class="talk-grid">
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

  <style>
    .talks {
      max-width: 980px;
      margin: 0 auto;
      padding: 1.25rem 1rem;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
      color: #111827;
    }

    .talks h2 {
      font-size: clamp(1.5rem, 1.2rem + 1vw, 2rem);
      line-height: 1.2;
      margin: 0 0 1rem;
      letter-spacing: -0.02em;
    }

    /* Always stacked (one column) */
    .talk-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
    }

    /* Optional: keep cards from getting too wide on large screens */
    .talk-card {
      max-width: 860px;
      width: 100%;
      margin: 0 auto;

      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 14px;
      padding: 1rem;
      box-shadow: 0 1px 2px rgba(0,0,0,0.04);
    }

    .talk-title {
      font-size: 1.05rem;
      line-height: 1.35;
      margin: 0 0 0.75rem;
      font-weight: 650;
    }

    .talk-year {
      font-weight: 600;
      color: #6b7280;
      margin-left: 0.25rem;
      white-space: nowrap;
    }

    .video-wrap {
      position: relative;
      width: 100%;
      padding-top: 1%;
      border-radius: 12px;
      overflow: hidden;
      background: #f3f4f6;
    }

    .video-wrap iframe {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }
  </style>
</section>
