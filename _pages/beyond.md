---
layout: page
title: beyond
permalink: /beyond/
nav: true
nav_order: 7
description:
---

Here I share some of the things I make in my leisure time, along with their finished forms. Most of them were created during my PhD years, so each one carries something from that time: a little sorrow, a few tears, some sweat, and the happiness of finding free time to enjoy myself, distract myself, and make something by hand.

<div class="beyond-grid">

  <a class="beyond-card" href="/beyond/crafting/">
    <h2>Crafty times</h2>
    <p>Projects, patterns, and things I have made.</p>
  </a>

  <a class="beyond-card" href="/beyond/cooking-baking/">
    <h2>Cooking & Baking</h2>
    <p>Recipes, experiments, and favorite dishes.</p>
  </a>

 <a class="beyond-card" href="https://github.com/hande-sevgi/linguistics_research_chatbot">
    <h2>In progress chatbot</h2>
    <p>I am working on a chatbot to use in linguistic research to improve my skills to build.</p>
  </a>


<a class="beyond-card" href="/assets/pdf/Sevgi_Resume_Master.pdf">
    <h2>Resume</h2>
    <p>View or download my general resume.</p>
  </a>

</div>

<style>
.beyond-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.25rem;
  margin-top: 2rem;
}

.beyond-card {
  display: block;
  padding: 1.5rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 12px;
  text-decoration: none;
  color: var(--global-text-color);
  background: var(--global-card-bg-color);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.beyond-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.12);
  text-decoration: none;
}

.beyond-card h2 {
  margin-top: 0;
  margin-bottom: 0.5rem;
}

.beyond-card p {
  margin-bottom: 0;
}
</style>
