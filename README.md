# Pytorch_BERT_Text_Classification
It is a repository to store text classification code with BERT and BERT-related pertained models.
<br></br>

## BERT Description

BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained model developed by Google. With BERT, we could complete a wide range of tasks in NLP by fine-tuning the pretrained model, such as question answering, language inference text classification and etc. 

This repository mainly focuses on the text classification task with BERT and BERT-related pretrained models, like RoBERTa and etc. 

For further reading about BERT, you could refer to this paper:
> Devlin J, Chang M W, Lee K, et al. Bert: Pre-training of deep bidirectional transformers for language understanding[J]. arXiv preprint arXiv:1810.04805, 2018.

<br></br>

## Dataset Description

Aiming to implement a text classification task with BERT, I chose the `Yelp polarity dataset` with `text` and `label` and treated the task as a sentiment classification problem. 

For the limitation of file size uploaded on Github, you could download the dataset via link by yourself:

- From Kaggle: https://www.kaggle.com/irustandi/yelp-review-polarity/version/1
- From Yelp's official website: https://www.yelp.com/dataset/download

**Please Notice**: 

- After downloading the `Yelp polarity dataset`, you could rename the directory's name to `yelp_review_polarity_csv` or modified the dataset path in `BERT_Text_Classification_CPU.ipynb`. Otherwise, it would pop up `FileNotFoundError`.
- For convenience, I recommended you could download the dataset from the link provided with Kaggle and put the dataset under the directory.

<br></br>

## Code Description

### 1. BERT_Text_Classification_CPU.ipynb

It is a text classification task implementation in Pytorch and transformers (by HuggingFace) with BERT. It contains several parts:

- Data pre-processing
- BERT tokenization and input formating
- Train with BERT
- Evaluation
- Save and load saved model

If you have any questions about the code, please feel free to issue or email me. 
<br></br>

## License
```
MIT License

Copyright (c) 2020 icmpnorequest

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
