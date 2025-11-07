# pubmed-AbGen-extension
Citation-aware dataset for AbGen benchmark extension
# PubMed AbGen Extension

This repository contains the citation-aware dataset constructed to extend the AbGen benchmark for scientific reasoning in LLMs.

## Contents

- `dataset.json`: Original PubMed abstracts and synthetic citation variants
- `scores.json`: Soundness and importance scores from GPT-4 and manual annotation
- `annotation_rubric.md`: Rubric adapted from AbGen for evaluating factuality and relevance

## Construction Process

Abstracts were retrieved from PubMed using the E-utilities API. Variants were generated to simulate citation edits and formatted for AbGen-style prompts. Human annotation was performed on 50 samples, with Cohen’s kappa = 0.82.

## License

This dataset is released under the MIT License.
