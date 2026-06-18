---
permalink: /zh/
author_profile: true
---

<style>
    /* ===== Hero ===== */
    .hero {
        text-align: center;
        padding: 1.5em 0 0.8em;
        margin-bottom: 0.5em;
    }
    .hero h1 {
        font-family: 'Lora', 'Noto Serif SC', Georgia, 'Times New Roman', serif;
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
        font-family: 'Lora', 'Noto Serif SC', Georgia, serif !important;
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
    <p class="tagline">本科 @ <a href="https://www.nwpu.edu.cn/" target="_blank">西北工业大学</a> → 博士 @ <a href="https://www.sjtu.edu.cn/" target="_blank">上海交通大学</a> · AIGC & MLLM</p>
    <p class="update-time">更新于 2026.06</p>
</div>

Latest News
======

- 📝 **[2026.06]** 一篇共同第一作者论文被 **ECCV 2026** (CCF-B) 接收：In-context Region-based Drag: Drag Any Region to Any Shape

- 🏭 **[2025.10 - 至今]** 作为项目负责人，启动面向工业缺陷检测的小样本缺陷图像生成项目。

- 🎓 **[2025.10]** 直博保研至**上海交通大学**计算机学院，同时开始在 [**BCMI 实验室**](https://bcmi.sjtu.edu.cn/){:target="_blank"} 实习。

- 🧠 **[2025.03 - 2025.06]** 完成科研训练项目：资源受限场景下的大模型微调训练技术研究与实践。

- 🥇 **[2025.02]** 在[**美国大学生数学建模竞赛**](https://www.comap.com/contests/mcm-icm){:target="_blank"}（MCM/ICM）中荣获**国际级一等奖（M奖）**。

- 🎓 **[2024.12]** 获校优秀大学生及二等奖学金。

- 🥈 **[2024.09]** 在[**全国大学生数学建模竞赛**](https://www.mcm.edu.cn/){:target="_blank"}（CUMCM）中荣获**国家级二等奖**。

- 📜 **[2024.08 - 2024.11]** 完成国家发明专利《一种用于无人机视觉语言导航任务的数据增广方法》（学生第一发明人）。

- 🎖️ **[2024.04]** 在“启智杯”机器视觉设计大赛中荣获**优秀奖**。

- 🥇 **[2023.12]** 在**第15届全国大学生数学竞赛**中荣获**省级一等奖**。

- 🎓 **[2023.12]** 获校优秀大学生及一等奖学金。


教育背景
======
<div class="experience-container">
  <div class="experience-card">
      <img src="../images/NWPU.png" alt="NWPU logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://www.nwpu.edu.cn/" target="_blank">西北工业大学</a></strong><br>
          2022.09 - 2026.06<br>
          计算机科学与技术 工学学士<br>
          GPA: 3.918/4.1 (专业排名 8/192) | CET-6: 559
      </div>
  </div>

  <div class="experience-card">
      <img src="../images/SJTU.png" alt="SJTU logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://www.sjtu.edu.cn/" target="_blank">上海交通大学</a></strong><br>
          2026.09 - 即将入学<br>
          计算机学院 博士研究生<br>
          研究方向：AIGC & MLLM
      </div>
  </div>
</div>

项目经历
======

<div class="project-item">
<div class="project-title">🏭 面向工业缺陷检测的小样本缺陷图像生成</div>
<div class="project-meta">项目负责人 | 2025.10 - 至今</div>
<p>针对工业异常检测中缺陷样本稀缺的问题，设计并实现基于视觉基础模型与流匹配生成框架的小样本缺陷图像生成方法。将缺陷合成建模为上下文感知的局部编辑任务，构建双分支缺陷特征提取模块学习细粒度缺陷语义，基于 FLUX.1 Kontext 设计结合 inpaint-aware flow matching、缺陷特征匹配和正常区域保持约束的生成训练目标，提出 "Generate-Select-Refine" 三阶段掩码生成流程以提升缺陷区域与目标图像的对齐质量。主要负责方法设计、模型训练与实验分析。</p>
</div>

<div class="project-item">
<div class="project-title">⚡ 资源受限场景下的大模型微调训练技术研究与实践</div>
<div class="project-meta">科研训练项目 | 2025.03 - 2025.06</div>
<p>围绕资源受限环境下大模型微调中的显存优化问题，深入研究高效微调方法的原理与工程实现。建立 Decoder-only Transformer 显存开销评估模型，量化各类内存需求；系统调研 LoRA、QLoRA、激活值重计算与参数卸载等主流方法，从算法和系统层面分析优缺点；基于 GSM8K 数据集在 LLaMA3.2-3B 上完成 5 种微调策略对比实验，评估各方法在显存开销、训练时长与收敛质量方面的表现。</p>
</div>

<div class="project-item">
<div class="project-title">📜 国家发明专利：一种用于无人机视觉语言导航任务的数据增广方法</div>
<div class="project-meta">学生第一发明人 | 2024.08 - 2024.11</div>
<p>针对无人机视觉语言导航任务中数据稀缺、指令质量差及长路径下关键动作稀疏等问题，提出基于双尺度图 Transformer（DUET）和大语言模型的层次化指令生成模型。通过启发式搜索生成路径，利用 ViT-B/16 和 BERT 提取多模态特征，动态合并策略减少冗余，借助 DUET 双尺度视觉表征与 LLM 上下文推理生成高质量导航指令，经 BLEU 指标筛选形成增广数据，显著提升指令简洁性与关键动作密度。</p>
</div>

荣誉奖项
======

<div class="blue-box">

<h3>🏆 奖学金</h3>
<ul>
<li>校级一等奖学金（2023）</li>
<li>校级二等奖学金（2024、2025）</li>
</ul>

<h3>🎖️ 荣誉称号</h3>
<ul>
<li>校优秀大学生（2023、2024、2025）</li>
</ul>

<h3>🥇 竞赛获奖</h3>
<ul>
<li>美国大学生数学建模竞赛 (MCM/ICM) - <span style="color: #2E5C8A;"><strong>国际级一等奖 / M奖</strong></span>（2025）</li>
<li>全国大学生数学建模竞赛 (CUMCM) - <span style="color: #2E5C8A;"><strong>国家级二等奖</strong></span>（2024）</li>
<li>第15届全国大学生数学竞赛 - <span style="color: #2E5C8A;"><strong>省级一等奖</strong></span>（2023）</li>
<li>"启智杯"机器视觉设计大赛 - 优秀奖（2024）</li>
</ul>

</div>
