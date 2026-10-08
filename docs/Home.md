# Wicked Combo
<style>
:root {
  --c-bg: #100d16;
  --c-surface: #1a1426;
  --c-ink: #f2ecdc;
  --c-muted: #9d8fb5;
  --c-accent: #e8d21c;
  --c-border: #352a4d;
}
/* Landing page: break out of the wiki shell (no sidebar column, no topbar, no footer) */
.shell { display: block !important; }
.sidebar, .nav-toggle, .breadcrumb, header.topbar, footer { display: none !important; }
.content > h1:first-child { display: none; }
main.content { max-width: 1000px; margin: 0 auto; padding-left: 1.5rem; padding-right: 1.5rem; }
.wc-hero { text-align: center; padding: 3rem 0 3.5rem; }
.wc-hero img { width: min(340px, 70vw); border-radius: 1rem; box-shadow: 0 20px 60px rgba(0,0,0,0.6); }
.wc-title {
  font-size: clamp(2.6rem, 7vw, 4.5rem); margin: 1.5rem 0 0.3rem;
  color: var(--c-accent); letter-spacing: 0.04em; font-weight: 900;
}
.wc-motto { color: var(--c-muted); letter-spacing: 0.3em; font-size: 0.95rem; text-transform: uppercase; }
.wc-blurb { max-width: 640px; margin: 1.5rem auto 0; line-height: 1.7; font-size: 1.1rem; }
.wc-section { padding: 3rem 0; border-top: 1px solid var(--c-border); }
.wc-section h2 {
  color: var(--c-accent); text-align: center; font-size: 1.8rem;
  margin-bottom: 2rem; border: none; letter-spacing: 0.06em;
}
.wc-game {
  display: grid; grid-template-columns: 200px 1fr; gap: 2rem; align-items: center;
  background: var(--c-surface); border: 1px solid var(--c-border);
  border-radius: 0.6rem; padding: 1.8rem; max-width: 760px; margin: 0 auto;
  text-decoration: none;
}
@media (max-width: 600px) { .wc-game { grid-template-columns: 1fr; text-align: center; } }
.wc-game:hover { border-color: var(--c-accent); }
.wc-game img { width: 100%; border-radius: 0.4rem; }
.wc-game h3 { margin: 0 0 0.4rem; color: var(--c-accent); font-size: 1.4rem; }
.wc-game p { margin: 0.4rem 0; color: var(--c-ink); line-height: 1.6; }
.wc-game .wc-go { color: var(--c-accent); font-weight: bold; }
.wc-about { max-width: 640px; margin: 0 auto; line-height: 1.7; text-align: center; }
.wc-about .wc-fine { color: var(--c-muted); font-size: 0.9rem; margin-top: 1.2rem; }
</style>

<div class="wc-hero">
<img src=".attachments/logo.jpg" alt="Wicked Combo logo">
<div class="wc-title">WICKED COMBO</div>
<div class="wc-motto">High five &middot; Horns up</div>
<p class="wc-blurb">Wicked Combo is an independent game studio making serious tactical games. When your tactics land with a devastating blow &mdash; that's a Wicked Combo.</p>
</div>

<div class="wc-section">
<h2>OUR GAMES</h2>
<a class="wc-game" href="https://sanguisharena.com/">
<img src=".attachments/cover.jpg" alt="Sanguis et Harena">
<div>
<h3>Sanguis et Harena</h3>
<p><em>A tactical card game of timing, positioning, and nerve.</em></p>
<p>Gladiatorial combat for 2&ndash;6 players. Draft a champion, assemble your loadout, and outthink your opponents &mdash; six seconds at a time.</p>
<p class="wc-go">Visit sanguisharena.com &rarr;</p>
</div>
</a>
</div>

<div class="wc-section">
<h2>THE STUDIO</h2>
<div class="wc-about">
<p>Wicked Combo designs games where every decision matters and every play tells a story. Sanguis et Harena is our first release &mdash; more are in the arena.</p>
<p class="wc-fine">Wicked Combo is a wholly owned subsidiary of Mark Davis Holdings, LLC.<br>&copy; 2026 Wicked Combo. All rights reserved.</p>
</div>
</div>

