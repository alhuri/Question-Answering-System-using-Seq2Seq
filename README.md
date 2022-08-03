# Question-Answering-System-using-Seq2Seq-
The goal here is to create a Baseline Question Answering System utilizing the seq2seq method using both versions of SQuAD Found [here](https://rajpurkar.github.io/SQuAD-explorer/). The main difference between the two datasets is that SQuAD v2 also considers samples where the questions have no answer in the given paragraph. This baseline approach get low results due to the problem of “Greedy decoding” while it also suffers from bottleneck problem, gets answers out of span, and there is no way to go back in the gererated sequance because of used architecture.





