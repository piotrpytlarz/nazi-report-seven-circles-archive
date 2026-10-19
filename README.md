---
license: cc-by-4.0
task_categories:
  - text-classification
  - question-answering
  - feature-extraction
  - translation
language:
  - en
  - pl
  - de
  - ru
  - fr
tags:
  - digital-humanities
  - history
  - ww2
  - holocaust
  - occupied-poland
  - knowledge-graph
  - legal-history
  - entity-linking
  - multilingual-corpus
pretty_name: Nazi Report — Seven Circles of Responsibility Multilingual Historical Archive & Knowledge Graph
description: >-
  Five-language digital humanities archive and historical knowledge graph (CC BY 4.0):
  499 perpetrator profiles across the Seven Circles of Responsibility, 1,846 directed
  graph edges, 206 memorial calendar events, 55 documented crime dossiers, and 127
  historical/legal glossary terms (EN/PL/DE/RU/FR) published by https://nazi.report
size_categories:
  - 1K<n<10K
---

# Nazi Report — Seven Circles of Responsibility: Multilingual Historical Archive & Knowledge Graph (CC BY 4.0)

Published by **[Nazi Report — Seven Circles of Responsibility / Siedem Kręgów Zbrodni](https://nazi.report)** — an evidence-based, five-language digital historical archive documenting the perpetrators, institutions, crime mechanisms, and postwar legal accountability of Nazi crimes in Europe (1933–1945), with its principal research focus on occupied Poland.

All structured datasets in this repository are released under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**. You are free to share, adapt, and redistribute this data in academic, educational, digital humanities, and machine learning projects provided you attribute **Nazi Report** with a link back to the canonical URLs at [`https://nazi.report`](https://nazi.report).

---

## 📦 Included Open Datasets (5 Languages: EN · PL · DE · RU · FR)

| Dataset File | Records | Formats | Description & Canonical Interactive Hub |
|---|---:|---|---|
| `perpetrator-profiles-index.json` / `.csv` | **499** | JSON, CSV | Complete 5-language index of **[499 Perpetrator & Functionary Profiles](https://nazi.report/en/people/)** structured across the **[Seven Circles of Responsibility](https://nazi.report/en/circles/)**, including biographical metadata, organizations, ranks, command/scope levels, crime profiles, postwar verdicts/fates, evidentiary limitations, institutional source URLs (USHMM, IPN, Auschwitz-Birkenau State Museum, Yad Vashem, NMT), and canonical URLs in EN, PL, DE, RU, and FR. |
| `historical-glossary-index.json` / `.csv` | **127** | JSON, CSV | Complete 5-language **[Historical, Institutional & Legal Glossary](https://nazi.report/en/glossary/)** covering 127 concepts across 7 types (operations, institutions, camps/places, trials, legal categories, mechanisms, and perpetrator-language euphemisms with explicit critical warnings), cross-referenced to profiles, crime dossiers, mechanisms, and calendar events. |
| `memorial-calendar-events.json` / `.csv` | **206** | JSON, CSV | Complete 5-language **[Memorial Calendar (`NR-001`–`NR-206`)](https://nazi.report/en/calendar/)** of 206 source-verified historical events, leads, historical contexts, significance notes, and explicit separation of `direct` vs. `contextual` profile links, with deep links to the 65 monthly calendar articles. |
| `documented-crimes-dossiers.json` / `.csv` | **55** | JSON, CSV | Complete 5-language index of **[55 Documented Crime Dossiers in Occupied Poland (1939–1945)](https://nazi.report/en/crimes/)**, detailing dates, regions, victim findings, perpetrator units, documented violence methods, explicit evidentiary limitations, and primary investigative/archival sources. |
| `knowledge-graph-relations.json` / `.csv` | **1,846 edges**<br>**(151 nodes)** | JSON, CSV | Complete **[Historical Knowledge Graph & Network](https://nazi.report/en/network/)** connecting the 499 perpetrator profiles with 151 historical context nodes (operations, camps, trials, institutions, occupied territories) via 1,846 directed edges (`commanded`, `participated_in`, `tried_in`, `subordinated_to`, `supervised`, etc.). |

---

## 🌐 Five-Language Editions & Interactive Hubs on `nazi.report`

Every entity in this dataset resolves to a permanent, cross-linked page across five language editions (`hreflang`-synchronized):

| Hub / Section | 🇬🇧 English (`/en/`) | 🇵🇱 Polski (`/`) | 🇩🇪 Deutsch (`/de/`) | 🇷🇺 Русский (`/ru/`) | 🇫🇷 Français (`/fr/`) |
|---|---|---|---|---|---|
| **Home & Overview** | [nazi.report/en/](https://nazi.report/en/) | [nazi.report](https://nazi.report/) | [nazi.report/de/](https://nazi.report/de/) | [nazi.report/ru/](https://nazi.report/ru/) | [nazi.report/fr/](https://nazi.report/fr/) |
| **Perpetrator Archive (499)** | [/en/people/](https://nazi.report/en/people/) | [/archiwum](https://nazi.report/archiwum) | [/de/personen/](https://nazi.report/de/personen/) | [/ru/persony/](https://nazi.report/ru/persony/) | [/fr/personnes/](https://nazi.report/fr/personnes/) |
| **Seven Circles Index** | [/en/circles/](https://nazi.report/en/circles/) | [/krag-1](https://nazi.report/krag-1) – [/krag-7](https://nazi.report/krag-7) | [/de/kreise/](https://nazi.report/de/kreise/) | [/ru/krugi/](https://nazi.report/ru/krugi/) | [/fr/cercles/](https://nazi.report/fr/cercles/) |
| **Knowledge Graph Network** | [/en/network/](https://nazi.report/en/network/) | [/siec](https://nazi.report/siec) | [/de/netzwerk/](https://nazi.report/de/netzwerk/) | [/ru/set/](https://nazi.report/ru/set/) | [/fr/reseau/](https://nazi.report/fr/reseau/) |
| **Documented Crimes (55)** | [/en/crimes/](https://nazi.report/en/crimes/) | [/zbrodnie/](https://nazi.report/zbrodnie/) | [/de/verbrechen/](https://nazi.report/de/verbrechen/) | [/ru/prestupleniya/](https://nazi.report/ru/prestupleniya/) | [/fr/crimes/](https://nazi.report/fr/crimes/) |
| **Crime Mechanisms (15)** | [/en/mechanisms/](https://nazi.report/en/mechanisms/) | [/siec](https://nazi.report/siec) | [/de/mechanismen/](https://nazi.report/de/mechanismen/) | [/ru/mekhanizmy/](https://nazi.report/ru/mekhanizmy/) | [/fr/mecanismes/](https://nazi.report/fr/mecanismes/) |
| **Regional Chains (5)** | [/en/regions/](https://nazi.report/en/regions/) | [/archiwum](https://nazi.report/archiwum) | [/de/regionen/](https://nazi.report/de/regionen/) | [/ru/regiony/](https://nazi.report/ru/regiony/) | [/fr/regions/](https://nazi.report/fr/regions/) |
| **Historical Glossary (127)** | [/en/glossary/](https://nazi.report/en/glossary/) | [/slownik](https://nazi.report/slownik) | [/de/begriffe/](https://nazi.report/de/begriffe/) | [/ru/terminy/](https://nazi.report/ru/terminy/) | [/fr/glossaire/](https://nazi.report/fr/glossaire/) |
| **Memorial Calendar (206)** | [/en/calendar/](https://nazi.report/en/calendar/) | [/kalendarz/](https://nazi.report/kalendarz/) | [/de/kalender/](https://nazi.report/de/kalender/) | [/ru/kalendar/](https://nazi.report/ru/kalendar/) | [/fr/calendrier/](https://nazi.report/fr/calendrier/) |
| **Timeline / Chronology** | [/en/timeline/](https://nazi.report/en/timeline/) | [/os-czasu](https://nazi.report/os-czasu) | [/de/chronologie/](https://nazi.report/de/chronologie/) | [/ru/khronologiya/](https://nazi.report/ru/khronologiya/) | [/fr/chronologie/](https://nazi.report/fr/chronologie/) |
| **Methodology & Sources** | [/en/methodology/](https://nazi.report/en/methodology/) | [/zrodla](https://nazi.report/zrodla) | [/de/methodik/](https://nazi.report/de/methodik/) | [/ru/metodologiya/](https://nazi.report/ru/metodologiya/) | [/fr/methodologie/](https://nazi.report/fr/methodologie/) |
| **Memorial & Victims** | [/en/memory/](https://nazi.report/en/memory/) | [/pamiec](https://nazi.report/pamiec) | [/de/gedenken/](https://nazi.report/de/gedenken/) | [/ru/pamyat/](https://nazi.report/ru/pamyat/) | [/fr/memoire/](https://nazi.report/fr/memoire/) |

### The Seven Circles of Responsibility (`tier` 1–7)
The taxonomy organizes perpetrators by **institutional function, agency, and position in the chain of decision and execution**—never as a moral "scale of guilt" or a ranking by victim counts:
- **[Circle I — Supreme Architect](https://nazi.report/en/circles/1/)** ([PL](https://nazi.report/krag-1) · [DE](https://nazi.report/de/kreise/1/) · [RU](https://nazi.report/ru/krugi/1/) · [FR](https://nazi.report/fr/cercles/1/)): Initiator and supreme decision-maker of aggressive war and genocide as a state project.
- **[Circle II — Strategic Core of the Regime](https://nazi.report/en/circles/2/)** ([PL](https://nazi.report/krag-2) · [DE](https://nazi.report/de/kreise/2/) · [RU](https://nazi.report/ru/krugi/2/) · [FR](https://nazi.report/fr/cercles/2/)): Reich leadership shaping state terror, war policy, occupation regimes, and economic mobilization.
- **[Circle III — Designers of the Machinery of Destruction](https://nazi.report/en/circles/3/)** ([PL](https://nazi.report/krag-3) · [DE](https://nazi.report/de/kreise/3/) · [RU](https://nazi.report/ru/krugi/3/) · [FR](https://nazi.report/fr/cercles/3/)): Architects of the RSHA, WVHA, camp system, Aktion Reinhardt, Aktion T4, and mass deportation logistics.
- **[Circle IV — Territorial Rulers and Programme Chiefs](https://nazi.report/en/circles/4/)** ([PL](https://nazi.report/krag-4) · [DE](https://nazi.report/de/kreise/4/) · [RU](https://nazi.report/ru/krugi/4/) · [FR](https://nazi.report/fr/cercles/4/)): Reichsstatthalter, Gauleiter, Governors-General, Higher SS and Police Leaders (HSSPF), and regional programme directors.
- **[Circle V — Operational Commanders](https://nazi.report/en/circles/5/)** ([PL](https://nazi.report/krag-5) · [DE](https://nazi.report/de/kreise/5/) · [RU](https://nazi.report/ru/krugi/5/) · [FR](https://nazi.report/fr/cercles/5/)): Camp commandants, Einsatzgruppen/Einsatzkommando commanders, SSPF, KdS, and Order Police battalion commanders.
- **[Circle VI — Enablers of War and Occupation](https://nazi.report/en/circles/6/)** ([PL](https://nazi.report/krag-6) · [DE](https://nazi.report/de/kreise/6/) · [RU](https://nazi.report/ru/krugi/6/) · [FR](https://nazi.report/fr/cercles/6/)): Judicial terror judges/prosecutors, ministerial bureaucrats, medical experimenters, industrialists exploiting forced labour, and cultural plunderers.
- **[Circle VII — Inciters and Local Perpetrators](https://nazi.report/en/circles/7/)** ([PL](https://nazi.report/krag-7) · [DE](https://nazi.report/de/kreise/7/) · [RU](https://nazi.report/ru/krugi/7/) · [FR](https://nazi.report/fr/cercles/7/)): Block/rapport leaders, Gestapo interrogators, camp guards, Selbstschutz commanders, and regime propagandists.

### Featured Mechanism & Regional Deep Dives
- **Regional Chains of Command:** [Warsaw](https://nazi.report/en/regions/warszawa/) · [Łódź (Litzmannstadt)](https://nazi.report/en/regions/lodz/) · [Kraków](https://nazi.report/en/regions/krakow/) · [Poznań (Wartheland)](https://nazi.report/en/regions/poznan/) · [Bydgoszcz & Pomerania](https://nazi.report/en/regions/bydgoszcz/)
- **Selected Mechanism Dossiers:**
  - [Regional Gestapo, Security Police and SD Offices](https://nazi.report/en/mechanisms/regional-gestapo-sipo-sd/)
  - [Ghettoisation, Deportation and Liquidation](https://nazi.report/en/mechanisms/ghettoisation-deportation-liquidation/)
  - [Camp Command, Mass Killing and Evacuation Marches](https://nazi.report/en/mechanisms/camp-command-killing-evacuation/)
  - [Order Police Battalions and Mass Shootings](https://nazi.report/en/mechanisms/order-police-battalions-mass-shootings/)
  - [Medical Killing, Aktion T4 and Camp Selections](https://nazi.report/en/mechanisms/medical-killing-t4-selection/)
  - [State Bureaucracy, Germanisation and Judicial Terror](https://nazi.report/en/mechanisms/state-bureaucracy-germanization-judicial-terror/)

---

## ⚖️ Methodological & Epistemological Guardrails

When using these datasets for historical research, knowledge-graph construction, or NLP/LLM benchmarking, please preserve the following source constraints:

1. **Two Independent Institutional Publishers Per Profile:** Every published profile in `perpetrator-profiles-index` is backed by at least two independent institutional or scholarly publishers (e.g., USHMM, Institute of National Remembrance / IPN, Auschwitz-Birkenau State Museum, Yad Vashem, Harvard/Yale Nuremberg Trials Project, German Federal Archives).
2. **Direct vs. Contextual Linkages (`direct_profile_slugs` vs. `contextual_profile_slugs`):** In `memorial-calendar-events` and `documented-crimes-dossiers`, links between events/crimes and perpetrator profiles are strictly typed as either `direct` (verified personal command or participation) or `contextual` (institutional, territorial, or structural chain-of-command context). Do not collapse `contextual` relations into claims of direct personal participation in a specific act.
3. **Explicit Evidentiary Limitations (`limitations_*`):** Every profile, glossary term, and crime dossier includes an explicit `limitations` field stating where victim counts represent investigative minimums rather than closed nominal lists, or where postwar court findings left specific charges un adjudicated.
4. **Perpetrator Language Warnings (`perpetrator_language_warning`):** Bureaucratic Nazi euphemisms (such as *Sonderbehandlung*, *Evakuierung*, or *Befriedungsaktion*) are flagged in `historical-glossary-index` so downstream models and researchers do not reproduce perpetrator framing uncritically.

---

## 📝 How to Cite (APA & BibTeX)

**APA:**
> Nazi Report. (2026). *Seven Circles of Responsibility: Multilingual Historical Archive, Crime Dossiers, and Knowledge Graph (EN/PL/DE/RU/FR)*. Retrieved from https://nazi.report

**BibTeX:**
```bibtex
@misc{nazi_report_2026,
  author = {{Nazi Report Editorial Archive}},
  title = {{Seven Circles of Responsibility: Multilingual Historical Archive, Crime Dossiers, and Knowledge Graph}},
  year = {2026},
  howpublished = {\url{https://nazi.report}},
  note = {Five-language open dataset (EN, PL, DE, RU, FR) licensed under CC BY 4.0}
}
```

---

## 🔗 Related Open Research Datasets & Platforms
- **[Skills Intelligence — GenAI 2026 Skills Atlas & AI Glossary](https://www.skillsintelligence.tools)** — Open research index of 466 AI/Data skills, prerequisite graphs, and 400 maturity-graded glossary terms.
- **[WWW Taxonomy (`wwwtaxonomy.com`)](https://wwwtaxonomy.com)** & **[Taxonomy Works (`taxonomy.works`)](https://taxonomy.works)** — Applied taxonomy engineering, controlled vocabularies, and multi-axis classification systems.
