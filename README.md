# Weatherfluencers: Trust and Collective Sensemaking in Severe Weather Livestreams

**Julie A. Vera** | Supplementary Dissertation Materials | University of Washington, Human Centered Design & Engineering | 2026

This repository contains analysis code and supporting data for Studies 1 and 3 of the dissertation, along with a supplementary analysis of real-time X/Twitter discourse surrounding the Whitman, Nebraska tornado (June 2024). All materials correspond to analyses described in the dissertation text and appendices.

---

## Study 1: Audience Credibility Evaluation of Weather Communicators

Study 1 examined how audiences evaluate broadcast meteorologists and YouTube weatherfluencers across six credibility dimensions (accuracy, trustworthiness, objectivity, credibility, coverage legitimacy, and presenter legitimacy) and three safety-relevant ranking criteria.

**Files:**
- `Study_1_Survey_Analysis_Notebook.ipynb` — Analysis notebook for the Study 1 survey data. Includes descriptive statistics and Wilcoxon signed-rank tests, across credibility dimensions and ranking criteria.
- `Qualtrics Survey Data - Trust-Credibility-Legitimacy` — Raw survey data exported from Qualtrics. Responses were cleaned manually: fraudulent responses identified through MTurk quality flags and within-survey attention checks were excluded prior to analysis. No other preprocessing was applied.

---

## Study 2: Production-Level Analysis of Weatherfluencer Interpretive Practices

Study 2 used focused content analysis of archived severe weather livestream segments during Particularly Dangerous Situation (PDS) warning windows. Analysis was conducted using structured observation notes rather than computational methods. The PDS warning capture template and full codebook for Study 2 are included in the dissertation as Appendix C.

---

## Study 3: Interactional Trust Work in Severe Weather Livestream Chat

Study 3 examined how trust operates as interactional work in severe weather livestream chat during tornado outbreaks, drawing on a corpus of over 1.1 million archived comments across 34 individual streams.

**Files:**
- `Study 3 - Stitch All Event Chat Files Together.ipynb` — Preprocessing notebook for assembling raw YouTube Live Chat exports into a unified corpus across outbreak events.
- `Study 3 - Conversation Extraction.ipynb` — Notebook for reconstructing viewer-to-viewer micro-conversations from the chat corpus using timestamp and reply proximity heuristics.
- `Study 3 - Robust Analysis.ipynb` — Primary analysis notebook for the qualitatively coded comment sample and reconstructed conversation sample. Includes frequency distributions, cross-tabulations, and inter-rater reliability calculations.
- `Study 3 - Analyze Qualitatively Coded Comments.ipynb` — Analysis of the coded individual comment corpus.
- `Study 3 - Coded Individual Comments.xlsx` — Qualitatively coded sample of 2,000 individual comments with L1 (communicative function) and L2 (trust practice) codes applied.
- `Study 3 - Coded Conversations.xlsx` — Qualitatively coded sample of 200 reconstructed micro-conversations with L1 and L2 codes applied.

---

## Supplementary: North Platte / Whitman Tornado X/Twitter Analysis

- `northplatte_whitman.ipynb` — Descriptive analysis of the 418-post X/Twitter corpus collected around the June 2024 Whitman, Nebraska tornado and the concurrent NWS warning gap. This corpus is described in Chapter 1 of the dissertation.

---

## Dependencies

Notebooks were developed in Python 3 and are runnable in Google Colab. Key packages: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`.

---

## Citation

Vera, J. A. (2026). *Weatherfluencers: Trust and collective sensemaking in severe weather livestreams* [Doctoral dissertation, University of Washington].

---

## Contact

Julie A. Vera | jvera@uw.edu
