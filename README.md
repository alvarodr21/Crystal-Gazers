---
annotations_creators:
- no-annotation
language:
- ca
language_creators:
- crowdsourced
license:
- cc-by-sa-3.0
multilinguality:
- monolingual
pretty_name: "Viquip\xE8dia"
size_categories:
- unknown
source_datasets:
- original
tags:
- wikipedia
- catalan
- text
- articles
- educational
task_categories:
- text-generation
task_ids:
- language-modeling
---

## Dataset Description

- **Link:** [https://www.kaggle.com/datasets/jarfo1/viquipdia]()
- **Main author:** [José Andrés Rodriguez Fonollosa](https://www.kaggle.com/jarfo1)

### Dataset summary

The Wikipedia dataset is a collection of scraped Wikipedia pages. The dataset is defined in catalan language, thus the model will be trained to recognize input exclusively in catalan.

### Supported tasks

Text generation

### Languages

Catalan

## Dataset structure

```
{
  'ca-2': [
    'ca.wiki.test.tokens',
    'ca.wiki.train.tokens',
    'ca.wiki.valid.tokens']
  'ca-100': [
    'ca.wiki.test.tokens',
    'ca.wiki.train.tokens',
    'ca.wiki.valid.tokens']
  'ca-all': [
    'ca.wiki.test.tokens',
    'ca.wiki.train.tokens',
    'ca.wiki.valid.tokens']
}
```

### Data fields

Plain text

### Data splits

|                         | train  | validation | test |
|-------------------------|-------:|-----------:|-----:|
| ca-2                    |10.64MB |1.07MB      |1.06MB|
| ca-100                  |528.96MB|1.07MB      |1.06MB|
| ca-all                  |1.32GB  |1.07MB      |1.06MB|
