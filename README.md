# Voting Ensemble Technique for Spam Classification

## Abstract

This paper proposes a voting ensemble technique for spam classification. While previous authors have proposed voting ensemble methods for spam filtering, this research offers an alternative criteria for determining which underlying methods should be included in the ensemble. The suggested approach relies on a training, validation, and test data design, whereby the validation dataset is used to evaluate an optimal ensemble.

The voting ensemble considered here is a three-method model with hard voting and equal weighting. Eleven different underlying methods are considered for inclusion in the ensemble. These underlying methods range from older naïve Bayes methods to modern Bidirectional Encoder Representations from Transformers (BERT). All possible three-method ensembles using these eleven underlying methods are evaluated against the validation dataset, and the resulting ensemble with the highest F-score is selected as optimal.

For the dataset examined in this paper, the resulting ensemble is found to outperform the ensemble design proposed by previous authors.

## Keywords

- Spam classification
- Voting ensemble
- BERT (Bidirectional Encoder Representations from Transformers)
- Support Vector Machine (SVM)
- Random Forests
- Extremely Randomized Trees (ExtraTrees)
- Neural Networks
- Natural Language Processing (NLP)
