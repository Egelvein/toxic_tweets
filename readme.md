# Description
Social media platforms have become a prevalent means of communication, but they also face challenges related to the spread of toxic content. Identifying and moderating toxic tweets is crucial for maintaining
a healthy online environment. In this study, we focus on the binary classification of tweets as either toxic or non-toxic using natural language
processing techniques.

## Contents
- [Methods](#methods)
- [Success Metrics](#success-metrics)
- [Contributing](#contributing)
- [FAQ](#faq)
- [Project Team](#project-team)
- [Links](#links)


### Methods
The code, comments and comparison are provided in the “methods” folder. So 4 different approaches have been used:
BERT, CatBoostClassifier, embeddings + CatBoostClassifier, ensemble models.


### Success Metrics
F1-score binary was chosen as the metric. The ensemble model showed the best result (0.919), the detailed description can be seen in the notebook or in template.


### Contributing
If you would like to participate in the project development, give feedback or complain about errors - write to someone from the project team (below).


### FAQ
We will fill it in as errors occur while using the project.


### Project Team
[Adelina Tsoi](https://www.linkedin.com/in/adelina-tsoi/) - prepared paper and documentation

[Viacheslav Siniaev](https://www.linkedin.com/in/vyacheslavsinyaev/) - developed models and measured the results


### Links
Dataset is [here](https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset?resource=download)

BERT-based model is [here](https://huggingface.co/JungleLee/bert-toxic-comment-classification). We can say that this model is SOTA because it has >200k downloads a month.

The model by which we obtained the embeddings for our data is [here](https://huggingface.co/jinaai/jina-embeddings-v2-base-en)
