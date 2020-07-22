# Deep Learning Papers Survey
Personal repository to track my paper surveys. Based on [Yagami360/MachineLearning-Papers_Survey](https://github.com/Yagami360/MachineLearning-Papers_Survey).

Each paper summary is under Issues. 
- Unstarted papers are labeled [TODO](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues?q=is%3Aissue+label%3ATODO). 
- Started papers are labeled [in progress](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues?q=+is%3Aissue+label%3A%22in+progress%22). Not all papers need to be read in depth and will thus under this label.
- Nearly finished papers are labeled [almost done](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues?q=label%3A%22almost+done%22). Most of my "finished" papers will end up here because I may want to add more in the future.
- 100% finished papers are under [Closed](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues?q=is%3Aissue+is%3Aclosed).

I'll only list nearly or 100% finished papers in this document.

## ■ Deep Learning Papers
### ◎ General Deep Learning
- TODO

### ◎ Vision
- TODO

### ◎ Generative Graphics
#### Semantic Image Synthesis
- [[GauGAN/SPADE] Semantic Image Synthesis with Spatially-Adaptive Normalization - Park et al. 2019 CVPR](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues/12)
- [[SMIS] Semantically Multi-modal Image Synthesis - Zhu et al. 2020](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues/7)

#### Latent Space Exploration
- [[SeFa] Closed-Form Factorization of Latent Semantics in GANs - Shen and Zhou 2020](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues/21)

#### Metrics
- [The Unreasonable Effectiveness of Deep Features as a Perceptual Metric - Zhang et al. 2018 CVPR](https://github.com/andrewjong/Deep-Learning-Paper-Surveys/issues/5)

### ◎ Reinforcement Learning
- TODO 
#### Model Free
#### Model Based
#### Learning from Demonstrations

### ◎ Natural Language Processing
- TODO

## ■ Other Papers
- TODO: Maybe I'll survey papers from other fields.

## ■ How to read and research papers on machine learning
 - Paper survey
     - The easiest way to find an advanced version of the paper is to find the cited paper on Google Scholer.
     -Basically, the ones with the highest number of citations are the ones of interest. However, the latest papers will of course have fewer citations.
     - Basically, the latest papers give better experimental results, so look for the latest published date on Google Scholar as much as possible.
     - If there is no official implementation of the paper, the cost of reproducing the original implementation is high, so we preferentially search for one with an official implementation.
     - Check PapersWithCode to see if the paper is officially implemented.

- How to read a dissertation
    - Basically, it is efficient to read "Abstract"-> "Introduction"-> "Conclusion"-> "Details of what you did"-> "Experiments"-> "Related Work". Related Work can be skipped at worst.
    - Notice the words "In this paper ..." and "In this work ..." in the Abstract and Introduction, and the words "the contributions of this paper ... as follows." At the end of the Introduction.
    - Unresolved issues and problems in the paper are often described in Future work and Conculution in the paper. Or, it is often mentioned in the Related Work of the paper citing the paper.

## ■ Template for Paper Survey
```
## 0. Article Information and Links

- Paper's project website: 
- Release date: YYYY/MM/DD
- Number of citations (as of 2020/MM/DD): 

## 1. What do the authors try to accomplish?

## 2. What's great compared to previous research?

## 3. Where are the key elements of the technology and method?

## 4. How do the authors measure success?

## 5. How did _you_ verify that it works?

## 6. Things to discuss? (e.g. weaknesses, potential for future work, relation to other work)

## 7. Are there any papers to read next?

## 8. References

```

## ■ Reference site
### ◎ Paper site
- arXiv
- Google Scholer
### ◎ Convenient site
- PapersWithCode.com: check if a paper is implemented
- SemanticScholar.org: uses ML to cluster related papers
- ConnectedPapers.com: visualize a graph of related papers
- Hyper Collocation

### ◎ Other reference sites
- arXivTimes
- ymym3412/acl-papers
- shunk031/paper-survey
