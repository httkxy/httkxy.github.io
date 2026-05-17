---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    /* Modify from https://selen-suyue.github.io/ */
    .experience-card {
        display: flex;
        align-items: center;
        background: #F9F9F9;
        border-radius: 12px;
        padding: 16px;
        margin-bottom: 0px;
        border-left: 4px solid #4A90E2;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .experience-card:hover {
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }
    .experience-logo {
        width: 60px;
        height: 60px;
        margin-right: 20px;
        border-radius: 8px;
        object-fit: contain;
    }
    .experience-info {
        font-size: 15px;
        color: #494E52;
        font-family: "Segoe UI", sans-serif;
    }
    .experience-info strong {
        font-size: 16px;
        color: #494E52;
    }
    .experience-info a {
        text-decoration: none;
        color: #3498DB;
        transition: color 0.3s ease;
    }
    .experience-info a:hover {
        color: #154360;
    }
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
    }
    .experience-card {
        box-sizing: border-box;
    }

    .blue-box {
        border: 2px solid #4A90E2;
        border-radius: 8px;
        padding: 20px;
        margin: 15px 0;
        box-shadow: 0 2px 8px rgba(74, 144, 226, 0.15);
    }
    .blue-box h3 {
        color: #2E5C8A;
        margin-top: 0;
        border-bottom: 2px solid #4A90E2;
        padding-bottom: 8px;
    }

    .list-item.publication {
        display: flex;
        align-items: flex-start;
        background: #F9F9F9;
        border-radius: 12px;
        padding: 20px;
        margin-bottom: 20px;
        border-left: 4px solid #4A90E2;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .list-item.publication:hover {
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }
    .list-item.publication .thumbnail {
        flex: 0 0 35%;
        max-width: 200px;
        margin-right: 20px;
        border-radius: 8px;
        overflow: hidden;
    }
    .list-item.publication .thumbnail img {
        width: 200px;
        height: auto;
        display: block;
        object-fit: contain;
        border: 1px solid #E1E8ED;
        border-radius: 8px;
    }
    .list-item.publication .project-description {
        flex: 1;
        font-family: "Segoe UI", sans-serif;
    }
    .list-item.publication .project-description h3 {
        margin-top: 0;
        margin-bottom: 10px;
        font-size: 1.15em;
    }
    .list-item.publication .project-description h3 a {
        color: #2E5C8A;
        /* font-size: 18px; */
        text-decoration: none;
    }
    .list-item.publication .project-description .authors {
        font-size: 12px;
        color: #494E52;
        margin-bottom: 5px;
    }
    .list-item.publication .project-description .venue {
        font-size: 15px;
        color: #6B9BD1;
        margin-bottom: 5px;
    }
    .list-item.publication .project-description p {
        margin: 0;
        font-size: 0.95em;
        line-height: 1.6;
        color: #494E52;
    }
    @media (max-width: 768px) {
        .list-item.publication {
            flex-direction: column;
        }
        .list-item.publication .thumbnail {
            flex: 0 0 100%;
            max-width: 100%;
            margin-right: 0;
            margin-bottom: 15px;
        }
        .list-item.publication .thumbnail img {
            width: 100%;
            max-width: 200px;
            margin: 0 auto;
        }
    }

    .project-item {
        border: 1px solid #DDDDDD;
        margin: 15px 0;
        background-color: #F9F9F9;
        padding: 15px 20px;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .project-item:hover {
        transform: translateY(-2px);
        box-shadow: 0 8px 15px rgba(74, 144, 226, 0.2);
    }

    .project-title {
        color: #2E5C8A;
        font-weight: bold;
        font-size: 1.1em;
        margin-bottom: 5px;
    }

    .project-meta {
        color: #4A90E2;
        font-size: 0.9em;
    }

    .project-item p {
        color: #494E52;
        font-size: 0.95em;
        line-height: 1.6;
        margin-top: 8px;
        margin-bottom: 0;
    }

    details summary {
        cursor: pointer;
        font-weight: bold;
    }

    .update-time {
        font-size: 5px;
        color: #6B9BD1;
        font-style: italic;
        text-align: right;
        margin-bottom: 20px;
    }
</style>

<html> 
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,500;1,500&display=swap');
        body {
            font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
            font-size: 17px;
        }
        h1, h2 {
            margin-top: 0.5em !important;
        }
        .main-heading {
            font-size: 35px;
            font-family: 'Lora', serif;
            font-weight: 500;
            text-align: center;
            color: #2E86C1;
        }
        div.markdown-body a,a {
            text-decoration: none !important;
            color: #3498DB;
            transition: all 0.3s ease;
        }
        div.markdown-body a:hover, a:hover {
            color: #195275ff;
            text-decoration: underline;
        }
    </style>
</head>
<body>
<h1 class="main-heading">👋 Hello, World! Welcome to My Space 🚀</h1>
<p class="update-time">last update: 2026.05</p>
</body>
</html>

I am a senior undergraduate student majoring in Computer Science at the School of Computer Science, [Northwestern Polytechnical University](https://en.nwpu.edu.cn/){:target="_blank"} (NWPU, 985/211/双一流). I was recommended for direct PhD admission to [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/){:target="_blank"} (SJTU) in October 2025 and will start in Fall 2026, focusing on **image generation and editing**. **GPA: 3.918/4.1** (rank **8/192**). **CET-6: 559**.

Latest News
======

- 📝 **[2026.05]** One co-first-author paper submitted to **ECCV 2026** (CCF-B): In-context Region-based Drag: Drag Any Region to Any Shape.

- 🏭 **[2025.10 - Present]** Launched the Few-shot Defect Image Generation project as project lead.

- 🎓 **[2025.10]** Recommended for direct PhD admission to **Shanghai Jiao Tong University** (SJTU); started interning at the [**BCMI Lab**](https://bcmi.sjtu.edu.cn/member.cn.html){:target="_blank"}.

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
      <img src="../images/ZJU.png" alt="SJTU logo" class="experience-logo">
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
