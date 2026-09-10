<p align="center">
  <img src="header.svg" alt="Lysander Elgar" width="100%"/>
</p>

I'm an undergraduate researcher at **Washington University in St. Louis** building
computational tools for spatial biology, genomics, and machine learning. I care about
reproducible analysis, honest uncertainty, and results that other people can inspect.

### Current research

#### CosMx spatial transcriptomics of mouse dorsal root ganglia

I contribute to a Chamessian Lab study of **34,540 cells from 37 L4 ganglia across 20
mice**. My work includes R/Seurat pipelines for reference-based cell-type annotation,
unsupervised clustering, section-aware spatial-neighborhood analysis, validation, and
reproducible figures. The research repository is lab-managed and is not currently public.

#### TCR network topology and kidney allograft rejection

I joined an ongoing Borcherding Lab manuscript project studying whether pre-transplant
TCR-beta sequence-similarity network structure can predict kidney allograft outcomes
independently of HLA mismatch. My role begins with the current revision: reproducibly
rerunning and stress-testing the computational analysis, incorporating an additional
external cohort, evaluating statistical and machine-learning extensions, and helping
revise the figures and manuscript. The code and patient-level data are private.
[Read the earlier manuscript version](https://pmc.ncbi.nlm.nih.gov/articles/PMC13174407/)

### Independent analysis

#### Pain-associated GWAS variants x cell-type regulatory elements

An exploratory Python pipeline comparing **107 cataloged pain-associated SNPs** with
**222 cell-type cCRE peak sets**. It produces interval-overlap and chromosome-density
summaries; it is an exploratory prioritization exercise, not causal fine-mapping.
[View the project](https://github.com/1ysander/gwas-snp-analysis)

### Hackathon work

#### [Argus — emergency intake and dispatch-support prototype](https://github.com/cifyr/argus)

A team hackathon project built as a local macOS console. It combines Messages, Find My,
Ollama, SQLite, and OpenStreetMap to surface emergency messages, medical context,
location, and dispatch contact information for a human operator. Argus assists the
operator; it does not autonomously contact 911.

#### Sepsis Early Warning

A four-person prototype combining a clinical dashboard, two FastAPI services, a
RandomForest trained on synthetic patient trajectories, and Gemini-generated
nurse-facing explanations. The hosted browser demo uses fixture data; the local model
and agent path is not yet wired into the hosted frontend. The team repository is not
currently public.

### Selected builds

- **[Conversation Capture](https://github.com/1ysander/conversation-capture)** — product
  architecture and implementation blueprint for an Apple Watch + iPhone transcription,
  summarization, and semantic Q&A system; implementation is in progress.
- **[Projectly](https://github.com/1ysander/projectly)** — shipping-workflow prototype
  built with TypeScript, React, Vite, and Supabase.

### Tools I use

`R` · `Seurat` · `ggplot2` · `Python` · `scikit-learn` · `TypeScript` · `React` ·
`FastAPI` · `SwiftUI` · `Supabase` · `Git`
