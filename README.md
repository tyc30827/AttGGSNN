# AttGGSNN
AttGGSNN is an attention-based gated graph sequence neural network, which is built in an end-to-end model to formulate a VQA-like system.

### The example of our input data and target is showed below.
![image](https://github.com/tyc30827/AttGGSNN/blob/master/Example.PNG)
V means the multiple time-series sequences for all during a period of time before the predicted timestamp.

Q means the question of "Pairwise" companies.

A means the answer of the question we set.

Noted that this is a QA-like system, where the questions are embedded according to the keywords instead of the whole sentence.

### The `System Overview` of my model is showed below.
![image](https://github.com/tyc30827/AttGGSNN/blob/master/SystemOverview_AttGGSNN.PNG)

Readme.docx is a document written in Chinese, and it shows how to run the codes.

This is the programs of my thesis for Master of Science in Information Management in National Chiao Tung University.
The format of citation is : `Wei-Chia Huang (2019). "A Question Answering System for Financial Time-Series Correlation Based on Improved Gated Graph Sequence Neural Network with Attention Mechanism". Master's Thesis of Institute of Information Management, Hsinchu: National Chiao Tung University. Retrieved from https://hdl.handle.net/11296/hu4b8r.`

`AttGGSNN_1DConv.ipynb` is the main version of my work, which implement my proposed method.

`RelationNetwork_Benchmark.ipynb` is the benchmark model for my proposed model - Attention based GGSNN.

`Rule-based_PairsTrading.ipynb` shows you how I operate the experiment used for simulating the real world case. And it's a rule-based pairs-trading, a market neutral strategy aims to do statistical arbitrage.
