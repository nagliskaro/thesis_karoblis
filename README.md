Repository contains Python code for the analysing of Bachelor's Thesis. 

Naglis Karoblis, 13129104:
"Evaluation of Text Mining Algorithms on Short-Text Consumer Preference Survey"

Text Classification:

"Supervised_" narratives contain analysis for text classification task for two questions. "_no" is the Narrative Open question corresponding to Appendix A.2; "_ns" is the Narratives Self question corresponding to Appendix A.1


Named Entity Recognition:
1. Running NER_BERT.ipynb to generate .json raw output
2. Running fuzzy_ner.ipynb to clean through the mislabeling and typos; generating pickle file
3. Running ner_evaluation.ipynb for evaluations and political affiliations grouping

Note! Before running BERTopic narrative, appropriate libraries should be installed

