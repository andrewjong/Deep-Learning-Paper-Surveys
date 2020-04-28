# Deep Learning Papers Survey
Personal repository to track my paper surveys.

Each paper summary is under Issues. Progress is managed on the Projects page.

## ■ Deep Learning Papers
### ◎ General Deep Learning
- Activation Functions
  - Swish

- Batch Size

- Learning Rate

### ◎ Vision
- Hand-Designed Architectures
  - Accuracy
    - ?
  - Mobile Efficiency
    - MobileNetV1
    - MobileNetV2
    - GhostNet

- Neural Architecture Search
  - MNasNet
  - Searching for MobileNetV3
  - EfficientNets
  - Designing Network Design Spaces
  - FBNet
  
- Data Augmentation
  - AutoAugment
  - Fast AutoAugment
  - AdvProp [TODO]
  
- Camera Pipeline
  - Deep Demosaicing for Edge Implementation

### ◎ Generative Graphics
- Architectures
  - DCGAN
  - StyleGAN
  - MSG-GAN
  - StyleGAN2
  
- Loss Functions
  - WGAN
  - WGAN-GP
  - Mescheder R1/R2
  - Implicit Competitive Regularization
  
- Systems
  - Pix2Pix
  - CycleGAN

- Applications
  - Virtual Try-on
    - FW-GAN

### ◎ Reinforcement Learning
- Algorithms
  - Q-Learning [TODO]
  - PPO [TODO]
  
  - World Models [TODO]
  
### ◎ Natural Language Processing
- Architectures
  - Attention is All You Need (Transformers)
  - BERT

## ■ Other Papers
Maybe I'll survey papers from other fields.

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

- Paper link: 
- Release date: YYYY/MM/DD
- Number of citations (as of 2020/MM/DD): 
- Implementation code: 
- Supplemental links (e.g. results): 
- Publication: Conference YYYY


## 1. What do the authors try to accomplish?

## 2. What's great compared to previous research?

## 3. Where are the key elements of the technology and method?

## 4. How did you verify that it works?

## 5. Things to discuss? (e.g. weaknesses, potential for future work, relation to other work)

## 6. Are there any papers to read next?

## 7. References

```

## ■ Reference site
### ◎ Paper site
arXiv
Google Scholer
### ◎ Convenient site
- papers with code
    - You can check if the paper is implemented.
- Hyper Collocation
- arXiv Vanity
### ◎ Other reference sites
- arXivTimes
- ymym3412/acl-papers
- shunk031/paper-survey
