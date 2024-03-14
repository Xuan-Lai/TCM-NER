# TCM-NER
The source code of the paper:
Qing Ye, Xuan Lai, Chunlei Cheng. Named entity recognition for traditional Chinese medicine with lexical enhancement and span method.
## Environment Requirement
    torch==1.7.1 
    numpy==1.19.5 
    transformers==4.26.1 
    FastNLP==0.5.0
## The Pretrained character embeddings and word embeddings
* Character embeddings: [gigaword_chn.all.a2b.uni.ite50.vec](https://drive.google.com/file/d/1_Zlf0OAZKVdydk7loUpkzD2KPEotUE8u/view)
* Bi-gram embeddings: [gigaword_chn.all.a2b.bi.ite50.vec](https://pan.baidu.com/s/1pLO6T9D#list/path=%2F)
## The Pretrained model Chinese-BERT-wwm for embedding layer
[Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm)
## Acknowledgements
* The [FLAT model](https://github.com/LeeSureman/Flat-Lattice-Transformer) source code.
* The paper of FLAT model: Li X, Yan H, Qiu X, Huang X. J. 2020. FLAT: Chinese NER Using Flat-Lattice Transformer. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 6836-6842
* The detials about [FastNLP](https://github.com/fastnlp/fastNLP)
