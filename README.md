## Code for Evaluation of impact of contextual importance of COT tokens

### Updates

Analysis based on Extended Set is available on ![notes](https://notes.itskd.me/doc/cot-faithfulness-extra-vs-external-tokens-xBXJ54de0K).

Problem Statement: Chain-of-thought (CoT) prompting often improves model performance and is commonly treated as evidence of how a model reasons. 

Is the semantic content of CoT causally necessary for correct answers, or can it use internal layers for reasoning with enough inference compute?

For more details check out the following ![doc](https://docs.google.com/document/d/10aRH1BESpif-VJnFDUfc0XZgS7pw_wtX4TepCe27Epo/edit?tab=t.0)

## Code Structure

Two notebooks:
- evaluation.ipynb: Evaluate all the strategies across validation datasets
- analysis.ipynb: Perform Spatial and Temporal wide analysis

## Useful Links
- Evaluation Dataset across strategies: ![Google Sheet](https://docs.google.com/spreadsheets/d/1FSd1UauH16fzvZKIBiu0jYzv-77aLvePFtIkzg4DDiQ/edit?usp=sharing)


## Extended Results
- Performance on full dataset of triviaQA
|Type | Initial Samples | Length-matched filler | Unrelated coherent scratchpad | Proper CoT|
|-----|-----------------|-----------------------|-------------------------------|-----------|
|Results|523 (out of 5771)|50|156|195|
|Results (Extended Set)|2551 (out of 22715)|994|869|1262|
"Initial Samples
 (`No CoT` Failure Cases)"