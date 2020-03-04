# Deep generative models to counter class imbalance: a guided model selection strategy
Code Base By - (k173004 FAST NUCES Karachi).

## Datasets:

AML dataset: Anti-money laundering dataset comprises of SAR (suspicious activity report) and Non-SAR transactions of the individuals in a financial institution accumulated for the period of 1 year.
    
Home Credit Default dataset: Home credit default contain the transactional and repayment history of the customers which are provided loan with no credit history. (Ref: https://www.kaggle.com/c/home-credit-default-risk/data)
    
Credit card fraud dataset: This dataset contain the fraudulent and non-fraudulent credit card transactions of all the customers for a period of one month which are European credit card holders. (Ref: https://www.kaggle.com/mlg-ulb/creditcardfraud/version/3)

## Experiments: 

The experiments on each of the three datasetsare  categorized  into  3  types:   generative,  synthetic  and  hybrid  based  on  thesampling  technique  used.   Generative  over  sampling  is  one  of  artifacts  of  the proposed model in this study as explained in Fig.  3.  It uses three deep mod-els including Generative adversarial networks (GAN), Variational autoencoders(VAE) and Restricted Boltzmann Machines (RBM) for generating minority sam-ples. Performance of this is compared with synthetic oversampling counterparts.These are followed by two hybrid techniques namely traditional over/under sam-pling  and  chaining  generative  and  reductives.   The  former  uses  SMOTEENN while  the  later  conceived  as  Artifact  II  in  the  proposed  model  couples  VAE with Instance hardness threshold 

## Preprint: 
https://www.researchgate.net/publication/334720715_Deep_generative_models_to_counter_class_imbalance_a_guided_model_selection_strategy
