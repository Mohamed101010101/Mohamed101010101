<div align="center">

<img src="./header.svg" width="100%" alt="Mohamed Said Diab - Computational Biostatistics &amp; Evidence Synthesis" />

<br/>

<p align="center">
  <a href="https://github.com/Mohamed101010101/nma-nsclc-evidence-synthesis">
    <img src="https://img.shields.io/badge/Flagship%20Engine-nma--nsclc--evidence--synthesis-0071E3?style=for-the-badge&logo=r&logoColor=white" alt="Flagship Engine" />
  </a>
  <a href="https://mohamed101010101.github.io/nma-nsclc-evidence-synthesis/">
    <img src="https://img.shields.io/badge/Live%20Report-Interactive%20Monograph-0071E3?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Interactive Monograph" />
  </a>
  <a href="https://mohamed101010101.github.io/">
    <img src="https://img.shields.io/badge/Personal%20Website-mohamed101010101.github.io-161B22?style=for-the-badge&logo=safari&logoColor=2997FF" alt="Personal Website" />
  </a>
  <a href="https://github.com/Mohamed101010101">
    <img src="https://img.shields.io/badge/Compliance-PRISMA--NMA%202015-238636?style=for-the-badge&logoColor=white" alt="PRISMA-NMA" />
  </a>
</p>

<p align="center">
  <a href="https://orcid.org/0009-0003-3143-387X">
    <img src="https://img.shields.io/badge/ORCID-0009--0003--3143--387X-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" />
  </a>
  <a href="mailto:Mohamed.98478@Medicine.mti.edu.eg">
    <img src="https://img.shields.io/badge/Institutional%20Email-Mohamed.98478%40Medicine.mti.edu.eg-0071E3?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.mti.edu.eg/">
    <img src="https://img.shields.io/badge/Faculty%20of%20Medicine-MTI%20Cairo%2C%20Egypt-161B22?style=flat-square&logo=medscape&logoColor=2997FF" alt="Affiliation" />
  </a>
</p>

</div>

---

## 🔬 Scientific Philosophy & Mission

> *"In modern oncology, clinical practice guidelines frequently face an intractable dilemma: multiple active first-line systemic therapies exist, yet direct head-to-head randomized trials comparing all regimens are rarely available. Network Meta-Analysis (NMA) bridges this fundamental divide—synthesizing direct and indirect trial evidence through graph theory and likelihood models into a unified, mathematically coherent global evidence hierarchy."*

I design and engineer **reproducible, high-throughput computational evidence synthesis systems in R**, combining:
- **Graph-Theoretical Network Synthesis:** Multi-arm correlation-preserving NMA using the electrical network / random walk framework (`netmeta`).
- **Inconsistency Auditing & Diagnostics:** Node-splitting, design-by-treatment interaction decomposition, and NetHeat spectral matrix diagnostics.
- **Decision Analytics & Clinical Valuation:** Translating statistical hazard ratios into ASCO/ESMO Minimal Clinically Important Differences (MCID) and bivariate benefit-risk trade-offs.

---

## 🗺️ End-to-End Evidence Synthesis Pipeline Architecture

```mermaid
flowchart LR
    subgraph Data["1. Evidence Ingestion"]
        A["24 Landmark Phase II/III RCTs<br/><b>15,753 Patients</b>"] --> B["Multi-Arm Correlation Adjustment<br/><b>Covariance Preserving</b>"]
    end

    subgraph Analytics["2. Mathematical Synthesis (12 Engines)"]
        B --> C["netmeta Global Network<br/><b>Frequentist Graph Model</b>"]
        C --> D["Inconsistency Diagnostics<br/><b>Node-Splitting & NetHeat</b>"]
        C --> E["Component Decomposition<br/><b>Synergy & Additivity</b>"]
    end

    subgraph Translation["3. Clinical Decision Analytics"]
        D --> F["Hierarchy Profiling<br/><b>P-Scores & 10k Simulations</b>"]
        E --> F
        F --> G["ASCO / ESMO MCID<br/><b>Benefit-Risk Optimization</b>"]
    end

    subgraph Output["4. Publication Artifacts"]
        G --> H["14 Exhibits (300 DPI Vector)<br/><b>Lancet / NEJM Standards</b>"]
    end

    style A fill:#0D1117,stroke:#30363D,color:#C9D1D9
    style B fill:#0D1117,stroke:#30363D,color:#C9D1D9
    style C fill:#0D2744,stroke:#2997FF,color:#FFFFFF,stroke-width:2px
    style D fill:#0D1117,stroke:#30363D,color:#C9D1D9
    style E fill:#0D1117,stroke:#30363D,color:#C9D1D9
    style F fill:#0D1117,stroke:#30363D,color:#C9D1D9
    style G fill:#0D2744,stroke:#2997FF,color:#FFFFFF,stroke-width:2px
    style H fill:#1C3D24,stroke:#3FB950,color:#FFFFFF,stroke-width:2px
```

---

## 🏆 Flagship Landmark Repository

### 🩺 [`nma-nsclc-evidence-synthesis`](https://github.com/Mohamed101010101/nma-nsclc-evidence-synthesis)
> **Publication-Grade Frequentist Network Meta-Analysis Engine for Advanced Oncology**

An enterprise-grade, fully reproducible research engine evaluating first-line systemic immunotherapies and chemotherapies in advanced non-small cell lung cancer (NSCLC):

- 📊 **Curated Clinical Base:** 24 landmark randomized controlled trials comprising **15,753 patients**.
- ⚙️ **Modular Execution:** 12 sequential mathematical engines (`01_fit_nma_model.R` through `12_mcid_analysis.R`).
- 🔬 **Sensitivity & Rigor:** Full leave-one-out cross-validation, design-by-treatment tests, and 10,000-scenario Monte Carlo simulations.
- 🎨 **Visual Portfolio:** 14 high-resolution, 300-DPI vector exhibits adhering strictly to *Lancet*, *NEJM*, and *JAMA Oncology* guidelines.
- 📜 **Reproducibility Guarantee:** Curated data tables, exact session lockfile parameters, and complete open-source code under the MIT License.

```
📁 nma-nsclc-evidence-synthesis/
├── 📂 data/                 # Systematic extraction matrices (OS, PFS, Grade 3-5 Toxicities)
├── 📂 scripts/analyses/     # 12 sequential mathematical engines (Modular R pipeline)
├── 📂 outputs/figures/      # 14 publication-grade 300 DPI exhibits (Vector PDF & PNG)
├── 📂 report/               # Publication-grade R Markdown analytical monograph
├── 📄 CITATION.cff         # Machine-readable scholarly citation metadata
├── 📄 REPRODUCIBILITY.md   # Complete computational environment audit & execution log
└── 📄 LICENSE              # Open-source MIT License
```

### 📊 Landmark Empirical Exhibits (300 DPI)

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/Mohamed101010101/nma-nsclc-evidence-synthesis#figure-01--evidence-network-geometry">
        <img src="https://raw.githubusercontent.com/Mohamed101010101/nma-nsclc-evidence-synthesis/main/outputs/figures/01_network_geometry.png" width="100%" alt="Figure 01: Star-Loop Network Geometry" />
      </a>
      <br/>
      <sub><b>Figure 01:</b> Multi-arm star-loop network geometry (24 RCTs · 15,753 Patients)</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/Mohamed101010101/nma-nsclc-evidence-synthesis#figure-11--benefit-risk-trade-off-plane">
        <img src="https://raw.githubusercontent.com/Mohamed101010101/nma-nsclc-evidence-synthesis/main/outputs/figures/11_benefit_risk_tradeoff.png" width="100%" alt="Figure 11: Benefit-Risk Trade-Off" />
      </a>
      <br/>
      <sub><b>Figure 11:</b> Bivariate benefit-risk plane (Overall Survival HR vs Grade 3–5 Toxicity OR)</sub>
    </td>
  </tr>
</table>

---

## 📐 Methodological Matrix & Core Competencies

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🧬 Evidence Synthesis</h4>
      <ul>
        <li>Network Meta-Analysis (NMA)</li>
        <li>Pairwise Meta-Analysis (DL, REML)</li>
        <li>Component Network Meta-Analysis</li>
        <li>Local &amp; Global Inconsistency Audits</li>
        <li>Node-Splitting &amp; Back-Calculation</li>
        <li>Design-by-Treatment Interaction</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>📊 Decision Analytics</h4>
      <ul>
        <li>Treatment Ranking (P-Scores, SUCRA)</li>
        <li>Probabilistic Monte Carlo Simulations</li>
        <li>ASCO / ESMO MCID Benefit Benchmarks</li>
        <li>Bivariate Benefit-Risk Trade-Off Models</li>
        <li>Leave-One-Out Robustness Audits</li>
        <li>Meta-Regression &amp; Subgroup Analysis</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>💻 Computational Engineering</h4>
      <ul>
        <li><strong>Core Ecosystem:</strong> <code>R</code> (<code>netmeta</code>, <code>meta</code>, <code>tidyverse</code>)</li>
        <li><strong>Reproducibility:</strong> Quarto, R Markdown, <code>renv</code></li>
        <li><strong>Publication Engine:</strong> 300 DPI <code>ggplot2</code>, Grid</li>
        <li><strong>Version Control:</strong> Git, GitHub Workflows</li>
        <li><strong>Cross-Disciplinary:</strong> Python, LaTeX, BibTeX</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🎯 Global Methodological Compliance

<div align="center">

| International Framework | Computational Implementation Scope |
| :--- | :--- |
| **PRISMA-NMA (2015)** | Complete 32-item checklist alignment across network geometry, bias, and reporting |
| **Cochrane Handbook v6** | Multi-arm trial correlation adjustment and variance-covariance preservation |
| **GRADE Working Group** | Systematic assessment of transitivity, direct/indirect coherence, and certainty |
| **ASCO / ESMO Frameworks** | Quantitative evaluation of Minimal Clinically Important Difference (MCID) thresholds |

</div>

---

## 🔬 Advanced Biostatistical Tooling & Methodological Rigor

In high-impact oncology research, the validity of clinical evidence synthesis hinges on rigorous handling of trial heterogeneity, selection mechanisms, and small-sample constraints:

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🔍 Bias Diagnostics &amp; Selection Models</h4>
      <ul>
        <li><strong>Publication Bias Modeling:</strong> Copas selection models for evaluating missing study mechanisms under non-ignorable selection.</li>
        <li><strong>Small-Study Effects:</strong> Contour-enhanced funnel plots, Egger linear regression, and Peters test for binary outcomes.</li>
        <li><strong>Risk of Bias Architecture:</strong> Cochrane RoB 2.0 (for randomized trials) and ROBINS-I (for observational cohorts).</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚖️ Sparse Data &amp; Survival Synthesis</h4>
      <ul>
        <li><strong>Zero-Event Corrections:</strong> Penalized likelihood methods (Firth logistic regression) and exact beta-binomial models.</li>
        <li><strong>Inconsistency Deconstruction:</strong> NetHeat spectral leverage decomposition and node-splitting back-calculation.</li>
        <li><strong>Certainty of Evidence:</strong> GRADE working group profiles and CINeMA (Confidence in Network Meta-Analysis) framework.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🔭 Strategic Research Horizons & Methodological Focus

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🎯 Precision Immuno-Oncology</h4>
      <p>Deciphering multi-agent checkpoint blockade synergy (anti-PD-1/PD-L1 + anti-CTLA-4) stratified by quantitative biomarker thresholds (PD-L1 TPS/CPS expression, tumor mutational burden, driver alterations).</p>
    </td>
    <td width="33%" valign="top">
      <h4>⚖️ Sparse Data Synthesis</h4>
      <p>Formulating exact beta-binomial likelihoods, Firth penalized regressions, and Copas non-ignorable selection models to counter extreme sparsity, zero-event arms, and selective outcome reporting.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🩺 Decision Analytics &amp; EVPI</h4>
      <p>Bridging NMA effect size distributions into decision-analytic Markov state-transition models, ASCO/ESMO MCID frontiers, and Expected Value of Perfect Information (EVPI) health economics frameworks.</p>
    </td>
  </tr>
</table>

---

## 📊 Analytics & Activity

<div align="center">
  <img src="./stats.svg" width="100%" alt="Research Analytics & Computational Metrics" />
</div>

---

## 👨‍🔬 Principal Investigator & Research Inquiries

<div align="center">

<p align="center">
  <a href="https://www.mti.edu.eg/" target="_blank">
    <img src="./mti_logo.png" width="220" alt="Modern University for Technology and Information (MTI)" style="background: rgba(255,255,255,0.95); padding: 8px 14px; border-radius: 10px; margin-bottom: 12px;" />
  </a>
</p>

### **Mohamed Said Mohamed Diab** *(Lead Investigator)*
**Faculty of Medicine, Modern University for Technology and Information (MTI), Cairo, Egypt**

<p align="center">
  <a href="https://mohamed101010101.github.io/cv.html">
    <img src="https://img.shields.io/badge/Academic%20CV-Download%20PDF-0071E3?style=flat-square&logo=academia&logoColor=white" alt="Academic CV" />
  </a>
  <a href="https://orcid.org/0009-0003-3143-387X">
    <img src="https://img.shields.io/badge/ORCID-0009--0003--3143--387X-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" />
  </a>
  <a href="https://scholar.google.com/citations?user=_tJ3MkYAAAAJ">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar" />
  </a>
  <a href="https://www.linkedin.com/search/results/all/?keywords=Mohamed%20Said%20Mohamed%20Diab">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.researchgate.net/search/researcher?q=Mohamed%20Said%20Mohamed%20Diab">
    <img src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=flat-square&logo=researchgate&logoColor=white" alt="ResearchGate" />
  </a>
  <a href="mailto:Mohamed.98478@Medicine.mti.edu.eg">
    <img src="https://img.shields.io/badge/Institutional%20Email-Mohamed.98478%40Medicine.mti.edu.eg-0071E3?style=flat-square&logo=gmail&logoColor=white" alt="Institutional Email" />
  </a>
  <a href="https://mohamed101010101.github.io/">
    <img src="https://img.shields.io/badge/Portfolio%20Website-Live-black?style=flat-square&logo=safari&logoColor=2997FF" alt="Portfolio Website" />
  </a>
</p>

<p align="center">
  <b>MTI Evidence Synthesis Working Group:</b><br/>
  <sub><b>Mohamed Said Mohamed Diab</b> (Lead) &middot; <b>Badr Essam Ali</b> &middot; <b>Ali Hassan Hafez</b> &middot; <b>Omar Gomaa Mousa</b> &middot; <b>Mahmoud Hussein Fathy</b></sub>
</p>

</div>

> **🤝 Research Collaboration & Methodological Advisory**  
> Open to collaborative systematic reviews, Bayesian/Frequentist network meta-analyses, and quantitative decision-analytic modeling for high-impact oncology research and clinical practice guideline synthesis.

<br/>

<div align="center">
<sub>Crafted with Cupertino minimalism · Powered by R and Open Science</sub>
</div>
