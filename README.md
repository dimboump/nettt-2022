# Quantitative and Qualitative Evaluation of Human and Machine-Translated EU Economic Texts in the English-Greek Language Pair

## Abstract

Studying the literature regarding EU texts, we see that there are publications on the usefulness of neural machine translation (NMT) for translators in EU institutions, who professionally translate from a major into minor languages. However, there is a research gap regarding the quantitative analysis of human and machinetranslated texts in major-to-minor language combinations. This paper explores the quantitative characteristics of both kinds of texts and tries to profile them. We explore the impact of many input textual features, including word n-grams frequencies, Parts of Speech (PoS), function words, punctuation, and a number of stylometric indices (e.g., readability index, type/token ratio, and mean sentence length). We compiled a corpus of 646 English press releases manually translated into Greek by professionals in the European Central Bank, along with their NMT counterparts by state-of-the-art systems. We produce input features for a Support Vector Machines (SVM) algorithm that can predict whether a text is produced by a human or an NMT system and achieves 90% accuracy and f1-macro score. Furthermore, we compare the similarity between the original and the NMT outputs using methods for dimensionality reduction and cluster analysis (PCA, HCA, t-SNE). Finally, we evaluate the quality of the NMT outputs using BLEU.

## Resources

- [Corpus](./data/corpus/)
- [Poster](./Poster.pdf)
- [Paper](./Boumparis%20%26%20Giannoutsos%20(2022).pdf)

## Cite this paper

To cite this paper, please:

1. Add the following code in your `.bib` file.
2. Refer to it by using `\cite{boumparis-giannoutsos-2022-quantitative}`.

```bibtex
@inproceedings{boumparis-giannoutsos-2022-quantitative,
	title        = {Quantitative and Qualitative Evaluation of Human and Machine-Translated EU Economic Texts in the English-Greek Language Pair},
	author       = {Boumparis, Dimitris and Giannoutsos, Christos},
	year         = 2023,
	month        = {July},
	booktitle    = {Proceedings of the New Trends in Translation and Technology Conference - NeTTT 2022},
	address      = {Rhodes Island, Greece},
	editor       = {Castilho, Sheila and Caro Quintana, Rafael and Stasimioti, Maria and Sosoni, Vilelmini},
	days         = {4-6},
}
```
