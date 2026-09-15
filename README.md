<picture>
  <source media="(prefers-color-scheme: dark)" srcset="header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="header.svg">
  <img src="header.svg" alt="Lysander Elgar. Research and software. Cells, networks, code." width="100%">
</picture>

<p align="center">
  <a href="#user-content-research">Research</a> &nbsp; / &nbsp;
  <a href="#user-content-projects">Projects</a> &nbsp; / &nbsp;
  <a href="#user-content-approach">How I work</a>
</p>

## About

I'm **Lysander**, an undergraduate researcher at **Washington University in St. Louis**. I write code to study cells, immune networks, and the biology of pain. Outside the lab, I build applications and test ideas at hackathons.

Most of my research code lives in private repositories. Below is a look at the questions I work on, my part in the analysis, and the projects you can explore here.

<br>

<a id="research"></a>

## 01 / Research

### Cells in context

**CosMx-mDRG spatial transcriptomics · Chamessian Lab**

I analyze mouse dorsal root ganglia, studying cell identity and spatial organization in sensory tissue. My work covers atlas-based annotation, unsupervised clustering, spatial statistics that account for tissue sections, and reproducible figures.

> **34,540 cells · 37 L4 dorsal root ganglia · 20 mice**

<details>
<summary>Methods and scope</summary>

I build workflows in R and Seurat, check cell-type annotations, validate clustering, and compare spatial patterns across tissue sections. Research code and source data are private.

</details>

### Immune networks before transplant

**T-cell receptor topology · Borcherding Lab**

I will join a manuscript revision studying whether pre-transplant TCR-beta sequence-similarity networks predict kidney allograft outcomes independently of HLA mismatch. I will rerun and stress-test the analysis, incorporate an external cohort, and help revise the figures and manuscript.

[Read the earlier manuscript version ↗](https://pmc.ncbi.nlm.nih.gov/articles/PMC13174407/)

<details>
<summary>Methods and scope</summary>

The project combines immune repertoire analysis, network science, and predictive modeling. My work also includes evaluating statistical and machine-learning extensions. Research code and patient-level data are private.

</details>

<br>

<a id="projects"></a>

## 02 / Projects

### [Tracing pain-associated variants](https://github.com/1ysander/gwas-snp-analysis)

An exploratory Python analysis comparing **107 pain-associated GWAS variants** with **222 cell-type regulatory-element sets**. It maps variants, calculates chromosomal density, and ranks cell types by overlap with candidate regulatory regions.

**A question behind the code:** which cell types are worth a closer look?

[Explore the analysis ↗](https://github.com/1ysander/gwas-snp-analysis)

### [Argus](https://github.com/cifyr/argus)

A team-built hackathon prototype that brings emergency messages, location, medical context, and dispatch contacts into a local macOS console. It combines Messages, Find My, Ollama, SQLite, and OpenStreetMap to support a human operator.

**Design constraint:** the operator makes the call. Argus does not autonomously contact 911.

[Explore the prototype ↗](https://github.com/cifyr/argus)

### Sepsis Early Warning

A four-person hackathon prototype pairing a clinical dashboard with FastAPI, a random forest model, and Gemini-generated explanations for nurses.

**Demo scope:** the model was trained on synthetic patient trajectories. The hosted dashboard uses fixture data; model and agent components run locally.

<details>
<summary>Also on my workbench</summary>

#### [Conversation Capture](https://github.com/1ysander/conversation-capture)

An Apple Watch and iPhone app for recording, transcribing, summarizing, and asking questions about conversations. The architecture is defined; implementation is in progress. Built around SwiftUI, WatchConnectivity, and Supabase.

#### [Projectly](https://github.com/1ysander/projectly)

A shipping-workflow prototype built with TypeScript, React, Vite, and Supabase.

</details>

<br>

<a id="approach"></a>

## 03 / How I work

I care about being able to trace a result back to its inputs, check the assumptions, and rerun the analysis. I try to make uncertainty visible and keep a project's claims close to what its code and data can support.

**Research:** R, Seurat, ggplot2, Python, scikit-learn<br>
**Applications:** TypeScript, React, FastAPI, SwiftUI, Supabase<br>
**Across both:** Git, validation, reproducible workflows

<br>

---

<p align="center">
  <sub>Lysander Elgar · Washington University in St. Louis</sub><br>
  <a href="#">Back to top ↑</a>
</p>
