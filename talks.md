
## The book of Why 
**Beate Sick (UZH)**

Abstract:

This talk discusses parts of the “The book of Why” by Judea Pearl and Dana Mackenzie. 
the book was discussed in the [New York Times](https://www.nytimes.com/2018/06/01/business/dealbook/review-the-book-of-why-examines-the-science-of-cause-and-effect.html) 
and on [ML Reddit](http://www.inference.vc/untitled/) and also in a 
[science podcast (last third)](http://www.sciencemag.org/podcast/science-and-nature-get-their-social-science-studies-replicated-or-not-mechanisms-behind)
The reading of the book inspired me a lot and brought me to reflect on typical pitfalls and the limitations of statistics 
and machine learning and the great potentials of incorporating causal graphical using the language of Bayesian Networks. 
I will use examples from the book to point out that intervention planning and the search for causal relationships with observational data
requires the usage of graphical causal models.

## Effects of client-counselor matching on counseling and motivating unemployed clients

**Julia Casutt**

In my contribution, I want to investigate the impact of client-counsellor matching in the framework 
of counselling unemployed people at the local unemployment agencies in Switzerland 
(Regionale Arbeitsvermittlungszentren RAV). I'm interested in whether certain matching constellations 
(e.g. female counsellors/female clients, client and counsellor are in the same age-group etc.) affect the 
job search outcomes and reduce the duration of unemployment. My database consists of about 60000 unemployment 
cases from 2016, where I have information on socio-economic characteristics and other variables for both 
counsellor and client as well as information on outcome and duration of the job search. 
For my research I want to apply causal inference methods in order to derive well-founded recommendations for my work.


## Bayesian networks meet observational data
**Gilles Kratzer (UZH)**

Abstract:

Bayesian Networks are types of graphical models that are useful to model high dimensional and strongly correlated data in a causal or acausal perspective. They have an impressive track record list of successful applications to real-world data. Bayesian networks are used for modelling beliefs in a wide range of domains such as social sciences, veterinary epidemiology, decisions support system or bioinformatics. The purpose of this talk is to present a short overview of the comprehensive methodology using an R package called abn. To introduce large classes of algorithms used in practice to learn the structures. To discuss performance and practical usability of approximate or exact inference frameworks. In an applied perspective and in Bayesian Network context, researchers often struggle to select a moderate number of variables. Indeed the class of problem where Bayesian Networks are proficient implies typically not a unique outcome-type formulation. Consequently, classical variable selection methods based on predictive power often fail to select significant variables when related to multiple outcomes. A possible alternative, based on a general implementation of the minimum redundancy maximum relevance model, will be presented using the varrank R package. Possible synergies between those methodologies will be highlighted using real-world data.


## Comparing covariate adjustment in interventional and observational studies 
**Markus Kalisch (ETH)**

Abstract:

Covariate adjustment is a popular tool for trying to estimat causal effects from interventional and observational data. We sketch both fields of application and comment on recent research on the validity of covariate adjustment sets.

## Methods to estimate personalised treatment effects in observational data
**Daniela Buchwald (LMU)**

Abstract:

The propensity score is commonly used for adjustment in causal inference. Methods include Inverse Probability of Treatment Weighting (IPTW) – where observations are weighted according to the probability of receiving the treatment–, Matching – a method for data preprocessing with the goal to reduce imbalance between the treated and control group–, Stratification, and Including the propensity score as a covariate. These methods can be used in different contexts, for example when estimating personalised treatment effects. In this presentation we will discuss propensity score adjustment and show examples how to use them for personalised medicine.

## Challenges of intervention planning in an ongoing project with observational MS patient data
**Heidi Seibold (LMU)**

Abstract:

For the multiple sclerosis use-case in DIFUTURE project we want to determine which patients should receive which treatment. The database at hand stems from clinical practice and comes with various challenges. In this talk I will present the project, challenges and possible solutions and hope to get some input from the participants on how to overcome the challenges.

## Interpretable Machine Learning
**Christoph Molnar (LMU)**

Abstract:

Machine learning has great potential for improving products, processes and research. But machine learning models usually don’t explain their predictions, which is an obstacle to the application of machine learning. This presentation gives an overview of methods and models to make machine learning more interpretable.

