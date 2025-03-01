---
# For reference on dataset card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/datasetcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/datasets-cards
{}
---

# TweetEval Annotated Dataset

<!-- Provide a quick summary of the dataset. -->

This dataset card aims to be a base template for new datasets. It has been generated using [this raw template](https://github.com/huggingface/huggingface_hub/blob/main/src/huggingface_hub/templates/datasetcard_template.md?plain=1).

## Dataset Details

### Dataset Description

- **Curated by:** keimoriyama
- **Language(s) (NLP):** English
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

- **id** 
- **text**
- **original_label**
- **ground_truth_label**
- **emoji_label**
- **annotaiton_[0-3|llm]**
- **annotation_label_[0-3|llm]**

## Citation

<!-- If there is a paper or blog post introducing the dataset, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**

WIP


## Dataset Card Authors [optional]

[More Information Needed]

## Dataset Card Contact

[More Information Needed]
