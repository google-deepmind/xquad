This directory contains the Cross-lingual Question Answering Dataset (XQuAD), described in the following paper (https://arxiv.org/abs/1910.11856):

Mikel Artetxe, Sebastian Ruder, and Dani Yogatama. (2019). On the cross-lingual transferability of monolingual representations. arXiv 1910.11856.

The dataset consists of a subset of 240 context paragraphs and 1,190 question-answer pairs from the development set of SQuAD v1.1 (Rajpurkar et al., 2016) together with their translations into 10 languages: Spanish, German, Greek, Russian, Turkish, Arabic, Vietnamese, Thai, Chinese, and Hindi. 
Please refer to the paper for a detailed description of how the dataset was created.

The files are in JSON format and contain the same fields as the original SQuAD 1.1 dataset described in the following paper:

Pranav Rajpurkar, Jian Zhang, Konstantin Lopyrev, and Percy Liang. (2016). SQuAD: 100,000+ Questions for Machine Comprehension of Text. In Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing.

The original SQuAD 1.1 dataset can be downloaded from https://github.com/rajpurkar/SQuAD-explorer/tree/master/dataset

This directory contains the following files:
- Arabic: xquad.ar.json
- German: xquad.de.json
- Greek: xquad.el.json
- English: xquad.en.json
- Spanish: xquad.es.json
- Hindi: xquad.hi.json
- Russian: xquad.ru.json
- Thai: xquad.th.json
- Turkish: xquad.tr.json
- Vietnamese: xquad.vi.json
- Chinese: xquad.zh.json

This dataset is distributed under the CC BY-SA 4.0 license (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

This is not an officially supported Google product.

If you use this dataset, please cite:

```
@article{Artetxe:etal:2019,
      author    = {Mikel Artetxe and Sebastian Ruder and Dani Yogatama},
      title     = {On the cross-lingual transferability of monolingual representations},
      journal   = {CoRR},
      volume    = {abs/1910.11856},
      year      = {2019},
      archivePrefix = {arXiv},
      eprint    = {1910.11856}
}
```
