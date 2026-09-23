<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Awais Abdul Khaliq — PhD candidate in Computer Science, Università degli Studi di Milano" width="100%">
</picture>

<br><br>

Dipartimento di Informatica "Giovanni Degli Antoni" · ISLab

<br>

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--3439--6256-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-3439-6256)
[![Email](https://img.shields.io/badge/awais.abdul@unimi.it-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:awais.abdul@unimi.it)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/awais-abdul-khaliq-a8ab1972/)

<br>

**Legal NLP** &nbsp;·&nbsp; **Graph neural networks** &nbsp;·&nbsp; **Retrieval-augmented generation** &nbsp;·&nbsp; **Evaluation methodology**

</div>

<br>

---

## The question I work on

Legal text is **defeasible**. A rule states an obligation, a later clause carves out an
exception, a superior authority overrides both. Encoding that structure explicitly, as typed
operators inside a graph neural network, ought to help a model read legal documents.

My doctoral work asks whether it actually does, and runs into a sharper question on the way:

> When you add structure to a neural model and it performs better, how do you show the
> **structure** is doing the work, rather than the **capacity** that came with it?

The answer to the first is conditional, and the conditions turn out to be narrow and
measurable. The method built to answer the second is the part that travels beyond law: a
permutation control that retrains an identical architecture on true, shuffled and removed
structure, validated across eighteen graph benchmarks.

<br>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oziofficial5/oziofficial5/refs/heads/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/oziofficial5/oziofficial5/refs/heads/output/github-snake-light.svg" alt="Contribution graph" width="100%">
</picture>

</div>

<br>

---

## Repositories

<table>
<tr>
<td width="50%" valign="top">

### [jusdefv2](https://github.com/oziofficial5/jusdefv2)

Defeasibility-aware graph neural networks for legal text, and a three-arm
permutation control for deciding whether a structural prior does any work.

Ships the annotated corpus, the operator detector, and the per-seed logs
behind every reported number.

![lang](https://img.shields.io/github/languages/top/oziofficial5/jusdefv2?style=flat-square&color=4c6ef5)
![licence](https://img.shields.io/github/license/oziofficial5/jusdefv2?style=flat-square&color=4c6ef5)

</td>
<td width="50%" valign="top">

### [Aske](https://github.com/oziofficial5/Aske)

Benchmark of a knowledge-based legal extraction pipeline against fine-tuned
transformers across the LexGLUE suite.

The result is two-sided — strong on ranking, weaker on decisions — and the
README shows both sides.

![lang](https://img.shields.io/github/languages/top/oziofficial5/Aske?style=flat-square&color=2f6f4e)
![licence](https://img.shields.io/github/license/oziofficial5/Aske?style=flat-square&color=2f6f4e)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Jusdef](https://github.com/oziofficial5/Jusdef) &nbsp;<sub>archived</sub>

The original workshop implementation, kept for provenance.

Superseded by **jusdefv2**, with the status of the numbers it reports
documented in the README.

![lang](https://img.shields.io/github/languages/top/oziofficial5/Jusdef?style=flat-square&color=868e96)
![status](https://img.shields.io/badge/status-superseded-868e96?style=flat-square)

</td>
<td width="50%" valign="top">

### Released resources

A **3,000-sentence** operator-annotated EUR-Lex corpus, its annotation
guidelines, the inter-annotator validation files, and a neural operator
detector that transfers to contract text without retraining.

All inside **jusdefv2**, all usable independently of any verdict on the
architecture.

</td>
</tr>
</table>

<br>

---

## Publications

### Legal NLP

<table>
<tr><td width="96" align="center" valign="middle"><b>2026</b><br><sub>Elsevier</sub></td><td>

**Evaluating Knowledge-Based Approaches for Legal Text Analysis: A Benchmark Study**
Khaliq, Riva & Montanelli · *Computer Law & Security Review* **61**:106279
[![DOI](https://img.shields.io/badge/10.1016%2Fj.clsr.2026.106279-blue?style=flat-square&label=DOI)](https://doi.org/10.1016/j.clsr.2026.106279)

</td></tr>
<tr><td align="center" valign="middle"><b>2026</b><br><sub>Springer</sub></td><td>

**JusDef: Defeasible Message Passing for Exception-Aware Legal Document Classification**
Khaliq, Montanelli, Dalianis & Naqvi · *ANNPR 2026, 12th IAPR TC3 Workshop* · LNAI
[![DOI](https://img.shields.io/badge/10.1007%2F978--3--032--39028--8__6-blue?style=flat-square&label=DOI)](https://doi.org/10.1007/978-3-032-39028-8_6)

</td></tr>
<tr><td align="center" valign="middle"><b>2025</b><br><sub>Springer</sub></td><td>

**Language Models for Legal NLP: A Literature Review**
Khaliq & Montanelli · *CAiSE 2025 Workshops* · LNBIP **556**, 326–337
[![DOI](https://img.shields.io/badge/10.1007%2F978--3--031--94931--9__27-blue?style=flat-square&label=DOI)](https://doi.org/10.1007/978-3-031-94931-9_27)

</td></tr>
<tr><td align="center" valign="middle"><b>—</b><br><sub>Springer</sub></td><td>

**When Does Defeasibility-Aware Neural Aggregation Help Legal Text Classification?
Separating Mechanism from Added Capacity with a Permutation Control**
Khaliq & Montanelli · *Artificial Intelligence and Law*
![status](https://img.shields.io/badge/under%20review-lightgrey?style=flat-square&label=status)

</td></tr>
</table>

### Computer vision and security

<table>
<tr><td width="96" align="center" valign="middle"><b>2025</b><br><sub>Springer</sub></td><td>

**Multimodal Deepfake Detection with Large Vision-Language Models: The State of the Art**
*ICIAP 2025*, 364–375 — survey of CLIP, BLIP2 and LLaVA for cross-modal
inconsistency detection

</td></tr>
<tr><td align="center" valign="middle"><b>2022</b><br><sub>IEEE</sub></td><td>

**A Secure and Privacy Preserved Parking Recommender System Using Elliptic Curve
Cryptography and Local Differential Privacy**
Khaliq, Anjum, Ajmal, Webber, Mehbodniya & Khan · *IEEE Access* **10**:56410–56426
[![IEEE](https://img.shields.io/badge/IEEE%20Xplore-00629B?style=flat-square&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/9775988/)

</td></tr>
<tr><td align="center" valign="middle"><b>2021</b><br><sub>IEEE</sub></td><td>

**Last Line of Defense: Reliability Through Inducing Cyber Threat Hunting With Deception
in SCADA Networks**
Ajmal, Alam, Khaliq, Khan, Qadir & Mahmud · *IEEE Access* **9**:126789–126800
[![IEEE](https://img.shields.io/badge/IEEE%20Xplore-00629B?style=flat-square&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/9531651/)

</td></tr>
</table>

<br>

---

## Also worked on

Research stays outside the thesis, both applied retrieval systems:

- **Clinical Graph RAG** — ontology-grounded multi-hop retrieval for clinical question
  answering over electronic health records, built at DSV, Stockholm University. Knowledge
  graph constructed from MIMIC and grounded in UMLS, SNOMED CT, ICD and RxNorm, with a
  hybrid graph-traversal and dense-retrieval layer and a GDPR-compliant de-identification
  pipeline.
- **CSIL-Assistant** — hybrid RAG assistant over a corporate document corpus, combining
  FAISS dense retrieval with BM25 and keyword indexing, with LLM-based query decomposition
  and adaptive retrieval depth.

<br>

---

<div align="center">

### Built with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)


<sub>Legal NLP · graph neural networks · defeasible reasoning · retrieval-augmented generation · evaluation methodology · knowledge extraction</sub>

</div>
