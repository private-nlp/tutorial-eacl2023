# tutorial-eacl2023
EACL 2023 Tutorial on Privacy-preserving Natural Language Processing

## Preliminary schedule

### Block 1: Attacks (30 minutes)

> This block will provide an overview why differential privacy is needed by introducing and discussing reconstruction attacks and examples of difference attacks \citep{Dinur-Nissim2003}. We will discuss how an algorithm can be blatantly non-private via an example from census data and explain inefficient and efficient attacks. We then discuss reconstruction attacks in practice for several cases \citep{Cohen2020LinearPR}. We conclude this block by briefly explaining some examples of tracing attacks \citep{Homer2008} and \citep{Dwork2015}.


### Block 2a: Defence with formal guarantees (60 min)

> This block will introduce differential privacy, a mathematical framework for privacy protection \citep{Dwork.Roth.2013}. We will explain the typical setup (why this privacy approach has `differential' in its title) and the formal definitions. Then we will address some basic DP mechanisms and show their NLP applications. This part will involve a few mathematical proofs, but our aim is to make it low-barrier and accessible to a very broad audience.

> In the second part, we will introduce some cryptographic tools, namely homomorphic encryption and secure multiparty computation. The main focus will be on introducing the basics of lattice-based cryptography and homomorphic encryption and the most popular schemes (BGV, CKKS). We will go over the available libraries (PALISADE, HElib, SEAL) and dive into an NLP-specific example. 

### Block 2b: Defences without formal guarantees (20 min)

> Apart from privacy-preserving schemes that directly optimize for a given definition of privacy, there are given execution models and environments that help enhance privacy and are not by themselves privacy-preserving in a formal sense. This block will introduce privacy-enhancing methods such as federated learning~\cite{McMahan2017LearningDP}, split learning~\cite{Vepakomma2018SplitLF} and regularizer-based methods~\cite{coavoux-etal-2018-privacy,mireshghallahprivacy,Li2018TowardsRA}.

> Federated learning and split learning are both based on distributed learning and are great methods for application in enterprise and clinical setups. 
Regularizer based and private representation learning methods add extra terms to the loss function to limit the memorization and encoding of sensitive data within the model. 

### Block 3: Privacy in industry (40 min)

> Companies have practical constraints when deploying privacy preserving technologies. Some of these include deployment and computation at scale, or guarantees that solutions meet compliance or regulatory requirements. There is also the trade-off between privacy, utility, bias, fairness,~\cite{farrand2020neither} as well as explainability and verifiability of the implemented solutions. In this section, we will dive deep into different technologies and discuss their trade-offs from an industry perspective. We will also highlight how the community can help accelerate progress along different dimensions. 

### Block 4: Open problems in privacy in NLP (30 min)

> We will talks some further NLP specifics, such as (1) perturbing long-form text with differential privacy without losing the content, 
and (2) introducing better auditing methods for measuring memorization in discriminative and generative large language models (BERT or GPT based models).

