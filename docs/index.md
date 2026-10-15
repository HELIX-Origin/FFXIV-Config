---
layout: default
title: FFXIV Config
eyebrow: Final Fantasy XIV HUD & Macro Layout
summary: "A custom, information-dense HUD, hotbar and macro layout for Final Fantasy XIV. Every combat, crafting and gathering job is pre-arranged, with an on-screen macro menu for switching jobs and opening common windows."
nav_order: 1
notice: "<strong>Config-only.</strong> FFXIV Config ships only the game's own character data files — no installer and no third-party tools. <strong>Back up your character folder before installing.</strong>"
header_actions:
  - title: Installation Guide
    url: /docs/Installation/
    class: button--primary
  - title: Configuration Files
    url: /docs/Configuration-Files/
    class: button--secondary
  - title: View on GitHub ↗
    url: https://github.com/HELIX-Origin/FFXIV-Config
    class: button--secondary
image: assets/images/ffxiv-config.svg
---

<div markdown="0" class="site-banner-container" style="margin-bottom: 2.2rem; border-radius: 14px; overflow: hidden; border: 1px solid rgba(135, 195, 250, 0.25); box-shadow: 0 16px 48px rgba(0,0,0,0.5); line-height: 0; font-size: 0;"><img src="https://github.com/user-attachments/assets/14de1ec4-7703-4396-89c5-c4976dbc1cf8" alt="FFXIV Config preview" style="width: 100%; height: auto; display: block; margin: 0; padding: 0; border: none;" loading="lazy" decoding="async" /></div>

<section id="about" class="doc-section">
<div class="section-heading">
<span class="section-number">01</span>
<div>
<p class="eyebrow">Overview</p>
<h2>What is FFXIV Config?</h2>
</div>
</div>
<p>
<strong>FFXIV Config</strong> is a ready-to-use HUD, hotbar, and macro layout for <strong>Final Fantasy XIV</strong>.
Every combat, crafting, and gathering job has its actions, spells, items, and macros laid out ahead of
time — so you spend your time playing instead of arranging hotbars.
</p>
<p>
It is built on top of <a href="https://github.com/Fr4nsson/FFC">Fr4nsson's FFXIV Config (FFC)</a> and adapted
for current 8.x jobs. Switching jobs from the on-screen menu changes your gear set and reveals the
hotbars for that role, giving you one consistent layout across every job in the game.
</p>

<h3>At a glance</h3>
<table>
<thead>
<tr><th>Dimension</th><th>Details</th></tr>
</thead>
<tbody>
<tr><td><strong>What it is</strong></td><td>A curated set of the game's native per-character data files (no executable or third-party hook)</td></tr>
<tr><td><strong>What it changes</strong></td><td>HUD layout, hotbars, macros, keybinds, gear sets, control settings</td></tr>
<tr><td><strong>What it preserves</strong></td><td>Graphics, audio, resolution, and chat settings remain untouched</td></tr>
<tr><td><strong>Platform</strong></td><td>Windows PC client</td></tr>
<tr><td><strong>Requirements</strong></td><td>Final Fantasy XIV, with the game closed during installation</td></tr>
</tbody>
</table>
</section>

<section id="features" class="doc-section">
<div class="section-heading">
<span class="section-number">02</span>
<div>
<p class="eyebrow">Highlights</p>
<h2>Features &amp; Hotbar Architecture</h2>
</div>
</div>

<div class="features-grid">
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">⚔️</span>
<h3>Hotbars 1–3</h3>
<p>Combat hotbars hosting the active job's single-target, AoE, and combo actions.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🎛️</span>
<h3>Hotbars 4–7</h3>
<p>Free-use hotbars left empty for personal items, potions, and custom shortcuts.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🎒</span>
<h3>Hotbars 8–9</h3>
<p>Utility hotbars with role actions, sprint, mounts, teleport, and general conveniences.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">📜</span>
<h3>Hotbar 10</h3>
<p>Menu hotbar hosting the on-screen macro menu for job switching and window toggles.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🔄</span>
<h3>Job Switching</h3>
<p>One-click macro for every job that swaps gear sets and displays role-specific bars.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">✨</span>
<h3>Clean HUD</h3>
<p>Single-button toggle macro to instantly hide duty lists, server info, and minimaps.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">⚡</span>
<h3>Battle-Effect Presets</h3>
<p>Five "BFX" presets that toggle battle effects and nameplates for raids or performance.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🔒</span>
<h3>Zero Tools Needed</h3>
<p>Uses pure game DAT files; no memory injection, overlays, or third-party launchers.</p>
</div>
</div>
</section>

<section id="jobs" class="doc-section">
<div class="section-heading">
<span class="section-number">03</span>
<div>
<p class="eyebrow">Roster</p>
<h2>Supported Jobs (8.x Current)</h2>
</div>
</div>

<div class="features-grid">
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🛡️</span>
<h3>Tanks</h3>
<p>Paladin, Warrior, Dark Knight, Gunbreaker.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">💚</span>
<h3>Healers</h3>
<p>White Mage, Scholar, Astrologian, Sage.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🗡️</span>
<h3>Melee DPS</h3>
<p>Monk, Dragoon, Ninja, Samurai, Reaper, Viper.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🏹</span>
<h3>Physical Ranged DPS</h3>
<p>Bard, Machinist, Dancer.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🔮</span>
<h3>Magical Ranged DPS</h3>
<p>Black Mage, Summoner, Red Mage, Blue Mage, Beastmaster.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">🔨</span>
<h3>Crafters (DoH)</h3>
<p>Carpenter, Blacksmith, Armorer, Goldsmith, Leatherworker, Weaver, Alchemist, Culinarian.</p>
</div>
<div class="feature-card">
<span class="feature-card__icon" aria-hidden="true">⛏️</span>
<h3>Gatherers (DoL)</h3>
<p>Miner, Botanist, Fisher.</p>
</div>
</div>
</section>

<section id="docs" class="doc-section">
<div class="section-heading">
<span class="section-number">04</span>
<div>
<p class="eyebrow">Directory</p>
<h2>Explore Documentation</h2>
</div>
</div>

<div class="documentation-directory">
<div>
<h3>User Guides</h3>
<ul>
{%- assign guide_pages = site.docs | sort: "nav_order" %}
{%- for doc in guide_pages %}
<li><a href="{{ doc.url | relative_url }}">{{ doc.title | escape }}</a></li>
{%- endfor %}
</ul>
</div>
</div>

<div class="header-actions" style="margin-top: 1.5rem;">
<a class="button button--primary" href="{{ '/docs/Installation/' | relative_url }}">Installation Guide</a>
<a class="button button--secondary" href="{{ '/docs/Configuration-Files/' | relative_url }}">Configuration Files</a>
<a class="button button--secondary" href="https://github.com/HELIX-Origin/FFXIV-Config">Source on GitHub ↗</a>
</div>
</section>

<section id="credits" class="doc-section">
<div class="section-heading">
<span class="section-number">05</span>
<div>
<p class="eyebrow">Attribution</p>
<h2>Credits &amp; Disclaimer</h2>
</div>
</div>
<ul>
<li><strong>Base layout, keybinds and menu system:</strong> <a href="https://github.com/Fr4nsson/FFC">Fr4nsson's FFXIV Config (FFC)</a>, adapted and extended for current 8.x jobs.</li>
<li><strong>Config-only guarantee:</strong> FFXIV Config is strictly configuration data. Every file is one the game client itself generates and reads. No third-party files, DLLs, or external applications are involved. Use at your own risk — always keep the backup described in the <a href="{{ '/docs/Installation/' | relative_url }}">Installation guide</a>.</li>
<li>FINAL FANTASY XIV is a registered trademark of Square Enix Holdings Co., Ltd. FFXIV Config is an independent community project and is not affiliated with or endorsed by Square Enix.</li>
</ul>
</section>
