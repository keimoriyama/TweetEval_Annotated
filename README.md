# README

## Dataset Summary

TweetEval-Annotated is created from emoji classification task of TweetEval dataset.
This dataset aims to simulate the task assignment strategy.
This dataset contains target task, ground truth label and annotations.
Annoation labels are from humans and LLMs.
Human annotation are created from the non-native English speaker.
LLM annotation is generated using few-shot prompt.

## Languages

The text in this dataset is English posted on X.

## Data Content

| Column name | Explanation |
|:-----------:|:-----------:|
|id | id number of the data |
|text| classification target text|
|original\_label| class label in TweetEval datset |
|emoji\_label | corresponding emoji |
|annotation\_[0-3]| annotation from annotator 0~3 |
| annotation\_label\_[0-3]| corresponding annotation emoji 0~3|
|llm\_annotation| annotation from LLM |

## Target Label

# License

This dataset is licensed under a Creative Commons Attribution 4.0 International License.

License details: https://creativecommons.org/licenses/by/4.0/
