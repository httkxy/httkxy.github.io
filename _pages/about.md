---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    /* ===== Hero ===== */
    .hero {
        text-align: center;
        padding: 1.5em 0 0.8em;
        margin-bottom: 0.5em;
    }
    .hero h1 {
        font-family: 'Lora', Georgia, 'Times New Roman', serif;
        font-size: 2.4em;
        font-weight: 600;
        color: #1a202c;
        margin-bottom: 0.25em;
        letter-spacing: -0.5px;
    }
    .hero .tagline {
        font-size: 1.05em;
        color: #64748b;
        font-weight: 400;
    }
    .hero .tagline a {
        color: #3b82f6;
        text-decoration: none;
    }
    .hero .tagline a:hover {
        text-decoration: underline;
    }
    .hero .stats {
        display: flex;
        justify-content: center;
        gap: 2em;
        margin-top: 0.8em;
        flex-wrap: wrap;
    }
    .hero .stat-item {
        text-align: center;
    }
    .hero .stat-value {
        font-size: 1.3em;
        font-weight: 700;
        color: #1e40af;
    }
    .hero .stat-label {
        font-size: 0.8em;
        color: #94a3b8;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }
    .update-time {
        text-align: center;
        font-size: 0.75em;
        color: #cbd5e1;
        margin-top: 0.3em;
    }

    /* ===== Section Headings ===== */
    h2 {
        font-family: 'Lora', Georgia, serif !important;
        font-weight: 600 !important;
        color: #1e293b !important;
        border-bottom: 2px solid #e2e8f0;
        padding-bottom: 0.35em;
        margin-top: 1.6em !important;
        margin-bottom: 0.6em !important;
        font-size: 1.35em !important;
    }

    /* ===== News List ===== */
    h2 + ul {
        list-style: none;
        padding-left: 0;
    }
    h2 + ul li {
        padding: 0.5em 0 0.5em 1em;
        border-left: 3px solid #e2e8f0;
        margin-bottom: 0.15em;
        transition: border-color 0.2s;
        font-size: 0.95em;
        line-height: 1.55;
    }
    h2 + ul li:hover {
        border-left-color: #3b82f6;
    }

    /* ===== Education Cards ===== */
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 16px;
    }
    .experience-card {
        display: flex;
        align-items: center;
        background: #f8fafc;
        border-radius: 10px;
        padding: 18px;
        border: 1px solid #e2e8f0;
        transition: box-shadow 0.25s, transform 0.25s;
        box-sizing: border-box;
    }
    .experience-card:hover {
        box-shadow: 0 4px 20px rgba(0,0,0,0.08);
        transform: translateY(-1px);
    }
    .experience-logo {
        width: 52px;
        height: 52px;
        margin-right: 16px;
        border-radius: 8px;
        object-fit: contain;
        flex-shrink: 0;
    }
    .experience-info {
        font-size: 0.92em;
        color: #475569;
        line-height: 1.5;
    }
    .experience-info strong {
        font-size: 1.05em;
        color: #1e293b;
    }
    .experience-info a {
        color: #3b82f6;
        text-decoration: none;
    }
    .experience-info a:hover {
        text-decoration: underline;
    }

    /* ===== Project Cards ===== */
    .project-item {
        border: 1px solid #e2e8f0;
        margin: 12px 0;
        background: #f8fafc;
        padding: 18px 22px;
        border-radius: 10px;
        transition: box-shadow 0.25s, transform 0.25s;
    }
    .project-item:hover {
        transform: translateY(-2px);
        box-shadow: 0 6px 24px rgba(0,0,0,0.07);
    }
    .project-title {
        color: #1e40af;
        font-weight: 650;
        font-size: 1.05em;
        margin-bottom: 4px;
    }
    .project-meta {
        color: #64748b;
        font-size: 0.85em;
        margin-bottom: 6px;
    }
    .project-item p {
        color: #475569;
        font-size: 0.92em;
        line-height: 1.65;
        margin-top: 6px;
        margin-bottom: 0;
    }

    /* ===== Honors Box ===== */
    .blue-box {
        border: 1px solid #e2e8f0;
        border-radius: 10px;
        padding: 22px 24px;
        margin: 12px 0;
        background: #f8fafc;
    }
    .blue-box h3 {
        color: #1e40af;
        margin-top: 0.8em;
        margin-bottom: 0.4em;
        font-size: 1em;
        font-weight: 650;
        padding-bottom: 6px;
        border-bottom: 1px solid #e2e8f0;
    }
    .blue-box h3:first-child {
        margin-top: 0;
    }
    .blue-box ul {
        margin: 0.3em 0 0 0;
        padding-left: 1.3em;
        color: #475569;
        font-size: 0.92em;
        line-height: 1.7;
    }

    /* ===== Global ===== */
    div.markdown-body a, a {
        color: #3b82f6;
        text-decoration: none;
        transition: color 0.2s;
    }
    div.markdown-body a:hover, a:hover {
        color: #1d4ed8;
        text-decoration: underline;
    }

    @media (max-width: 768px) {
        .hero h1 { font-size: 1.8em; }
        .hero .stats { gap: 1.2em; }
    }
</style>

<div class="hero">
    <h1>Hi, I'm Tianyu Hao 👋</h1>
    <p class="tagline">Undergrad @ <a href="https://en.nwpu.edu.cn/" target="_blank">NWPU</a> → PhD @ <a href="https://en.sjtu.edu.cn/" target="_blank">SJTU</a> · AIGC &amp; MLLM</p>
    <p class="update-time">last update: 2026.05</p>
</div>

Latest News
======

- 📝 **[2026.05]** One co-first-author paper submitted to **ECCV 2026** (CCF-B): In-context Region-based Drag: Drag Any Region to Any Shape.

- 🏭 **[2025.10 - Present]** Launched the Few-shot Defect Image Generation project as project lead.

- 🎓 **[2025.10]** Recommended for direct PhD admission to **Shanghai Jiao Tong University** (SJTU); started interning at the [**BCMI Lab**](https://bcmi.sjtu.edu.cn/){:target="_blank"}.

- 🧠 **[2025.03 - 2025.06]** Completed research training: efficient LLM fine-tuning under resource constraints.

- 🥇 **[2025.02]** Won the **Meritorious Winner (International First Prize)** in the Mathematical Contest in Modeling ([MCM/ICM](https://www.comap.com/contests/mcm-icm){:target="_blank"}).

- 🎓 **[2024.12]** Awarded Outstanding Student & Second-Class Scholarship.

- 🥈 **[2024.09]** Won the **National Second Prize** in the Contemporary Undergraduate Mathematical Contest in Modeling ([CUMCM](https://en.mcm.edu.cn/){:target="_blank"}).

- 📜 **[2024.08 - 2024.11]** Completed National Invention Patent on data augmentation for UAV vision-language navigation (first student inventor).

- 🎖️ **[2024.04]** Won the **Excellence Award** in the "Qizhi Cup" Machine Vision Design Competition.

- 🥇 **[2023.12]** Won the **Provincial First Prize** in the 15th National College Student Mathematics Competition.

- 🎓 **[2023.12]** Awarded Outstanding Student & First-Class Scholarship.


Education
======
<div class="experience-container">
  <div class="experience-card">
      <img src="../images/NWPU.png" alt="NWPU logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://en.nwpu.edu.cn/" target="_blank">Northwestern Polytechnical University</a></strong><br>
          2022.09 - 2026.06<br>
          B.E. in Computer Science and Technology<br>
          GPA: 3.918/4.1 (Rank 8/192) | CET-6: 559
      </div>
  </div>

  <div class="experience-card">
      <img src="../images/SJTU.png" alt="SJTU logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://en.sjtu.edu.cn/" target="_blank">Shanghai Jiao Tong University</a></strong><br>
          2026.09 - Incoming<br>
          Ph.D. in Computer Science<br>
          Research: Image Generation & Editing
      </div>
  </div>
</div>

Projects
======

<div class="project-item">
<div class="project-title">🏭 Few-shot Defect Image Generation for Industrial Anomaly Detection</div>
<div class="project-meta">Project Lead | 2025.10 - Present</div>
<p>Designed a few-shot defect image generation method based on vision foundation models and flow matching, addressing the scarcity of defect samples in industrial anomaly detection. Formulated defect synthesis as a context-aware local editing task: a dual-branch defect feature extraction module captures fine-grained defect semantics, while a FLUX.1 Kontext-based generation pipeline combines inpaint-aware flow matching, defect feature matching, and normal region preservation constraints. A "Generate-Select-Refine" three-stage mask generation flow was proposed to improve defect-to-image alignment quality. Responsible for method design, model training, and experimental analysis.</p>
</div>

<div class="project-item">
<div class="project-title">⚡ Efficient LLM Fine-tuning under Resource Constraints</div>
<div class="project-meta">Research Training Project | 2025.03 - 2025.06</div>
<p>Investigated memory optimization for LLM fine-tuning in resource-constrained environments. Built a GPU memory estimation model for Decoder-only Transformers, quantifying various memory demands. Systematically surveyed LoRA, QLoRA, activation recomputation, and parameter offloading strategies from both algorithmic and system perspectives. Conducted comparative experiments with 5 fine-tuning strategies on LLaMA3.2-3B using the GSM8K dataset, evaluating memory cost, training time, and convergence quality.</p>
</div>

<div class="project-item">
<div class="project-title">📜 National Invention Patent: Data Augmentation for UAV Vision-Language Navigation</div>
<div class="project-meta">First Student Inventor | 2024.08 - 2024.11</div>
<p>Proposed a hierarchical instruction generation model based on a two-scale graph Transformer (DUET) and a large language model to address data scarcity and low instruction quality in UAV vision-language navigation. The method uses heuristic search to generate paths, extracts multi-modal features via ViT-B/16 and BERT with a dynamic merging strategy, and leverages DUET's dual-scale visual representations with LLM contextual reasoning to generate high-quality navigation instructions. Filtered by BLEU metrics, the augmented data significantly improves instruction conciseness and key action density.</p>
</div>

Honors & Awards
======

<div class="blue-box">

<h3>🏆 Scholarships</h3>
<ul>
<li>First-Class Scholarship, NWPU (2023)</li>
<li>Second-Class Scholarship, NWPU (2024, 2025)</li>
</ul>

<h3>🎖️ Honorary Titles</h3>
<ul>
<li>Outstanding Student, NWPU (2023, 2024, 2025)</li>
</ul>

<h3>🥇 Competition Awards</h3>
<ul>
<li>Mathematical Contest in Modeling (MCM/ICM) - <span style="color: #2E5C8A;"><strong>Meritorious Winner (International First Prize)</strong></span> (2025)</li>
<li>Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM) - <span style="color: #2E5C8A;"><strong>National Second Prize</strong></span> (2024)</li>
<li>National College Student Mathematics Competition - <span style="color: #2E5C8A;"><strong>Provincial First Prize</strong></span> (2023)</li>
<li>"Qizhi Cup" Machine Vision Design Competition - Excellence Award (2024)</li>
</ul>

</div>
