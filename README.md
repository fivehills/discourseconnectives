# The Ebb and Flow of Discourse Connectives: Data Repository

This repository contains the datasets accompanying the paper:  
**“The Ebb and Flow of Discourse Connectives: Cognitive Decline or Stylistic Change?”**

The project investigates historical changes in the usage of English discourse connectives (DCs) from 1820 to 2010, drawing on large-scale diachronic corpora including the **Corpus of Historical American English (COHA)** and the **Google Books Ngram Corpus**. It also integrates information from the **Penn Discourse Treebank 3.0 (PDTB3)** to analyze discourse relations and implicitness.

---

## 📘 Repository Structure

| File | Description |
|------|--------------|
| **word_pdtb_fre_all1.csv** | Contains discourse connective senses, frequency weights, and decade-level frequencies (1820–2010). |
| **explicit_data2.csv** | List of explicit discourse connectives and their frequencies derived from PDTB3.0. |
| **implicitness.csv** | Data on the proportion of implicit discourse relations from PDTB3.0. |
| **eng_dat-comparison.csv**, **eng_dat-contingency.csv**, **eng_dat-expansion.csv**, **eng_dat-temporary.csv** | Data from **Google Books Ngram Corpus**, representing four major semantic classes of discourse connectives. |
| **en_gg_comp.csv**, **en_gg_ctg.csv**, **en_gg_exp.csv**, **en_gg_tem.csv** | Data from **COHA**, representing the same four classes (comparison, contingency, expansion, and temporal). |
| **so_coded.csv**, **well_coded.csv** | Annotated data on the discourse markers *so* and *well*, focusing on their pragmatic and stylistic functions. |
| **extra_data.csv** | Supplementary data for cross-validation tests and robustness checks. |

---

## 🧩 Data Overview

- **Time range:** 1820–2010  
- **Main corpora:** COHA, Google Books Ngram  
- **Annotation source:** PDTB3.0  
- **Analysis scope:** Explicit and implicit connectives, semantic classes, stylistic shifts (formal, neutral, informal)

---

## 🔍 Research Context

The dataset supports analyses of diachronic linguistic trends, particularly:
- The long-term decline of **formal** and **neutral** discourse connectives  
- The rise of **informal** and conversational connectives  
- The relationship between stylistic change and cognitive factors in language evolution

This work contributes to understanding **colloquialization**—the gradual shift of written English toward more speech-like, informal styles.

---

## 🧩 Main Findings

This study investigates diachronic changes in the use of discourse connectives (DCs) across **five languages** — *Chinese, English, French, German,* and *Spanish* — using large-scale historical corpora.

### 🔹 Key Observations

* **Cross-linguistic decline:**
  DC frequencies in English, French, German, and Spanish show a **long-term decline** from the 19th to the 20th century.

* **Post-1980 resurgence:**
  After the 1980s, especially after 2000, all five languages exhibit a **moderate increase** in DC use, suggesting a stylistic recovery or shift.

* **Stylistic alignment:**
  These historical trends closely **align with other stylistic indicators** (e.g., pronoun use, lexical diversity), supporting a coherent trajectory of register evolution rather than random fluctuation.

* **No evidence of cognitive decline:**
  The decrease in DCs **does not indicate weakened rationality** or logical reasoning but reflects broader communicative and stylistic changes.

* **Colloquialization as the main driver:**
  The shifts are primarily driven by **colloquialization** — the process by which written language becomes more speech-like, influenced by literacy expansion, democratization of communication, and social modernization.

### 🔹 Broader Implications

* These findings demonstrate how **social and cultural dynamics** shape linguistic change over time.
* The study provides a **quantitative, culturomic framework** for tracing historical links between language, cognition, and socio-cultural evolution.

---

## 📊 COHA-Specific Findings

Analysis of yearly *z*-score frequencies of discourse connectives (DCs) in the **Corpus of Historical American English (COHA)** reveals a clear stylistic shift over the past two centuries:

* **Formal DCs:** Declined sharply from 106.40 (1820) to 37.86 (2010), a **64.4% decrease**
* **Neutral DCs:** Decreased moderately from 715.77 (1820) to 583.73 (2010), an **18.5% decrease**
* **Informal DCs:** Increased from 854.80 (1820) to 1016.34 (2010), an **18.9% rise**

These trends parallel the broader cross-linguistic results: formal and neutral connectives have become less frequent, while informal ones have gained prominence. The findings exemplify the **colloquialization of written English**, a process reflecting stylistic simplification and social modernization rather than any decline in cognitive or rational capacities.


---

## 🧠 Citation

If you use this dataset, please cite:

> Sun, K. and Rong Wang (2025). *The Ebb and Flow of Discourse Connectives: Cognitive Decline or Stylistic Change?*  
> [Under Review / Preprint link: https://osf.io/preprints/psyarxiv/98psm_v1]

---

## ⚙️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/fivehills/discourseconnectives.git
