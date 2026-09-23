<div align="center">

# Awais Abdul Khaliq

**PhD candidate in Computer Science**
Università degli Studi di Milano · Dipartimento di Informatica "Giovanni Degli Antoni" · ISLab

<br>

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--3439--6256-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-3439-6256)
[![Email](https://img.shields.io/badge/awais.abdul@unimi.it-0A66C2?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:awais.abdul@unimi.it)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/awais-abdul-khaliq-a8ab1972/)

<br>

### Legal NLP · Graph neural networks · Evaluation methodology

</div>

<br>

---

## The question I work on

Legal text is **defeasible**. A rule states an obligation, a later clause carves out an
exception, a superior authority overrides both. Encoding that structure explicitly, as
typed operators inside a graph neural network, ought to help a model read legal documents.

My doctoral work asks whether it actually does, and runs into a harder question on the way:

> When you add structure to a neural model and it performs better, how do you show the
> **structure** is doing the work, rather than the **parameters** that came with it?

The answer to the first question is mostly no, and the conditions under which it is yes turn
out to be narrow and measurable. The method built to answer the second is the part I think
travels beyond law.

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

The result is two-sided — strong on ranking, weak on decisions — and the
README shows both sides.

![lang](https://img.shields.io/github/languages/top/oziofficial5/Aske?style=flat-square&color=2f6f4e)
![licence](https://img.shields.io/github/license/oziofficial5/Aske?style=flat-square&color=2f6f4e)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Jusdef](https://github.com/oziofficial5/Jusdef) &nbsp;<sub>archived</sub>

The original workshop implementation, kept for provenance.

The evaluation bug it contained is documented in full rather than quietly
dropped.

![lang](https://img.shields.io/github/languages/top/oziofficial5/Jusdef?style=flat-square&color=868e96)
![status](https://img.shields.io/badge/status-superseded-868e96?style=flat-square)

</td>
<td width="50%" valign="top">

### Released resources

A 3,000-sentence operator-annotated EUR-Lex corpus, its annotation guidelines,
the inter-annotator validation files, and a neural operator detector that
transfers to contract text without retraining.

All in **jusdefv2**, all usable independently of any verdict on the
architecture.

</td>
</tr>
</table>

<br>

---

## Publications

<table>
<tr>
<td width="110" align="center" valign="top"><br><b>2026</b><br><sub>Springer</sub></td>
<td>

**JusDef: Defeasible Message Passing for Exception-Aware Legal Document Classification**
Khaliq, Montanelli, Dalianis & Naqvi
*ANNPR 2026 — 12th IAPR TC3 Workshop, LNAI*
[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--3--032--39028--8__6-blue?style=flat-square)](https://doi.org/10.1007/978-3-032-39028-8_6)

</td>
</tr>
<tr>
<td width="110" align="center" valign="top"><br><b>2026</b><br><sub>Elsevier</sub></td>
<td>

**Evaluating Knowledge-Based Approaches for Legal Text Analysis: A Benchmark Study**
Khaliq, Riva & Montanelli
*Computer Law & Security Review* **61**:106279
[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.clsr.2026.106279-blue?style=flat-square)](https://doi.org/10.1016/j.clsr.2026.106279)

</td>
</tr>
<tr>
<td width="110" align="center" valign="top"><br><b>2025</b><br><sub>Springer</sub></td>
<td>

**Language Models for Legal NLP: A Literature Review**
Khaliq & Montanelli
*CAiSE 2025 Workshops, LNBIP 556, 326–337*
[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--3--031--94931--9__27-blue?style=flat-square)](https://doi.org/10.1007/978-3-031-94931-9_27)

</td>
</tr>
<tr>
<td width="110" align="center" valign="top"><br><b>—</b><br><sub>under review</sub></td>
<td>

**When Does Defeasibility-Aware Neural Aggregation Help Legal Text Classification?
Separating Mechanism from Added Capacity with a Permutation Control**
*Artificial Intelligence and Law*
![Status](https://img.shields.io/badge/status-under%20review-lightgrey?style=flat-square)

</td>
</tr>
</table>

<br>

---

## On negative results

Two of the repositories above exist partly to record things that did not work: an
architecture that finished nine macro-F1 points behind the baseline it was built to extend,
and a threshold-tuning bug in my own published evaluation.

Both are written up in the code rather than left for someone else to find. If you arrive at
one of these repositories from a paper, the README tells you the current status of the
numbers in it.

<br>

---

## Built with

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

</div>

<br>

<div align="center">
<sub>Legal NLP · graph neural networks · defeasible reasoning · evaluation methodology · knowledge extraction</sub>
</div>
