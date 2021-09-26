## Paradigm Shift in NLP

Welcome to the webpage for "[Paradigm Shift in Natural Language Processing](https://txsun1997.github.io/papers/paradigm_shift.pdf)". Some resources of the paper are constantly maintained here, such as a full list of papers of paradigm shift, an interactive Sankey diagram to depict the trend of paradigm shift, etc.

### What is paradigm shift?

First of all, what is paradigm, and what is paradigm shift? 

**Paradigm** is the general framework to model a class of tasks. For example, sequence labeling (SeqLab) is a popular paradigm to solve named entity recognition (NER). We summarize the mainstream paradigms that are widely used for common NLP tasks as: *Class*, *Matching*, *SeqLab*, *MRC*, *Seq2Seq*, *Seq2ASeq*, *(M)LM*. 

**Paradigm shift** is a phenomena of solving a task that is usually solved with some paradigm with another paradigm. For example, [Li et al. (2020)](https://www.aclweb.org/anthology/2020.acl-main.519) uses the *MRC* paradigm to solve NER, which is previously solved with *SeqLab*, then we can say that the paradigm of NER shifted from *SeqLab* to *MRC*.

The figure below shows the observed shift (or transfer) of the seven paradigms in recent years.



<img src="https://txsun1997.github.io/nlp-paradigm-shift/paradigm_shift.png" style="zoom:48%;" />

### Paradigm shift in NLP tasks

We collect the papers of paradigm shift in the table below, which is an extension of the Table 1 in our original paper. This table will be constantly updated.

| **Task**    | **Class**                                                | **Matching**                                                 | **SeqLab** | **MRC** | **Seq2Seq**                                            | **Seq2ASeq** | **(M)LM** |
| ----------- | -------------------------------------------------------- | ------------------------------------------------------------ | ---------- | ------- | ------------------------------------------------------ | ------------ | --------- |
| **TC**      | [Kim 2014](https://aclanthology.org/D14-1181/)           | [Chai et al. 2020](http://proceedings.mlr.press/v119/chai20a.html) |            |         | [Yang et al. 2018](https://aclanthology.org/C18-1330/) |              |           |
|             | [Liu et al. 2016](https://www.ijcai.org/Abstract/16/408) |                                                              |            |         |                                                        |              |           |
|             | [Devlin et al. 2019](https://aclanthology.org/N19-1423/) |                                                              |            |         |                                                        |              |           |
| **NLI**     |                                                          |                                                              |            |         |                                                        |              |           |
| **NER**     |                                                          |                                                              |            |         |                                                        |              |           |
| **ABSA**    |                                                          |                                                              |            |         |                                                        |              |           |
| **RE**      |                                                          |                                                              |            |         |                                                        |              |           |
| **Summ**    |                                                          |                                                              |            |         |                                                        |              |           |
| **Parsing** |                                                          |                                                              |            |         |                                                        |              |           |



See [Sankey Diagram](https://txsun1997.github.io/nlp-paradigm-shift/sankey.html).
