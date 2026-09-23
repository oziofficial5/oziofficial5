## Awais Abdul Khaliq

PhD candidate in Computer Science at the **Università degli Studi di Milano**,
Dipartimento di Informatica "Giovanni Degli Antoni", in the ISLab group.

I work on **legal NLP**, and specifically on a question that turns out to be
harder than it sounds: when you add structure to a neural model and it performs
better, how do you show the structure is doing the work rather than the extra
parameters that came with it?

ORCID [0000-0002-3439-6256](https://orcid.org/0000-0002-3439-6256)

---

### What I am working on

Legal text is *defeasible*. A rule states an obligation, a later clause carves out
an exception, a superior authority overrides both. My doctoral work asks whether
encoding that structure explicitly, as typed operators in a graph neural network,
helps a model classify legal documents.

The honest answer is: mostly no, and the conditions under which it is yes are
narrow and measurable. Getting to that answer meant building a method for telling
a real structural effect from added model capacity, which is the part I think
generalises beyond law.

| | |
|---|---|
| **[jusdefv2](https://github.com/oziofficial5/jusdefv2)** | Defeasibility-aware graph neural networks, a three-arm permutation control for deciding whether a structural prior does any work, and the released corpus and per-seed logs behind every reported number |
| **[Aske](https://github.com/oziofficial5/Aske)** | Benchmark of a knowledge-based legal extraction pipeline against fine-tuned transformers on LexGLUE |
| **[Jusdef](https://github.com/oziofficial5/Jusdef)** | The original workshop implementation, archived, with the evaluation bug it contained documented in full |

---

### Publications

- **JusDef: Defeasible Message Passing for Exception-Aware Legal Document Classification.**
  Khaliq, Montanelli, Dalianis & Naqvi. ANNPR 2026, 12th IAPR TC3 Workshop.
  Springer LNAI.
  [doi:10.1007/978-3-032-39028-8_6](https://doi.org/10.1007/978-3-032-39028-8_6)

- **Evaluating Knowledge-Based Approaches for Legal Text Analysis: A Benchmark Study.**
  Khaliq, Riva & Montanelli. *Computer Law & Security Review* 61:106279, 2026.
  Elsevier.
  [doi:10.1016/j.clsr.2026.106279](https://doi.org/10.1016/j.clsr.2026.106279)

- **Language Models for Legal NLP: A Literature Review.**
  Khaliq & Montanelli. CAiSE 2025 Workshops, Springer LNBIP 556, 326–337.
  [doi:10.1007/978-3-031-94931-9_27](https://doi.org/10.1007/978-3-031-94931-9_27)

- **When Does Defeasibility-Aware Neural Aggregation Help Legal Text
  Classification? Separating Mechanism from Added Capacity with a Permutation
  Control.** *Artificial Intelligence and Law.* Under review.

---

### On negative results

Two of the repositories above exist partly to record things that did not work: an
architecture that fell behind the baseline it was built to extend, and an
evaluation bug in my own published paper. Both are documented in the code rather
than left for someone else to find.

If you arrive at one of these repositories from a paper, the README will tell you
the current status of the numbers in it.

---

### Interests

Legal NLP · graph neural networks · defeasible reasoning · evaluation
methodology · knowledge extraction
