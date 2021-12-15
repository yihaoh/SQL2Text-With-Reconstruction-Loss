# Learning SQL-to-text with Graph-to-sequence Model
## Code Contributor: Yihao Hu

#### Description:
* Basic Pytorch dependency
* Tested on Pytorch 1.10, Python 3.7 
* No preprocessed data needed. For convenience, graph data is parsed on the fly. 
* Please expect that the training time to be 8-15 minutes per epoch given batch size 64.

* How to replicate our proejct: <br />
      - Graph2Seq model: SQL2Text-graph2seq.ipynb <br />
      - Open the file in Colab, run all code blocks in sequential order.
      - Copy the content in opt.txt to the Graph2Seq Model Setting code block in the ipynb file. <br />
      - A pretrained model state corresponding to the setting in opt.txt is available for download [here](https://drive.google.com/file/d/1gmkPxmbBvRN0jVUBUpsYHQkZI5mdkZSh/view?usp=sharing). This is for graph2seq model only, and it does not contain the seq2seq model which is used for reconstruction loss. <br />

##### Thanks to the following repositories: 
- Graph2Seq model repo: https://github.com/graph4ai/graph4nlp
- Graph2Seq model documentation: https://graph4ai.github.io/graph4nlp/

##### Note:
- The readability of code and documentation in the above GitHub repo is low. Going forward, we are likely to create our own graph2seq library for the purpose of readability and flexibility.
