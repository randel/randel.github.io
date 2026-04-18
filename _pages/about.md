---
permalink: /
title: "Jiebiao Wang, PhD"
excerpt: "Statistical methods for single-cell and spatial omics, cellular deconvolution, and causal mediation. Applied to Alzheimer's disease and beyond."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<link rel="stylesheet" href="{{ '/assets/css/home.css' | relative_url }}">
<div class="intro-block">
  <p class="lead">
    I'm an Associate Professor in the Department of
    <a href="https://www.sph.pitt.edu/biostatistics">Biostatistics and Health Data Science</a>
    (Primary) and the
    <a href="https://www.ctsi.pitt.edu/">Clinical and Translational Science Institute</a>
    (Secondary) at the University of Pittsburgh. Before Pitt, I was a postdoc at Carnegie Mellon
    with <a href="http://www.stat.cmu.edu/~roeder/">Kathryn Roeder</a>, and earned my PhD in
    Biostatistics from the University of Chicago with <a href="https://health.uchicago.edu/faculty/lin-chen-phd">Lin Chen</a> and <a href="https://health.uchicago.edu/faculty/robert-gibbons-phd">Robert Gibbons</a>.
  </p>
<p>
    My lab develops <strong>statistical and computational methods</strong> for high-dimensional
    genomic data, with a focus on <em>single-cell and spatial omics</em>,
    <em>cellular deconvolution</em>, and <em>causal mediation analysis</em>.
    We collaborate broadly on the biology of complex diseases — <em>Alzheimer's disease</em>,
    psychiatric disorders, asthma, and cancer — using whole-genome sequencing, bulk and
    single-cell RNA-seq, DNA methylation, and proteomics.
  </p>
<p class="funding-note">
    Current funding: <strong>R01AG080590</strong> · Statistical methods for population-level
    cell-type-specific analyses of tissue omics data for Alzheimer's disease; and
    <strong>R21AG087057</strong> · Heterogeneous genetic effects and mediation in Alzheimer's disease.
  </p>
</div>
Research themes
<div class="themes-grid">
  <div class="theme-card">
    <div class="theme-kicker">Theme 01</div>
    <h3>Single-cell &amp; spatial omics</h3>
    <p>
      Statistical methods that turn population-scale single-cell and spatial transcriptomic,
      epigenomic, and proteomic data into cell-type-specific biological insight.
    </p>
  </div>
  <div class="theme-card">
    <div class="theme-kicker">Theme 02</div>
    <h3>Cellular deconvolution</h3>
    <p>
      A family of methods — <em>MIND</em>, <em>bMIND</em>, <em>EnsDeconv</em>, <em>HiDecon</em>,
      <em>scMD</em>, <em>BLEND</em>, <em>EMixed</em> — that estimate cell-type composition and
      cell-type-specific expression from bulk tissue.
    </p>
  </div>
  <div class="theme-card">
    <div class="theme-kicker">Theme 03</div>
    <h3>Causal mediation</h3>
    <p>
      Genomic mediation analysis and heterogeneous causal methods (<em>HMBART</em>, <em>CCmed</em>)
      for dissecting how genetic variation propagates through molecular intermediates to disease.
    </p>
  </div>
</div>
Featured methods
<div class="featured-pubs">
<article class="pub-card">
    <div class="pub-figure">
      <img src="{{ '/images/featured/hmbart.svg' | relative_url }}" alt="HMBART mediation diagram with BART trees">
    </div>
    <div class="pub-body">
      <div class="pub-tags"><span class="tag tag-method">Mediation</span><span class="tag tag-year">2026</span></div>
      <h3>HMBART</h3>
      <p class="pub-tagline">Heterogeneous causal mediation analysis with Bayesian additive regression trees.</p>
      <p class="pub-meta">Liu C, Qin X, Talisa VB, <strong>Wang J</strong>. <em>Biometrics</em>, accepted.</p>
      <p class="pub-links">
        <a href="https://github.com/Lewis-ChenLiu/HMBART">code</a>
      </p>
    </div>
  </article>
<article class="pub-card">
    <div class="pub-figure">
      <img src="{{ '/images/featured/blend.svg' | relative_url }}" alt="BLEND posterior integration of single-cell references">
    </div>
    <div class="pub-body">
      <div class="pub-tags"><span class="tag tag-method">Deconvolution</span><span class="tag tag-year">2025</span></div>
      <h3>BLEND</h3>
      <p class="pub-tagline">Probabilistic cellular deconvolution with individualized single-cell reference integration.</p>
      <p class="pub-meta">Huang P, Cai M, McKennan C, <strong>Wang J</strong>. <em>Genome Biology</em>, 26:328.</p>
      <p class="pub-links">
        <a href="https://doi.org/10.1186/s13059-025-03732-1">paper</a> ·
        <a href="https://github.com/Penghuihuang2000/BLEND">code</a>
      </p>
    </div>
  </article>
<article class="pub-card">
    <div class="pub-figure">
      <img src="{{ '/images/featured/scmd.svg' | relative_url }}" alt="scMD single-cell DNA methylation reference panels">
    </div>
    <div class="pub-body">
      <div class="pub-tags"><span class="tag tag-method">Epigenomics</span><span class="tag tag-year">2024</span></div>
      <h3>scMD</h3>
      <p class="pub-tagline">Cell-type deconvolution using single-cell DNA methylation references.</p>
      <p class="pub-meta">Cai M, Zhou J, McKennan C, <strong>Wang J</strong>. <em>Communications Biology</em>, 7:1. <span class="highlight-note">Editors' Highlight</span></p>
      <p class="pub-links">
        <a href="https://doi.org/10.1038/s42003-023-05690-5">paper</a> ·
        <a href="https://github.com/randel/scMD">code</a>
      </p>
    </div>
  </article>
<article class="pub-card">
    <div class="pub-figure">
      <img src="{{ '/images/featured/hidecon.svg' | relative_url }}" alt="HiDecon hierarchical cell-type tree with rare type highlighted">
    </div>
    <div class="pub-body">
      <div class="pub-tags"><span class="tag tag-method">Deconvolution</span><span class="tag tag-year">2024</span></div>
      <h3>HiDecon</h3>
      <p class="pub-tagline">Hierarchical deconvolution for accurate estimation of <em>rare</em> cell-type fractions.</p>
      <p class="pub-meta">Huang P, Cai M, Lu X, McKennan C, <strong>Wang J</strong>. <em>Annals of Applied Statistics</em>, 18(2):1178–1194.</p>
      <p class="pub-links">
        <a href="https://doi.org/10.1214/23-AOAS1829">paper</a> ·
        <a href="https://github.com/randel/HiDecon">code</a>
      </p>
    </div>
  </article>
<article class="pub-card">
    <div class="pub-figure">
      <img src="{{ '/images/featured/mind.svg' | relative_url }}" alt="MIND deconvolution from bulk tissue to cell types">
    </div>
    <div class="pub-body">
      <div class="pub-tags"><span class="tag tag-method">Deconvolution</span><span class="tag tag-year">2020 / 2021</span></div>
      <h3>MIND &amp; bMIND</h3>
      <p class="pub-tagline">Subject- and cell-type-specific gene expression from multi-measurement tissue data — frequentist and Bayesian.</p>
      <p class="pub-meta">
        <strong>Wang J</strong>, Devlin B, Roeder K. <em>Bioinformatics</em>, 36(3):782–788 (2020) ·
        <strong>Wang J</strong>, Roeder K, Devlin B. <em>Genome Research</em>, 31(10):1807–1818 (2021).
      </p>
      <p class="pub-links">
        <a href="https://doi.org/10.1093/bioinformatics/btz619">MIND paper</a> ·
        <a href="https://doi.org/10.1101/gr.268722.120">bMIND paper</a> ·
        <a href="https://github.com/randel/MIND">code</a>
      </p>
    </div>
  </article>
</div>
<p class="see-all-pubs">
  <a href="{{ '/publications/' | relative_url }}">See the full publication list →</a>
</p>
Join the lab · Collaborate
<div class="cta-grid">
<div class="cta-card cta-students">
    <div class="cta-eyebrow">Prospective students</div>
    <h3>PhD &amp; MS applicants</h3>
    <p>
      I am actively recruiting <strong>PhD students</strong> in Biostatistics and welcome
      inquiries from strong <strong>MS students</strong> interested in research assistantships.
      If you enjoy statistical methodology, programming (R/Python), and working on biological data,
      we would love to hear from you.
    </p>
    <ul class="cta-list">
      <li>Pitt Biostatistics &amp; Health Data Science <a href="https://www.sph.pitt.edu/biostatistics/phd/biostatistics">PhD program</a></li>
      <li>Applications are reviewed annually; contact me before applying</li>
    </ul>
    <a class="cta-button" href="mailto:jbwang@pitt.edu?subject=Prospective%20PhD%20student%20inquiry">Email me about joining</a>
  </div>
<div class="cta-card cta-collab">
    <div class="cta-eyebrow">Biomedical collaborators</div>
    <h3>Research collaboration</h3>
    <p>
      I collaborate with investigators across <strong>Alzheimer's disease</strong>, psychiatry,
      asthma, cancer, and related areas. Whether you have a single-cell or bulk omics dataset,
      a mediation / causal question, or a new study in design, I'm happy to discuss.
    </p>
    <ul class="cta-list">
      <li>Method development driven by real biological problems</li>
      <li>Grant co-investigator roles and paper collaborations welcome</li>
    </ul>
    <a class="cta-button cta-button-alt" href="mailto:jbwang@pitt.edu?subject=Research%20collaboration%20inquiry">Start a conversation</a>
  </div>
</div>
Recent news
<ul class="news-list">
  <li><span class="news-date">2026</span> Promoted to Associate Professor with tenure at Pitt.</li>
  <li><span class="news-date">2026</span> Selected for the Health Sciences Leadership Academy for Early Career Faculty.</li>
  <li><span class="news-date">2025</span> Chen Liu received the ASA Health Policy Statistics Section Student Paper Award for HMBART.</li>
  <li><span class="news-date">2024</span> R21 funded — heterogeneous genetic effects and mediation in Alzheimer's disease.</li>
  <li><span class="news-date">2024</span> Presented at the Senior Vice Chancellor's Research Seminar, University of Pittsburgh.</li>
  <li><span class="news-date">2024</span> Manqi Cai defended her PhD dissertation (Delta Omega Dissertation Award).</li>
  <li><span class="news-date">2023</span> R01 funded — statistical methods for population-level cell-type-specific analyses of tissue omics data in Alzheimer's disease.</li>
</ul>
