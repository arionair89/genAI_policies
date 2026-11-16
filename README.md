# Generative AI Policies in Academic Research: Universities and Law Journals

This repository contains a selection of institutional and publishing policies on the use of generative AI in academic research. The university sample comprises 65 Italian universities and special-status higher education institutions, identified according to the institutional framework of the Italian Ministry of University and Research, and the top 30 universities in the Times Higher Education World University Rankings 2026, selected on the basis of the research quality indicator as of 17 September 2026. The journal sample comprises 168 entries from international legal journals (167 journals and one preprint repository, SSRN) associated with 18 publishers, selected for their relevance to the research group's areas of interest, alongside 18 Italian journals covering, among others, private law, financial law, law and technology, biolaw, comparative law, and family law.

All corpora were constructed from publicly available primary sources. For universities, the analysis encompassed AI policies, institutional guidelines, ethical codes, strategic plans, and other relevant documents. For journals, the sources included author guidelines, publication ethics statements, submission instructions, peer-review policies, publication agreements, and publisher-level AI frameworks. Institutions for which no relevant AI policy could be identified were retained in the sample and coded "Not found", since the absence of explicit regulation constitutes a relevant empirical finding. Journals whose documents were examined but contain no reference to AI are coded "Absent" (see Coding conventions).

## Repository contents

| File | Content | Units |
|---|---|---|
| `International_universities_genAI_policies.csv` | GenAI policies of the top 30 universities in the THE World University Rankings 2026 (research quality indicator, as of 17 September 2026) | 30 universities (25 with an identified policy document, 5 "Not found") |
| `Italian_universities_genAI_policies.csv` | GenAI policies of Italian universities and special-status higher education institutions | 65 institutions (35 with an identified policy document, 30 "Not found") |
| `Italian_law_journals_genAI_policies.csv` | GenAI policies of selected Italian law journals | 18 journals (19 records) |
| `International_journals_genAI_policies.pdf` | Annex: mapping of AI-use policies in international law journals, with sources | 168 entries |

## Data collection

| Corpus | Collection period |
|---|---|
| Universities (Italian and international) | June–September 2026 |
| Italian law journals | June–September 2026 |
| International law journals | September–October 2026; policy URLs last verified in October 2026 |

For international journals, each journal's instructions for authors, ethical guidelines, and publication agreements were consulted directly at source. Where no dedicated AI-use provision was found at journal level, the applicable publisher framework was verified on the publisher's own website.

## Dataset description and reading guide

### Universities (international and Italian)

*Mapping of Generative AI Policies and Guidelines at foreign universities (the 30 highest-ranked institutions according to the Research Quality indicator in the Times Higher Education World University Rankings 2026, as of 17 September 2026) and in Italian universities.*

The columns are organised into four main sections. Column names are prefixed with the name of their section (e.g., `General Principles: Academic Integrity`).

- **Institutional information**: identifies the university, country, relevant document, source link, document type, and year (where available).
- **General Principles**: records whether the institutional documents expressly address principles such as academic integrity, human oversight, social and environmental sustainability, AI literacy, and transparency.
- **Rules and Provisions**: identifies specific requirements concerning disclosure of AI use, citation or acknowledgement of AI tools, intellectual property rights, data protection and confidentiality, and authorial accountability.
- **Allowed Uses**: records institutional provisions concerning the use of GenAI for specific academic, teaching, research, and related activities, including linguistic revision, translation, summarisation, brainstorming, literature searches, data analysis, and scientific evaluation.

### Italian law journals

*Mapping of Generative AI Policies and Guidelines in Italian Law Journals (selected), June–September 2026.*

The columns are organised into three main sections.

- **Journal information**: journal, publisher, and subject area (topic).
- **Document information**: the editorial document examined (ethical code, editorial guidelines, author guidelines, peer review rules, etc.), its source link, and its year (`Year`, where available). Where a journal's rules are spread across several documents, each document is reported on a separate record, and the journal, publisher, and topic are repeated.
- **Policy content**: whether the document mentions GenAI (`mention of GenAI`), a summary of its content (`Summary of the policy`), and any reference to external ethical standards (`external sources`).

### International law journals

The Annex (PDF) is organised in eight sections: (1) supranational standard-setters (COPE, ICMJE, WAME, STM, Bluebook); (2) journals with autonomous AI-use policies (nineteen journals and the SSRN preprint repository); (3) publisher frameworks; (4) journals subject to the Cambridge University Press framework; (5) journals subject to the Oxford University Press framework; (6) journals subject to the Wiley, Elsevier, Springer, Taylor & Francis, SAGE, and MDPI frameworks; (7) journals with no identifiable policy; (8) a summary by regulatory model. Policy URLs are given in the rightmost column of each table.

## Coding conventions

**Universities**

- `Y` (Yes): the relevant principle or requirement is expressly recognised, or the activity is explicitly permitted, including where its use is subject to specified conditions.
- `N` (No): the relevant principle or requirement is expressly excluded, or the activity is explicitly prohibited. Where a document expressly discourages an activity without prohibiting it, the activity is coded `N` and the qualification is reported in parentheses.
- `NA` (Not Addressed): the relevant principle, requirement, or activity is not expressly addressed in the institutional document. This code does not imply that the activity is prohibited or permitted.
- `Not found`: no relevant institutional policy or guidance document was identified during the mapping exercise. Where no guidelines were found, the rest of the line is left blank.

Where necessary, additional textual explanations specify conditions, limitations, exceptions, or other relevant qualifications contained in the institutional documents. These explanations should be read together with the corresponding codes.

**Italian law journals**

- `Present`: the document expressly refers to generative AI, machine learning, or AI tools. This code does not indicate the content or direction of the provision, which may be a disclosure obligation, a declaration of non-use by the author, or a restriction on the use of the journal's contributions; the provision is described in the summary and should be read together with the code.
- `Absent`: a relevant document was identified and examined, but it contains no express reference to generative AI, machine learning, or AI tools. Generic references to technology or its responsible use are coded `Absent`.
- `external sources`: `Cross ref to COPE ethical code` indicates that the document expressly refers to the COPE ethical standards; `not found` indicates that no reference to external ethical standards was identified.
- `Year`: year of the document, where indicated; `not found` where no year could be identified.

The distinction between the two sets of datasets is deliberate: `Not found` means that no policy document could be identified, whereas `Absent` means that a document exists but is silent on AI.

## Notes

- Multi-line cells in the original spreadsheets were reduced to a single line; where a cell contains several URLs, they are separated by ` | `. Leading and trailing spaces were removed, and spaces inside URLs were percent-encoded (`%20`).
- Files are comma-separated, UTF-8 encoded, with a single header row.
- The PDF Annex reproduces the content of the Word version; only the page layout (landscape orientation, column widths, font size of the tables) was adapted for readability.

## Limitations

- The datasets are snapshots of documents available at the time of collection. Policies in this field change frequently, and some documents are interim guidelines pending final regulations.
- Some documents could not be fully accessed (for example, where access appears to require authentication); the relevant rows should be read with this in mind.
- The coding records what the documents expressly state; it does not assess how the policies are applied in practice.

## Declaration on the use of AI

AI tools were used for linguistic revision and ex post verification of potential transcription errors and inconsistencies between the Excel spreadsheet and the original sources. The dataset was independently compiled and classified by the authors, and all AI-assisted checks were subject to subsequent human verification.
