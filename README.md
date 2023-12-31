# PATAT
Predicting Affective Tokens for Aspect Terms for tackling ABSA (PATAT)

:star: :star: :star: :star: :star:
> Word Transferred Language Model for Aspect-based Sentiment Analysis]{PATAT: A Novel BERT-based Aspect-based Sentiment Analysis Approach by Utilizing ``Masked Language Model'' to Predict Affective Tokens for Target Words :smiley:

[![](/assets/wordtransabsa.PNG "Model Architecture of PATAT")][Model Architecture of PATAT]

```angular2html
> In order to alleviate the limitations of mainstream fine-tuning methods, we propose Predicting Affective Tokens for Aspect Terms (PATAT). PATAT subverts the conventional criterion of Transformerbased fine-tuning methods by utilizing the entire parameters in Transformer, to fully exploit the prior knowledge in Transformer.

> Compared with prompt learning, which requiresconstructing extra pre-defined templates with specific slots to better invoke the Pre-train LMs, PATAT only needs sentiment-related pivot tokens to obtain the sentiment polarity-related affective tokens on the position of an aspect term.

> In the specific PATAT implementation, we explore different discover measures to search high quality sentiment-related pivot tokens and try additional transferred word optimization strategies to stimulate the semantic understanding potential of PLMs better.

> The extensive experiments under the data-sufficient scenario (full-data supervised learning) and data-scarce scenario (few-shot learning) validate the superiority and effectiveness of the PATAT, suggesting that regressing to the Transformer pretraining paradigm is a better solution for some specific scenarios like ABSA.
```

***

> The ABSA experimental performance statistics (% Accuracy) between the PATATs and the SOTA baselines.

[![](/assets/comparisons.png "comparisons")][comparisons]

***

> The performance statistics (% Accuracy) of our PATAT variants and the SOTA baselines under the different
few-shot learning settings. All results are averaged over 10 runs to maintain the experimental authenticity.

[![](/assets/fewshotcomparisons.png "fewshot_comparisons")][fewshot_comparisons]

***

# Thanks!

### Star and Fork. 

:sunglasses: :pray: :innocent: :heartpulse: :heartpulse: :heartpulse: 	:stuck_out_tongue_closed_eyes:
