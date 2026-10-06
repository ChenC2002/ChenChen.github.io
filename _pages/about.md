---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a second-year Ph.D. student in Computer Science at the University of Kansas, advised by [Dr. Zijun Yao](https://ittc.ku.edu/~zyao/).

I develop learning methods for AI agents that reason reliably and use tools and external knowledge efficiently. My research spans LLM post-training, reinforcement learning, and graph learning, with applications in healthcare.

Previously, I received my B.E. in Artificial Intelligence from Guangdong University of Technology in 2024, where I worked on interpretable graph learning for social media analysis with [Dr. Fenghuan Li](https://dblp.org/pid/07/10130.html).

[Curriculum Vitae](https://drive.google.com/file/d/15Tjkj__hEPyMDef0W3BPiehrk6DqvqxN/view?usp=sharing) · [Google Scholar](https://scholar.google.com/citations?user=3PExFM8AAAAJ) · [GitHub](https://github.com/ChenC2002)


## Current Research

<article class="current-research">
  <div class="current-research__status">
    Submitted to ICLR 2027
  </div>

  <h3 class="selected-pub__title">
    <a
      href="https://drive.google.com/file/d/1spXfVC_miS_9d88gxZasExLFpxCqvY9a/view?usp=drivesdk"
      target="_blank"
      rel="noopener"
    >
      Where Credit Lands: Verifiable Step Credit for Bounded-Memory EHR Agents
    </a>
  </h3>

  <p class="selected-pub__summary">
    Critic-free agent post-training using verifiable process rewards and
    same-state replay to improve retrieval, memory, and stopping decisions.
  </p>

  <div class="selected-pub__links">
    <a
      href="https://drive.google.com/file/d/1spXfVC_miS_9d88gxZasExLFpxCqvY9a/view?usp=drivesdk"
      target="_blank"
      rel="noopener"
      aria-label="Read the VAPA manuscript"
    >Paper</a>

    <a
      href="https://anonymous.4open.science/r/VAPA"
      target="_blank"
      rel="noopener"
      aria-label="View the VAPA code"
    >Code</a>
  </div>
</article>


## Selected Publications

Selected first-author papers. See [Google Scholar](https://scholar.google.com/citations?user=3PExFM8AAAAJ) for the full publication list.

<div class="selected-pubs">

  <!-- BAR -->
  <article class="selected-pub">
    <div class="selected-pub__media">
      <div class="selected-pub__badge">NeurIPS 2026</div>

      <a
        class="selected-pub__figure"
        href="{{ '/images/BAR.png' | relative_url }}"
        target="_blank"
        rel="noopener"
        aria-label="Open full-size BAR framework image"
      >
        <div class="selected-pub__thumbnail">
          <img
            src="{{ '/images/BAR.png' | relative_url }}"
            alt="Overview of BAR's evidence graphs and budget-aware reasoning loop"
            loading="lazy"
            decoding="async"
          >
        </div>
      </a>
    </div>

    <div class="selected-pub__content">
      <h3 class="selected-pub__title">
        <a
          href="https://drive.google.com/file/d/1Zdz0E5MgfJeQ6dqonnQETAl-5FZhgAXG/view?usp=drivesdk"
          target="_blank"
          rel="noopener"
        >
          Cite What You Explore: Budget-Aware LLM Reasoning over Medical KGs
          with Verifiable Evidence
        </a>
      </h3>

      <div class="selected-pub__authors">
        <strong>Chen Chen</strong>, D. Wang, M. Liu, and Z. Yao
      </div>

      <p class="selected-pub__summary">
        A budget-aware agent that plans graph retrieval, verifies evidence,
        and learns when to revise or stop.
      </p>

      <div class="selected-pub__links">
        <a
          href="https://drive.google.com/file/d/1Zdz0E5MgfJeQ6dqonnQETAl-5FZhgAXG/view?usp=drivesdk"
          target="_blank"
          rel="noopener"
          aria-label="Read the BAR paper"
        >Paper</a>

        <a
          href="https://github.com/ChenC2002/BAR"
          target="_blank"
          rel="noopener"
          aria-label="View the BAR GitHub repository"
        >Code</a>
      </div>
    </div>
  </article>

  <!-- ReTA -->
  <article class="selected-pub">
    <div class="selected-pub__media">
      <div class="selected-pub__badge">EMNLP 2026 · Main</div>

      <a
        class="selected-pub__figure"
        href="{{ '/images/ReTA Poster.png' | relative_url }}"
        target="_blank"
        rel="noopener"
        aria-label="Open full-size ReTA image"
      >
        <div class="selected-pub__thumbnail">
          <img
            src="{{ '/images/ReTA Poster.png' | relative_url }}"
            alt="Overview of ReTA's adaptive knowledge augmentation"
            loading="lazy"
            decoding="async"
          >
        </div>
      </a>
    </div>

    <div class="selected-pub__content">
      <h3 class="selected-pub__title">
        <a
          href="https://arxiv.org/abs/2609.01839"
          target="_blank"
          rel="noopener"
        >
          Import What You Need: Learning When and How to Augment EHR Graphs
          with External Knowledge
        </a>
      </h3>

      <div class="selected-pub__authors">
        <strong>Chen Chen</strong>, M. N. Kerdabadi, D. Wang,
        M. Liu, and Z. Yao
      </div>

      <p class="selected-pub__summary">
        An RL policy that learns when and how to incorporate external knowledge,
        balancing predictive benefit against augmentation cost.
      </p>

      <div class="selected-pub__links">
        <a
          href="https://arxiv.org/abs/2609.01839"
          target="_blank"
          rel="noopener"
          aria-label="Read the ReTA paper"
        >Paper</a>

        <a
          href="https://github.com/ChenC2002/ReTA"
          target="_blank"
          rel="noopener"
          aria-label="View the ReTA GitHub repository"
        >Code</a>
      </div>
    </div>
  </article>

  <!-- HSNPL -->
  <article class="selected-pub">
    <div class="selected-pub__media">
      <div class="selected-pub__badge">KBS 2025</div>

      <a
        class="selected-pub__figure"
        href="{{ '/images/HSNPL.png' | relative_url }}"
        target="_blank"
        rel="noopener"
        aria-label="Open full-size HSNPL framework image"
      >
        <div class="selected-pub__thumbnail">
          <img
            src="{{ '/images/HSNPL.png' | relative_url }}"
            alt="Overview of HSNPL's prompt-enhanced heterogeneous graph learning"
            loading="lazy"
            decoding="async"
          >
        </div>
      </a>
    </div>

    <div class="selected-pub__content">
      <h3 class="selected-pub__title">
        <a
          href="https://doi.org/10.1016/j.knosys.2025.113215"
          target="_blank"
          rel="noopener"
        >
          Heterogeneous Subgraph Network with Prompt Learning for
          Interpretable Depression Detection on Social Media
        </a>
      </h3>

      <div class="selected-pub__authors">
        <strong>Chen Chen</strong>, F. Li, H. Chen, and Y. Lin
      </div>

      <div class="selected-pub__venue">
        Knowledge-Based Systems
      </div>

      <p class="selected-pub__summary">
        Prompt-enhanced graph learning that combines semantic and structural
        information for interpretable depression detection.
      </p>

      <div class="selected-pub__links">
        <a
          href="https://doi.org/10.1016/j.knosys.2025.113215"
          target="_blank"
          rel="noopener"
          aria-label="Read the published HSNPL paper"
        >Paper</a>

        <a
          href="https://arxiv.org/abs/2407.09019"
          target="_blank"
          rel="noopener"
          aria-label="Read the HSNPL preprint on arXiv"
        >arXiv</a>

        <a
          href="https://github.com/ChenC2002/HSNPL-master"
          target="_blank"
          rel="noopener"
          aria-label="View the HSNPL GitHub repository"
        >Code</a>
      </div>
    </div>
  </article>

</div>


## News

- **Sep 2026:** BAR was accepted to NeurIPS 2026.
- **Aug 2026:** ReTA was accepted to the EMNLP 2026 Main Conference.
- **Feb 2025:** HSNPL was accepted for publication in Knowledge-Based Systems.
- **Jun 2024:** I graduated with the Outstanding Undergraduate Thesis Award.
