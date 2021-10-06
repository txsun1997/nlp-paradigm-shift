# Paradigm Shift in NLP

Welcome to the webpage for "[Paradigm Shift in Natural Language Processing](https://txsun1997.github.io/papers/paradigm_shift.pdf)". Some resources of the paper are constantly maintained here, such as a full list of papers of paradigm shift, an interactive [Sankey diagram](https://txsun1997.github.io/nlp-paradigm-shift/sankey.html) to depict the trend of paradigm shift, etc.

What is paradigm shift?

First of all, what is paradigm, and what is paradigm shift? 

**Paradigm** is the general framework to model a class of tasks. For example, sequence labeling (SeqLab) is a popular paradigm to solve named entity recognition (NER). We summarize the mainstream paradigms that are widely used for common NLP tasks as: *Class*, *Matching*, *SeqLab*, *MRC*, *Seq2Seq*, *Seq2ASeq*, *(M)LM*. 

**Paradigm shift** is a phenomena of solving a task that is usually solved with some paradigm with another paradigm. For example, [Li et al. (2020)](https://www.aclweb.org/anthology/2020.acl-main.519) uses the *MRC* paradigm to solve NER, which is previously solved with *SeqLab*, then we can say that the paradigm of NER shifted from *SeqLab* to *MRC*.

The figure below shows the observed shift (or transfer) of the seven paradigms in recent years.



<img src="https://txsun1997.github.io/nlp-paradigm-shift/paradigm_shift.png" style="zoom:48%;" />

## Paradigm shift in NLP tasks

We collect the papers of paradigm shift in the table below, which is an extension of the Table 1 in our original paper. This table will be constantly updated.

| **Task**    | **Class**                                                    | **Matching**                                                 | **SeqLab**                                                   | **MRC**                                                      | **Seq2Seq**                                                  | **Seq2ASeq**                                                 | **(M)LM**                                                    |
| :---------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **TC**      | [Kim 2014](https://aclanthology.org/D14-1181/); <br>[Liu et al. 2016](https://www.ijcai.org/Abstract/16/408); <br>[Devlin et al. 2019](https://aclanthology.org/N19-1423/) | [Chai et al. 2020](http://proceedings.mlr.press/v119/chai20a.html);<br>[Yin et al. 2020](https://www.aclweb.org/anthology/2020.emnlp-main.660); <br>[Wang et al. 2021](https://arxiv.org/abs/2104.14690); |                                                              |                                                              | [Yang et al. 2018](https://aclanthology.org/C18-1330/)       |                                                              | [Brown et al. 2020](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html); <br>[Schick&Schutze 2021](https://aclanthology.org/2021.eacl-main.20/); <br>[Schick&Schutze 2021](https://www.aclweb.org/anthology/2021.naacl-main.185); <br>[Gao et al. 2021](https://aclanthology.org/2021.acl-long.295/) |
| **NLI**     | [Devlin et al. 2019](https://aclanthology.org/N19-1423/)     | [Chen et al. 2017](http://aclweb.org/anthology/P17-1152)     |                                                              |                                                              | [McCann et al. 2018](http://arxiv.org/abs/1806.08730)        |                                                              | [Schick&Schutze 2021](https://aclanthology.org/2021.eacl-main.20/); <br>[Schick&Schutze 2021](https://www.aclweb.org/anthology/2021.naacl-main.185); <br>[Gao et al. 2021](https://aclanthology.org/2021.acl-long.295/) |
| **NER**     | [Xia et al. 2019](https://www.aclweb.org/anthology/P19-1138); <br>[Fisher&Vlachos 2019](https://www.aclweb.org/anthology/P19-1585); <br>[Yu et al. 2020](https://www.aclweb.org/anthology/2020.acl-main.577); <br>[Fu et al. 2021](https://aclanthology.org/2021.acl-long.558/) |                                                              | [Ma&Hovy 2016](https://aclanthology.org/P16-1101/); <br>[Lample 2016](http://aclweb.org/anthology/N16-1030) | [Li et al. 2020](https://www.aclweb.org/anthology/2020.acl-main.519) | [Yan et al. 2021](https://aclanthology.org/2021.acl-long.451/) | [Lample et al. 2016](http://aclweb.org/anthology/N16-1030); <br>[Dai et al. 2020](https://www.aclweb.org/anthology/2020.acl-main.520) | [Ma et al. 2021](https://arxiv.org/abs/2109.13532)           |
| **ABSA**    | [Wang et al. 2016](https://aclanthology.org/D16-1058/)       | [Sun et al. 2019](https://aclanthology.org/N19-1035/)        |                                                              | [Mao et al. 2021](https://ojs.aaai.org/index.php/AAAI/article/view/17597)<br>[Chen et al. 2021](https://ojs.aaai.org/index.php/AAAI/article/view/17500) | [Yan et al. 2021](https://aclanthology.org/2021.acl-long.188/);<br/>[Zhang et al. 2021](https://aclanthology.org/2021.acl-short.64.pdf) |                                                              | [Li et al. 2021](https://arxiv.org/abs/2109.08306)           |
| **RE**      | [Zeng et al. 2014](https://aclanthology.org/C14-1220/)       |                                                              |                                                              | [Levy et al. 2017](https://aclanthology.org/K17-1034/); <br>[Li et al. 2019](https://aclanthology.org/P19-1129/); <br>[Zhao et al. 2020](https://www.ijcai.org/proceedings/2020/546) | [Zeng et al. 2018](https://aclanthology.org/P18-1047/)       |                                                              | [Han et al. 2021](https://arxiv.org/abs/2105.11259)          |
| **Summ**    |                                                              | [Zhong et al. 2020](https://aclanthology.org/2020.acl-main.552/) | [Cheng&Lapata 2016](https://aclanthology.org/P16-1046/)      |                                                              | [McCann et al. 2018](http://arxiv.org/abs/1806.08730)        |                                                              | [Aghajanyan et al. 2021](https://arxiv.org/abs/2107.06955)   |
| **Parsing** |                                                              |                                                              | [Rodríguez&Vilares 2018](https://aclanthology.org/D18-1162/); <br>[Strzyz et al. 2019](https://aclanthology.org/N19-1077/); <br>[Vilares&Rodríguez 2020](https://aclanthology.org/2020.emnlp-main.221/); <br>[Vacareanu et al. 2020](https://aclanthology.org/2020.lrec-1.643/); | [Gan et al. 2021](https://arxiv.org/abs/2105.07654)          | [Vinyals et al. 2015](https://proceedings.neurips.cc/paper/2015/hash/277281aada22045c03945dcb2ca6f2ec-Abstract.html); <br>[Li et al. 2018](https://aclanthology.org/C18-1271/);  <br>[Rongali et al. 2020](https://dl.acm.org/doi/10.1145/3366423.3380064) | [Chen et al. 2014](https://aclanthology.org/D14-1082/); <br>[Dyer et al. 2015](https://aclanthology.org/P15-1033/); | [Choe&Charniak 2016](https://aclanthology.org/D16-1257/)     |

## Trends 

To intuitively depict the trend of paradigm shift in NLP, we also draw an interactive [Sankey diagram](https://txsun1997.github.io/nlp-paradigm-shift/sankey.html), which is an extension of the Figure 2 in our original paper. Also, this diagram is constantly updated as the table above changed.

## Contributing

This line of research is difficult to be comprehensively surveyed, so welcome any additions, modifications, and suggestions! Please feel free to submit pull request or directly contact [me](https://txsun1997.github.io/).

## Citation

If you find this webpage or the paper helpful to your research, please cite our paper:

```bibtex
@article{sun2021paradigmshift,
  title={Paradigm Shift in Natural Language Processing}, 
  author={Tianxiang Sun and Xiangyang Liu and Xipeng Qiu and Xuanjing Huang},
  journal={arXiv preprint arXiv:2109.12575},
  year={2021}
}
```

