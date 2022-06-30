# CVE_analysis_with_NLP

Information about CVE: https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures

Open 'NLP_CVE_summaries.ipynb' in jupyter notebook to view.

Analyzing a dataset with unlabeled CVE summaries from open-source third-party software.
The goal is to figure out what weakness each vulnerability is describing and visualizing the results. Using machine learning to categorize each summary, this might be possible.

Different ways this dataset will be analyzed:

1. Supervised text categorization with hierarchical attention network (HAN)

2. Unsupervised topic modelling visualisation with gensim and pyLDAvis

3. Vulnerability update time analysis


Libraries required:

numpy,
pandas,
seaborn,
matplotlib

keras,
sklearn,
tensorflow

gensim,
pyLDAvis

nltk, spacy  (spacy3) 

    needs en_core_web_lg
    download by:
    python -m spacy download en_core_web_lg
