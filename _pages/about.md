---
layout: home
permalink: /
title: "Yiming Zeng"
last_modified_at: 2026-09-20
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<section class="profile-hero" aria-labelledby="profile-name">
  <div class="profile-hero__content">
    <p class="profile-kicker">PhD Candidate · University of Connecticut</p>
    <h1 id="profile-name">Yiming Zeng</h1>

    <p class="profile-lead">I am a <strong>PhD candidate in Computer Science at the University of Connecticut (UConn)</strong>, advised by <strong>Dr. Tingting Yu</strong>. I also collaborate with <strong>Dr. Shangqian Gao</strong> on large language models. I am currently a <strong>Research Scientist Intern</strong> with the <strong>AI Center at Samsung Research America</strong>. Previously, I was a <strong>Research Scientist Intern at ByteDance</strong> in San Jose, a software engineer at <strong>Baidu</strong>, and an AI researcher at <strong>UPMC Hillman Cancer Center</strong>.</p>

    <p class="research-label">My research focuses on:</p>
    <ol class="research-interests">
      <li><strong>Efficient and Adaptive Large Language Models</strong></li>
      <li><strong>LLM Post-training, Evaluation, and Agentic AI</strong></li>
      <li><strong>Natural Language Processing for Healthcare and Scientific Discovery</strong></li>
    </ol>

    <nav class="profile-links" aria-label="Profile links">
      <a href="mailto:yimingzeng99@gmail.com"><i class="fas fa-envelope" aria-hidden="true"></i> Email</a>
      <a href="https://scholar.google.com/citations?user=iVODU-AAAAAJ"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar</a>
      <a href="https://github.com/StuRinDQB"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </nav>

    <p class="collaboration-note"><i class="fas fa-paper-plane" aria-hidden="true"></i> I expect to graduate in May 2027 and am currently on the job market for full-time Research Scientist and Applied Scientist positions.</p>
  </div>

  <figure class="profile-photo">
    <img src="{{ '/images/Yiming_Zeng.jpg' | relative_url }}" alt="Portrait of Yiming Zeng" fetchpriority="high">
  </figure>
</section>

<section class="home-section" aria-labelledby="news">
  <h2 id="news">News</h2>
  <div class="news-box" tabindex="0">
    <p><time datetime="2026-09">2026.09</time> After completing my summer internship at <strong>ByteDance</strong>, I joined the <strong>AI Center at Samsung Research America</strong> as a <strong>Research Scientist Intern</strong>.</p>
    <p><time datetime="2026-04">2026.04</time> I will be joining <strong>ByteDance</strong> as a <strong>Research Scientist Intern</strong> in San Jose this summer. See you in the Valley!</p>
    <p><time datetime="2026-04">2026.04</time> My first-author paper <strong>“HyperEdit: Unlocking Instruction-based Text Editing in LLMs via Hypernetworks”</strong> has been accepted to <strong>ACL 2026</strong>.</p>
    <p><time datetime="2026-02">2026.02</time> Our paper <strong>“Rethinking LLM-as-a-Judge: Representation-as-a-Judge with Small Language Models via Semantic Capacity Asymmetry”</strong> has been accepted to <strong>ICLR 2026</strong>.</p>
    <p><time datetime="2025-08">2025.08</time> My first-author paper <strong>“Bridging the Editing Gap in LLMs: FineEdit for Precise and Targeted Text Modifications”</strong> has been accepted to <strong>EMNLP 2025</strong>.</p>
    <p><time datetime="2025-08">2025.08</time> Our paper <strong>“PromptSculptor: Multi-Agent Based Text-to-Image Prompt Optimization”</strong> has been accepted to the <strong>EMNLP 2025 Demonstration Track</strong>.</p>
    <p><time datetime="2025-04">2025.04</time> I passed the PhD Qualifying Exam and became a <strong>PhD Candidate</strong>.</p>
    <p><time datetime="2024-08">2024.08</time> I began my PhD in Computer Science at UConn, working with Dr. Tingting Yu on large language models and NLP.</p>
  </div>
</section>

<section class="home-section" aria-labelledby="publications">
  <div class="section-heading">
    <h2 id="publications">Selected Publications</h2>
    <a class="section-link" href="https://scholar.google.com/citations?user=iVODU-AAAAAJ">View all on Google Scholar <span aria-hidden="true">→</span></a>
  </div>

  <div class="publication-list">
    <article class="publication-item">
      <span class="venue-badge">Preprint 2026</span>
      <div>
        <h3><a href="https://arxiv.org/abs/2608.03275">MoEGen: Mixture-of-Experts for Instance-Adaptive LoRA Generation</a></h3>
        <p><strong>Y. Zeng</strong>, L. Lu, Z. Li, Z. Li, S. Li, S. Liao, X. Wu, Z. Zhang, M. Wang, Y. Zhao, T. Yu, S. Gao</p>
        <p class="publication-venue">arXiv preprint arXiv:2608.03275, 2026</p>
        <p class="publication-abstract"><span class="publication-abstract__label">Abstract.</span> Existing mixture-of-experts approaches to parameter-efficient fine-tuning typically store a complete LoRA adapter for every expert, so storage grows with the expert pool and adaptation remains limited to those fixed experts. MoEGen instead represents experts as compact learned codes, routes each input across them, and feeds the resulting combination to a lightweight hypernetwork that generates instance-specific low-rank updates. Across eight commonsense-reasoning benchmarks and three backbone models, it consistently improves on strong static and MoE-based PEFT baselines while also performing well in joint medical- and legal-domain adaptation.</p>
      </div>
    </article>

    <article class="publication-item">
      <span class="venue-badge">ACL 2026</span>
      <div>
        <h3>HyperEdit: Unlocking Instruction-based Text Editing in LLMs via Hypernetworks</h3>
        <p><strong>Y. Zeng</strong>, J. Cao, Z. Li, W. Yu, Z. Ye, D. Xiang, T. Hua, X. Liu, S. Gao, T. Yu</p>
        <p class="publication-venue">Association for Computational Linguistics (ACL), 2026, pp. 466–480</p>
        <p class="publication-abstract"><span class="publication-abstract__label">Abstract.</span> Instruction-based editing requires a model to carry out a requested change while leaving unrelated content untouched, a requirement that generic text-generation methods often fail to satisfy. HyperEdit combines a hypernetwork that produces request-specific adaptation parameters with difference-aware regularization that concentrates supervision on modified spans. This design improves alignment with diverse editing instructions and reduces unnecessary changes, producing relative BLEU gains of 9%–30% on edited regions over leading baselines with a model of only 3B parameters.</p>
      </div>
    </article>

    <article class="publication-item">
      <span class="venue-badge">ICLR 2026</span>
      <div>
        <h3>Rethinking LLM-as-a-Judge: Representation-as-a-Judge with Small Language Models via Semantic Capacity Asymmetry</h3>
        <p>Z. Li, Y. Zhang, M. Li, Y. Ji, <strong>Y. Zeng</strong>, N. Cheng, Y. Zhu, Y. Wang, S. Wang, et al.</p>
        <p class="publication-venue">The International Conference on Learning Representations (ICLR), 2026</p>
        <p class="publication-abstract"><span class="publication-abstract__label">Abstract.</span> Prompting large language models as reference-free judges is expensive, difficult to interpret, and sensitive to prompt wording. This work shows that small language models can contain strong evaluative signals in their hidden representations even when their generation quality is limited, motivating the Semantic Capacity Asymmetry Hypothesis. Based on this insight, INSPECTOR predicts aspect-level scores directly from small-model representations without decoding. On GSM8K, MATH, and GPQA, it substantially outperforms prompted small models and approaches the judgments of full-size LLMs with greater efficiency and interpretability.</p>
      </div>
    </article>

    <article class="publication-item">
      <span class="venue-badge">EMNLP 2025</span>
      <div>
        <h3>Bridging the Editing Gap in LLMs: FineEdit for Precise and Targeted Text Modifications</h3>
        <p><strong>Y. Zeng</strong>, W. Yu, Z. Li, T. Ren, Y. Ma, J. Cao, X. Chen, T. Yu</p>
        <p class="publication-venue">Conference on Empirical Methods in Natural Language Processing (EMNLP), 2025, pp. 2193–2206</p>
        <p class="publication-abstract"><span class="publication-abstract__label">Abstract.</span> State-of-the-art language models still have difficulty making precise, instruction-driven edits without introducing unrelated changes, especially in structured domains. The paper introduces InstrEditBench, an automatically constructed benchmark with more than 30,000 editing tasks covering Wikipedia articles, LaTeX, source code, and database languages, together with FineEdit, a model trained specifically for accurate context-aware editing. FineEdit improves on Gemini by about 10% in single-turn editing, exceeds Llama-3.2-3B and Mistral-7B-OpenOrca by larger margins, and generalizes effectively to realistic multi-turn scenarios.</p>
      </div>
    </article>

    <article class="publication-item">
      <span class="venue-badge">IEEE BHI 2024</span>
      <div>
        <h3>ReguloGPT: Harnessing GPT for End-to-End Knowledge Graph Construction of Molecular Regulatory Pathways</h3>
        <p>X. Wu, S. Jo, <strong>Y. Zeng</strong>, A. Das, T. H. Zhang, P. Patel, Y. Wei, L. Li, S. J. Gao, et al.</p>
        <p class="publication-venue">2024 IEEE EMBS International Conference on Biomedical and Health Informatics (BHI)</p>
        <p class="publication-abstract"><span class="publication-abstract__label">Abstract.</span> Biomedical knowledge-graph systems often struggle to capture the hierarchical relationships and biological context found in molecular regulatory pathways. ReguloGPT uses GPT-4 in-context learning to jointly recognize entities, extract N-ary regulatory relationships, and predict context, embedding that context directly into graph edges to reduce semantic inconsistencies. Evaluation on a benchmark of 400 annotated PubMed titles shows clear gains over existing methods, while a GPT-4-based G-Eval procedure closely tracks manual evaluation. The resulting m<sup>6</sup>A knowledge graph helps reveal regulatory mechanisms associated with cancer phenotypes.</p>
      </div>
    </article>
  </div>
</section>

<section class="home-section" aria-labelledby="industry-experience">
  <h2 id="industry-experience">Industry Experience</h2>
  <div class="industry-list">
    <article class="industry-item">
      <a class="industry-logo" href="https://research.samsung.com/aicenter_mountainview" aria-label="Samsung Research America AI Center">
        <img src="{{ '/images/samsung-wordmark.svg' | relative_url }}" alt="Samsung" width="150" height="23" loading="lazy">
      </a>
      <div class="industry-details">
        <div class="industry-heading">
          <h3><a href="https://research.samsung.com/aicenter_mountainview">Samsung Research America</a></h3>
          <p class="industry-dates"><time datetime="2026-09">09/2026</time> – Present</p>
        </div>
        <p class="industry-role">Research Scientist Intern <span aria-hidden="true">·</span> Mountain View, California</p>
        <p class="industry-team">AI Center</p>
      </div>
    </article>

    <article class="industry-item">
      <a class="industry-logo" href="https://www.bytedance.com/en/" aria-label="ByteDance">
        <img src="{{ '/images/bytedance-wordmark.svg' | relative_url }}" alt="ByteDance" width="150" height="26" loading="lazy">
      </a>
      <div class="industry-details">
        <div class="industry-heading">
          <h3><a href="https://www.bytedance.com/en/">ByteDance (TikTok)</a></h3>
          <p class="industry-dates"><time datetime="2026-05">05/2026</time> – <time datetime="2026-08">08/2026</time></p>
        </div>
        <p class="industry-role">Research Scientist Intern <span aria-hidden="true">·</span> San Jose, California</p>
        <p class="industry-team">Doubao Enterprise Agent Team at AML / <a href="https://www.volcengine.com/product/ark">Volcano Engine Ark</a></p>
      </div>
    </article>
  </div>
</section>

<section class="home-section" aria-labelledby="teaching-service">
  <h2 id="teaching-service">Teaching &amp; Service</h2>
  <div class="experience-grid">
    <article class="info-card">
      <p class="card-label">Teaching</p>
      <h3>Adjunct Lecturer · CSE2102</h3>
      <p>University of Connecticut</p>
      <ul>
        <li>Taught React.js fundamentals, including Hooks, state management, and component-based UI design.</li>
        <li>Guided students in deploying React and Express applications to AWS.</li>
      </ul>
    </article>

    <article class="info-card">
      <p class="card-label">Academic Service</p>
      <h3>Conference Reviewer</h3>
      <p>ICLR 2026 · NeurIPS 2025 · AAAI 2025</p>
      <p class="card-note">Contributing peer reviews across machine learning, natural language processing, and AI.</p>
    </article>
  </div>
</section>

<section class="home-section interests-section" aria-labelledby="interests">
  <h2 id="interests">Beyond Research</h2>
  <p>Table tennis · Running &amp; fitness · Pop music · Road trips</p>
</section>
