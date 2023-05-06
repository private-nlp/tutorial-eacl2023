# tutorial-eacl2023
EACL 2023 Tutorial on Privacy-preserving Natural Language Processing

## Preliminary schedule

### Block 1: Attacks (30 minutes)

####  Presenter: Sepideh Ghanavati

> This block will provide an overview why differential privacy is needed by introducing and discussing reconstruction attacks and examples of difference attacks. We will discuss how an algorithm can be blatantly non-private via an example from census data and explain inefficient and efficient attacks. We then discuss reconstruction attacks in practice for several cases. We conclude this block by briefly explaining some examples of tracing attacks.

* Slide deck [PDF](block-1/eacl2023-privacy-nlp-tutorial-1.pdf)

### Block 2a: Defence with formal guarantees (60 min)

#### Presenter: Ivan Habernal

> This block will introduce differential privacy, a mathematical framework for privacy protection. We will explain the typical setup (why this privacy approach has `differential' in its title) and the formal definitions. Then we will address some basic DP mechanisms and show their NLP applications. This part will involve a few mathematical proofs, but our aim is to make it low-barrier and accessible to a very broad audience.

* Slide deck [PDF](block-2a-1/pdf/eacl2023-privacy-nlp-tutorial-2a-1.pdf)
* [LaTeX sources under CC-BY-SA](block-2a-1/latex)
* Pre-recorded [YouTube video](https://www.youtube.com/watch?v=HCSqVwikv4U)

#### Presenter: Patricia Thaine

> In the second part, we will introduce some cryptographic tools, namely homomorphic encryption and secure multiparty computation. The main focus will be on introducing the basics of lattice-based cryptography and homomorphic encryption and the most popular schemes (BGV, CKKS). We will go over the available libraries (PALISADE, HElib, SEAL) and dive into an NLP-specific example. 

* Slide deck [PDF](block-2a-2/An%20Introduction%20to%20Homomorphic%20Encryption.pdf)
* Slide deck [PPTX](block-2a-2/An%20Introduction%20to%20Homomorphic%20Encryption%20for%20Computational%20Linguists.pptx)


### Block 2b: Defences without formal guarantees (20 min)

#### Presenter: Fatemeh Mireshghallah

> Apart from privacy-preserving schemes that directly optimize for a given definition of privacy, there are given execution models and environments that help enhance privacy and are not by themselves privacy-preserving in a formal sense. This block will introduce privacy-enhancing methods such as federated learning, split learning and regularizer-based methods. Federated learning and split learning are both based on distributed learning and are great methods for application in enterprise and clinical setups. Regularizer based and private representation learning methods add extra terms to the loss function to limit the memorization and encoding of sensitive data within the model. 

* Slide deck [PPTX](block-2b/eacl-tutorial.pptx)

### Block 3: Privacy in industry (40 min)

> Companies have practical constraints when deploying privacy preserving technologies. Some of these include deployment and computation at scale, or guarantees that solutions meet compliance or regulatory requirements. There is also the trade-off between privacy, utility, bias, fairness,~\cite{farrand2020neither} as well as explainability and verifiability of the implemented solutions. In this section, we will dive deep into different technologies and discuss their trade-offs from an industry perspective. We will also highlight how the community can help accelerate progress along different dimensions.
