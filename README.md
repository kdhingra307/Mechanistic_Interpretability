## Code for Evaluation of impact of contextual importance of COT tokens

Problem Statement: Chain-of-thought (CoT) prompting often improves model performance and is commonly treated as evidence of how a model reasons. 

Is the semantic content of CoT causally necessary for correct answers, or can it use internal layers for reasoning with enough inference compute?

For more details check out the following ![doc](https://docs.google.com/document/d/10aRH1BESpif-VJnFDUfc0XZgS7pw_wtX4TepCe27Epo/edit?tab=t.0)

## Code Structure

Two notebooks:
- evaluation.ipynb: Evaluate all the strategies across validation datasets
- analysis.ipynb: Perform Spatial and Temporal wide analysis