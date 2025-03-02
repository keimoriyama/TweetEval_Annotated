---
# For reference on dataset card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/datasetcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/datasets-cards
{}
---

# TweetEval-Annotated Dataset

<!-- Provide a quick summary of the dataset. -->
TweetEval-Annotated dataset is crowd-sourced collection of the ground-truth label and annotations.
This dataset is created a part from the emoji recognition task in TweetEval dataset.
The difference is the collection of the annotation of human and LLMs.

## Dataset Details

### Dataset Description

- **Curated by:** keimoriyama
- **Language(s) (NLP):** English only
- **License:** Creative Commons Attribution 4.0 International License.

### Dataset Sources [optional]

This dataset is created from the emoji recognition task in TweetEval dataset.

- **Repository:** [cardiffnlp/tweet_eval](https://huggingface.co/datasets/cardiffnlp/tweet_eval)

## Uses

<!-- Address questions around how the dataset is intended to be used. -->

### Direct Use

<!-- This section describes suitable use cases for the dataset. -->

[More Information Needed]

## Dataset Structure

<!-- This section provides a description of the dataset fields, and additional information about the dataset structure such as criteria used to create the splits, relationships between data points, etc. -->

An instance of the dataset is:

```jsonl
  {
    "id": 574,
    "text": "Magical moonbeam light dance. Things are good.",
    "original_label": 5,
    "ground_truth_label": 3,
    "emoji_label": "😊",
    "annotation_0": "😊",
    "annotation_label_0": 3,
    "annotation_1": "😊",
    "annotation_label_1": 3,
    "annotation_2": "😊",
    "annotation_label_2": 3,
    "annotation_3": "😊",
    "annotation_label_3": 3,
    "annotation_llm": 3,
    "annotation_label_llm": "😊"
  }
```

## Data Fields

- **id** : id of the dataset
- **text** : Target text 
- **original_label** : Corresponding label of `ground_truth_label` in TweetEval dataset 
- **ground_truth_label** : Correct annotation label
- **emoji_label** : Correct annotation label of emoji
- **annotaiton_[0-3|llm]** : Annotation from the human(0~3) and LLM(llm)
- **annotation_label_[0-3|llm]** : Annotation of emoji from the human(0~3) and LLM(llm)

## Citation

<!-- If there is a paper or blog post introducing the dataset, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**

WIP


## Dataset Card Authors [optional]

[More Information Needed]

## Dataset Card Contact

[More Information Needed]
