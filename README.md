# DeepYY1
## Abstract
The protein Yin Yang 1 (YY1) could form dimers that facilitate the interaction between active enhancers and promoter-proximal elements. YY1-mediated enhancer–promoter interaction is the general feature of mammalian gene control. Recently, some computational methods have been developed to characterize the interactions between DNA elements by elucidating important features of chromatin folding; however, no computational methods have been developed for identifying the YY1-mediated chromatin loops. In this study, we developed a deep learning algorithm named DeepYY1 based on word2vec to determine whether a pair of YY1 motifs would form a loop. The proposed models showed a high prediction performance (AUCs≥
0.93) on both training datasets and testing datasets in different cell types, demonstrating that DeepYY1 has an excellent performance in the identification of the YY1-mediated chromatin loops. Our study also suggested that sequences play an important role in the formation of YY1-mediated chromatin loops. Furthermore, we briefly discussed the distribution of the replication origin site in the loops. Finally, a user-friendly web server was established, and it can be freely accessed at http://lin-group.cn/server/DeepYY1.

## Required Package
DeepYY1 requires:
* Python3 (tested 3.5.4)
* numpy (tested 1.18.1)
* pandas (tested 1.0.1)
* gensim (tested 3.8.1)
* sklearn (tested 0.19.1)
* keras (tested 2.3.1)
* tensorflow (tested 1.2.1)
* jupyter (tested 1.0.0)
* scikit-learn (tested 0.22.1)


## Usage
generate feature set by 'word2vec.ipynb'
train model by 'CNN_model.ipynb'
load model by 'load_model.ipynb'

NOTE: For files with different input sequences, you need to pay attention to the modification of parameters in code.


