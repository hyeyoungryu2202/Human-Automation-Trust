# Human-Automation-Trust

• Key Research Question: Is trust for automated recommendations identical for all recommender system categories or not, and what is human-automation trust composed of?

• Scraped 215,046 reviews from SiteJabber and Trustpilot using Python and Selenium (AI_Trust_Crawling_Updated_August_2019.ipynb, SiteJabber Crawling.ipynb)

• Clustered human-automation trust based on previous literatures regarding the topical area into six differentiating trust features

• Clustered the recommender systems with surveys that asked the respondents to rate the level of importance for each trust feature per recommender system

• Explored the reviews by extracting important words through TF-IDF and Decision Tree and Gaussian Naïve Bayes classifiers (New POS Tagging_Decision Tree Classifier.ipynb) and sentiment analysis with Sentiment VADER (EURAM_crawl_text_sentiment_analysis.ipynb)

• Calculated Euclidean distance between the recommender system clusters and the trust clusters to examine which trust cluster had more significance (EURAM_PCA + Euclidean Distance.ipynb)

• Conducted a co-authorship network analysis using Gephi to investigate the articles that would have the most influence with high eigenvector centrality scores and those that have ties that are crucial for network flow with high betweenness and low degree association

