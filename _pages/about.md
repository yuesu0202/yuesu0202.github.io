---
layout: about
title: About
permalink: /
subtitle: Building agentic and multi-agent systems, and the tracing and evaluation that make them trustworthy

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

I build agentic AI systems: LLM agents that use tools, act over real knowledge, run across many coding-agent harnesses, and leave traces you can debug and price. I hold an M.S. in Artificial Intelligence Engineering from **Carnegie Mellon University** and studied Mathematics and Statistics at **UIUC**.

Most recently I was an AI Engineer at [Epsilla (YC S23)](https://www.epsilla.com){:.hl}, building agent products and infrastructure, and an AI Specialist at Handshake AI, evaluating frontier coding agents.

- **Tool-using agents over knowledge** - Gene Quest, a gene research agent running on the Claude Code harness. It reaches a 3.3M+ article PubMed knowledge graph through MCP servers with 7 retrieval tools, and a review loop checks every citation against the graph before a researcher sees the answer.
- **Routing across coding agents** - [HarnessRouter](https://www.harnessrouter.ai){:.hl}, an open-source router that puts 30 coding-agent harnesses behind one API. I moved the DeepSeek Harness onto the shared relay that keeps provider keys out of the agent, and fixed self-hosted model failures.
- **Tracing multi-agent runs** - [ClawTrace](https://github.com/epsilla-cloud/clawtrace){:.hl}, an open-source platform that attributes cost and tokens to every LLM call, tool call, and sub-agent in a run, diagnoses expensive or failing runs, and distills traces into reusable agent skills.
- **Evaluating agent behavior** - long-horizon evaluations and red-teaming of frontier coding agents at Handshake AI, and [diagnosing retrieval vs. utilization bottlenecks](https://arxiv.org/abs/2603.02473){:.hl} in agent memory.

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
    "description": "AI engineer building agentic and multi-agent LLM systems: tool-using agents, coding-agent harnesses, agent tracing, and agent evaluation.",
    "knowsAbout": [
      "LLM agents",
      "Agentic AI",
      "Multi-agent systems",
      "Coding agents",
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
