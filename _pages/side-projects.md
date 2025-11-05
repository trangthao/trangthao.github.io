---
layout: archive
title: "Side Projects"
permalink: /side-projects/
author_profile: true
redirect_from:
  - /side-projects
  - /side-projects
  - /side-projects
---

<hr>

### Welcome to Ngẫm Kinh Tế

Welcome! [*Ngẫm Kinh Tế*](https://github.com/trangthao/side-projects/blob/main/patents-web-scraping/match_patents_firmid.ipynb) is a platform dedicated to exploring and discussing industrial policy and the economics of innovation for Vietnamese audience. My goal is to bridge the gap between academic research and practical application, making complex economic concepts accessible to a wider audience. Here, I share in-depth analyses on the forces shaping our world.

For example, I wrote an overview on the latest shifts in [**global venture capital**](https://ngamkinhte.com/dau-tu-mao-hiem-toan-cau-nua-dau-nam-2025-phan-tich/), the rise of [**European Deep Tech**](https://ngamkinhte.com/he-sinh-thai-cong-nghe-chuyen-sau-deep-tech-chau-au-phan-tich/), and the future of emerging sectors like [**drone delivery**](https://ngamkinhte.com/giao-hang-bang-drone-phan-tich/) and the [**global hydrogen market**](https://ngamkinhte.com/thi-truong-hydro-toan-cau-phan-tich/), and took a close look at major economic events and structures, particularly in China, from its evolving [**electricity market**](https://ngamkinhte.com/thi-truong-dien-trung-quoc-phan-tich/) and the history of its [**mobile internet wars**](https://ngamkinhte.com/cuoc-chien-internet-di-dong-trung-quoc-2007-2009-phan-1-phan-tich/) to events like the [**2015 Yuan devaluation**](https://ngamkinhte.com/pha-gia-dong-nhan-dan-te-nam-2015-phan-tich/).

---

### Data projects

*   [**"Patents Web Scraping"**](https://github.com/trangthao/side-projects/blob/main/patents-web-scraping/match_patents_firmid.ipynb)
    *   Scraped patent data from the Vietnam Patent Office (2007-2019).
    *   Matched patents with Vietnamese firms using an Entity Matching model and Google API to establish unique linkage between patents and firms.
*   [**"Customer Churn Prediction"**](https://github.com/trangthao/side-projects/blob/main/customer-churn-prediction/Customer_Churn_Prediction_Analysis_using_Ensemble_Techniques.ipynb)
    *   Developed machine learning models to predict customer churn in banking, utilizing various supervised learning algorithms (e.g., Regression, SVM, Random Forest, XGBoost).
    *   Optimized hyperparameters using RandomSearch and GridSearch; achieved best model performance with an accuracy of 0.83, F1-score of 0.62, and ROC AUC of 0.76.
*   [**"Customer Complaints Classification"**](https://github.com/trangthao/side-projects/blob/main/customer-complaint-classification/attention.ipynb)
    *   Developed a classification model for over two million customer complaints regarding financial products, predicting the corresponding product.
    *   Employed multiclass text classification with an attention mechanism, achieving an accuracy of 66.5%.

---

###  Review of data science and machine learning

*   **[13 Dec 2024] A new blog on Medium ["Understanding challenges in deploying ML"](https://medium.com/@thaotrangk49clc3/understanding-challenges-in-deploying-ml-31cf58287d51) is posted.**
    *   In this post, I summarized the key challenges of running machine learning in practice, from handling data inconsistencies and integrating with existing systems to monitoring model performance after deployment. These insights highlight the complexities of operationalizing ML and offer strategies by other tech firms to address them effectively, ensuring that machine learning systems deliver value in real-world settings.
*   **[12 Dec 2024] A new blog on Medium ["Understanding measuring long-term effects"](https://medium.com/@thaotrangk49clc3/understanding-measuring-long-term-effects-05764c59970d) is posted.**
    *   In this post, I summarized how to measure long-term outcomes in A/B testing. While short-term results are easy to track, they often miss lasting impacts. Three approaches can help: Long-term experiments or holdouts compare groups over time but are slow and costly; Modeling user learning tracks how users adapt to changes, offering better insights into lasting effects; and Surrogate metrics use short-term data to predict long-term outcomes, enabling faster decisions. I also summarized examples from Instacart, Netflix, and LinkedIn to show these methods' benefits and challenges (especially in using surrogate metrics), emphasizing the need to balance speed and accuracy in decision-making.
*   **[12 Dec 2024] A new blog on Medium ["Understanding triggered analysis"](https://medium.com/@thaotrangk49clc3/understanding-triggered-analysis-bd52f63d498d) is posted.**
    *   In this post, I summarized triggered analysis in A/B testing, which focuses on users directly affected by the experiment (e.g., those reaching a checkout page). This method improves sensitivity by reducing noise from unaffected users but comes with challenges like smaller sample sizes and generalization issues. Key techniques like CUPED help reduce variance by leveraging pre-treatment data, making the analysis more precise and robust. For more details, see Larsen et al. (2024) and Kohavi et al. (2020).
*   **[12 Dec 2024] A new blog on Medium ["Understanding inference"](https://medium.com/@thaotrangk49clc3/understanding-inference-1cbcfe13b5d7) is posted.**
    *   In this post, I summarized interference in A/B testing, where users’ behavior influences others, breaking the assumption of independent effects (SUTVA). Common types include: Network Interference (i.e. Users affect each other through connections (e.g., LinkedIn messaging)), and Marketplace Interference (i.e. Users compete for shared resources (e.g., ride-sharing drivers). Suggested solutions include Cluster Randomization (i.e. Treat entire user clusters to limit interference), Switchback Experiments (i.e. Alternate treatment and control over time), Budget-Split Designs (i.e. Divide shared resources evenly in marketplaces), and Modeling Interference (i.e. Use network or marketplace models to account for interactions). These methods reduce interference but often trade off statistical power.
