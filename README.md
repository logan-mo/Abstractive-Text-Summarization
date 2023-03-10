# Abstractive-Text-Summarization

An abstractive text summarization model based on the seq2seq transformer architecture, that beats PreTrained BERT Summarizer with respect to Rogue Scores.

It uses the CNN_DailyMail Dataset for training.

**Pre-Trained BERT**
| ****  | Rogue-1              | Rogue-2  | Rogue-L  |
|:-----:|:--------------------:|:--------:|:--------:|
| **r** | 0.253672             | 0.088063 | 0.230165 |
| **p** | 0.398178             | 0.142948 | 0.361394 |
| **f** | 0.297954             | 0.103405 | 0.27031  |

**Our Seq2Seq Transformer**
| ****  | Rogue-1                     | Rogue-2  | Rogue-L  |
|:-----:|:---------------------------:|:--------:|:--------:|
| **r** | 0.3818                      | 0.161194 | 0.362263 |
| **p** | 0.378692                    | 0.17094  | 0.359935 |
| **f** | 0.370184                    | 0.160745 | 0.351657 |