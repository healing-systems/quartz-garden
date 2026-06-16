---
title: Home
---
Welcome to the Sweetbay Digital Garden

I'm glad you're here!
<!-- ── Custom Added 6.15.26 ── -->
<style>
  /* ── Token System ───────────────────────────────────────── */
  :root {
    --soil:       #2C1F14;
    --bark:       #5C3D2E;
    --terracotta: #B85C38;
    --moss:       #4A6741;
    --parchment:  #F5EFE0;
    --cream:      #FBF7EF;
    --fog:        #DDD4C2;

    --font-display: 'Georgia', 'Times New Roman', serif;
    --font-body:    system-ui, -apple-system, sans-serif;
    --font-mono:    'Courier New', monospace;
  }

  /* ── Reset & Base ───────────────────────────────────────── */
  .ci-garden * { box-sizing: border-box; margin: 0; padding: 0; }

  .ci-garden {
    font-family: var(--font-body);
    color: var(--soil);
    background: var(--parchment);
    line-height: 1.75;
    max-width: 860px;
    margin: 0 auto;
    padding: 0 1.5rem 4rem;
  }

  /* ── Hero ───────────────────────────────────────────────── */
  .ci-hero {
    padding: 5rem 0 3.5rem;
    border-bottom: 1px solid var(--fog);
    margin-bottom: 3rem;
  }

  .ci-eyebrow {
    font-family: var(--font-mono);
    font-size: 0.72rem;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--moss);
    margin-bottom: 1.25rem;
  }

  .ci-hero h1 {
    font-family: var(--font-display);
    font-size: clamp(2.4rem, 6vw, 4rem);
    font-weight: normal;
    font-style: italic;
    color: var(--soil);
    line-height: 1.15;
    margin-bottom: 1.5rem;
    max-width: 680px;
  }

  .ci-hero h1 em {
    font-style: normal;
    color: var(--terracotta);
  }

  .ci-hero p {
    font-size: 1.05rem;
    color: var(--bark);
    max-width: 540px;
    line-height: 1.8;
  }

  /* ── Section Labels ─────────────────────────────────────── */
  .ci-section-label {
    font-family: var(--font-mono);
    font-size: 0.68rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--moss);
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    gap: 0.75rem;
  }

  .ci-section-label::after {
    content: '';
    display: block;
    flex: 1;
    height: 1px;
    background: var(--fog);
  }

  /* ── About / Grounding Strip ─────────────────────────────── */
  .ci-grounding {
    background: var(--soil);
    color: var(--parchment);
    padding: 2.75rem 2rem;
    margin-bottom: 4rem;
    border-radius: 2px;
  }

  .ci-grounding .ci-section-label {
    color: var(--fog);
  }

  .ci-grounding .ci-section-label::after {
    background: #4a3928;
  }

  .ci-grounding p {
    font-size: 1rem;
    line-height: 1.85;
    color: #e8dece;
    max-width: 620px;
  }

  .ci-grounding p + p {
    margin-top: 1rem;
  }

  .ci-grounding strong {
    color: var(--parchment);
    font-weight: 600;
  }

  /* ── Footer ─────────────────────────────────────────────── */
  .ci-footer {
    border-top: 1px solid var(--fog);
    padding-top: 2rem;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 1.5rem;
  }

  .ci-footer-phrase {
    font-family: var(--font-display);
    font-style: italic;
    font-size: 0.9rem;
    color: var(--bark);
  }

  .ci-footer-links {
    display: flex;
    gap: 1.5rem;
    flex-wrap: wrap;
  }

  .ci-footer-links a {
    font-family: var(--font-mono);
    font-size: 0.68rem;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--moss);
    text-decoration: none;
  }

  .ci-footer-links a:hover {
    color: var(--terracotta);
  }

  /* ── Responsive ─────────────────────────────────────────── */
  @media (max-width: 600px) {
    .ci-hero { padding: 3rem 0 2.5rem; }
    .ci-grounding { padding: 2rem 1.25rem; }
    .ci-footer { flex-direction: column; }
  }
</style>
<div class="ci-garden">
  <!-- ── Hero ── -->
  <header class="ci-hero">
    <p class="ci-eyebrow">digital garden · ancestral healing arts</p>
    <h1>welcome back.<br><em>here's what's growing.</em></h1>
    <p>
      This is the garden — a living space for subscribers to go deeper,
      wander slowly, and return to whenever the work calls you back.
      Nothing here is finished. Everything here is alive.
    </p>
  </header>
  <!-- ── Grounding Strip ── -->
  <section class="ci-grounding">
    <p class="ci-section-label">how to be here</p>
    <p>
      This garden is not a feed. You don't have to consume it.
      Come when something pulls you. Follow a thread. Let a note
      sit with you for a few days before you move to the next one.
    </p>
    <p>
      Notes marked <strong>seed</strong> are still forming.
      <strong>Tree</strong> means I'm actively in it.
      <strong>Evergreen</strong> means it's settled...for now.
      Everything is subject to change because <strong>rest is sacred</strong>
      and so is the right to keep becoming.
    </p>
  </section>
  <!-- ── Footer ── -->
  <footer class="ci-footer">
    <p class="ci-footer-phrase">"creative intuition lives here."</p>
    <nav class="ci-footer-links">
      <a href="/about">About</a>
      <a href="/offerings">Offerings</a>
      <a href="https://creativeintuitive.substack.com" target="_blank">← Back to Substack</a>
      <a href="/contact">Contact</a>
    </nav>
  </footer>
</div>