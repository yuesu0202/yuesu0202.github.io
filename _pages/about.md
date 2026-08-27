---
layout: about
title: About
permalink: /
subtitle: Building the knowledge bases, platforms, and cost tracing that make LLM agents work

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>yuesu4[at]gmail.com</p>

selected_papers: true
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 20

latest_posts:
  enabled: false
---

<style>
  /* Subtitle sits at the same size and weight as body text by default, so it
     does not read as a tier. Size differentiates it without adding bold. */
  .post-header .desc {
    font-size: 1.1rem;
    letter-spacing: -0.01em;
    margin-top: 0.2rem;
  }
  /* Prose and bullet links: 13 accent-coloured links in a few lines reads as
     speckle. Keep them in the text colour with a soft underline, and reserve
     the accent for hover. Scoped to direct children so the timeline, the
     social row and the publication buttons are untouched. */
  .post .clearfix > p a,
  .post .clearfix > ul li a {
    color: inherit;
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 2px;
    text-decoration-color: color-mix(in srgb, currentColor 35%, transparent);
    transition:
      color 0.15s ease,
      text-decoration-color 0.15s ease;
  }
  .post .clearfix > p a:hover,
  .post .clearfix > ul li a:hover {
    color: var(--global-theme-color);
    text-decoration-color: var(--global-theme-color);
  }
  .post .clearfix > p a.hl,
  .post .clearfix > ul li a.hl {
    color: var(--global-theme-color);
    text-decoration-color: color-mix(in srgb, var(--global-theme-color) 45%, transparent);
  }
</style>

I'm an AI Engineer at [Epsilla (YC S23)](https://www.epsilla.com){:.hl} and hold an M.S. in Artificial Intelligence Engineering from **Carnegie Mellon University**. Before that I studied Mathematics and Statistics at **UIUC**.

I work on agent systems end to end: the knowledge bases they retrieve from, the platforms they run on, the benchmarks that measure them, and the tracing that shows what they cost.

- **Agent infrastructure** - the platforms agents run on: [HarnessRouter](https://www.harnessrouter.ai){:.hl}, an API that runs coding agents in isolated sandboxes and returns finished artifacts, and the shared identity and authorization core every Epsilla product signs in through.
- **Knowledge systems and retrieval** - the knowledge bases agents retrieve from: Stanford SIS, a science intelligence product over a 2.5M-article biomedical knowledge graph, served to cloud agents through MCP.
- **Benchmarks and agent memory** - measuring what agents actually do, including [diagnosing retrieval vs. utilization bottlenecks](https://arxiv.org/abs/2603.02473){:.hl} in agent memory.
- **Agent tracing and cost** - [ClawTrace](https://github.com/epsilla-cloud/clawtrace){:.hl}, an open-source platform that prices every step of an agent run and distills those traces into cheaper agent skills.

<div style="display:flex; flex-wrap:wrap; gap:0.6rem 1.4rem; margin-top:0.5rem; font-size:1rem;">
  <a href="mailto:yuesu4@gmail.com" style="display:flex; align-items:center; gap:0.4rem; text-decoration:none; opacity:0.8;" onmouseover="this.style.opacity='1'" onmouseout="this.style.opacity='0.8'"><i class="fa-solid fa-envelope"></i> Email</a>
  <a href="https://github.com/yuesu0202" target="_blank" style="display:flex; align-items:center; gap:0.4rem; text-decoration:none; opacity:0.8;" onmouseover="this.style.opacity='1'" onmouseout="this.style.opacity='0.8'"><i class="fa-brands fa-github"></i> GitHub</a>
  <a href="https://www.linkedin.com/in/yuesucmu/" target="_blank" style="display:flex; align-items:center; gap:0.4rem; text-decoration:none; opacity:0.8;" onmouseover="this.style.opacity='1'" onmouseout="this.style.opacity='0.8'"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
  <a href="/assets/pdf/YueSu_Resume.pdf" target="_blank" style="display:flex; align-items:center; gap:0.4rem; text-decoration:none; opacity:0.8;" onmouseover="this.style.opacity='1'" onmouseout="this.style.opacity='0.8'"><i class="fa-solid fa-file-pdf"></i> Resume</a>
</div>

<h2 style="margin-top: 2.5rem"><a href="{{ '/experience/' | relative_url }}" style="color: inherit">Recent Experience</a></h2>

{% include experience_timeline.liquid compact=true %}

<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Yue Su",
    "url": "https://yuesu0202.github.io",
    "email": "mailto:yuesu4@gmail.com",
    "jobTitle": "AI Engineer",
    "description": "AI engineer building LLM agent systems end to end: knowledge bases, agent platforms, evaluation benchmarks, and cost-aware tracing.",
    "knowsAbout": [
      "LLM agents",
      "Agent infrastructure",
      "Knowledge graphs",
      "Retrieval-augmented generation",
      "Model Context Protocol (MCP)",
      "Agent tracing",
      "Agent evaluation",
      "Model fine-tuning",
      "LoRA",
      "Reinforcement learning",
      "PyTorch",
      "Distributed systems",
      "Kubernetes",
      "AWS",
      "GCP"
    ],
    "alumniOf": [
      {
        "@type": "CollegeOrUniversity",
        "name": "Carnegie Mellon University",
        "url": "https://www.cmu.edu"
      },
      {
        "@type": "CollegeOrUniversity",
        "name": "University of Illinois Urbana-Champaign",
        "url": "https://illinois.edu"
      }
    ],
    "sameAs": [
      "https://github.com/yuesu0202"
    ]
  }
</script>
