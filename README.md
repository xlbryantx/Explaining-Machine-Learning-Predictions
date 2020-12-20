# Explaining Machine Learning Predictions
Book: [Interpretable Machine Learning][1]
>## 1. Local Explanations
>>### 1.1 Feature Importance
>>>  * [ ] LIME-``Why Should I Trust You?" Explaining the Predictions of Any Classifier 

>>>  * [ ] SHAP-A Unified Approach to Interpreting Model Predictions
>>### 1.2 Rule Based
>>>  * [ ] Anchors: High-Precision Model-Agnostic Explanations   
>>### 1.3 Saliency Maps
>>>  * [ ] How to Explain Individual Classification Decisions   
>>>  * [ ] Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps 
>>>  * [ ] SmoothGrad: removing noise by adding noise   
>>>  * [ ] Axiomatic Attribution for Deep Networks 
>>>  * [ ] Towards better understanding of gradient-based attribution methods for Deep Neural Networks   
>>>  * [ ] Contextual Prediction Difference Analysis for Explaining Individual Image Classifications 
>>>  * [ ] Learning important features through propagating activation differences   
>>>  * [ ] Learning Deep Features for Discriminative Localization   
>>### 1.4 Prototypes/Example Based
>>>  * [ ] Examples are not enough, learn to criticize! Criticism for Interpretability 
>>>  * [ ] Representer Point Selection for Explaining Deep Neural Networks 
>>>  * [ ] Evaluating Explanations: How much do explanations from the teacher aid students? 
>>### 1.5 Counterfactuals
>>>  * [ ] Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR 
>>>  * [ ] Interpretable Counterfactual Explanations Guided by Prototypes 
>>>  * [ ] Explaining machine learning classifiers through diverse counterfactual explanations 
>>>  * [ ] Model-agnostic counterfactual explanations for consequential decisions 
>## 2. Global Explanations
>>### 2.1 Collection of Local Explanations
>>>  * [ ] SP-LIME-``Why Should I Trust You?" Explaining the Predictions of Any Classifier
>>### 2.2 Representation Based
>>>  * [ ] Network Dissection: Quantifying Interpretability of Deep Visual Representations
>>>  * [ ] Compositional Explanations of Neurons
>>>  * [ ] Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)
>>### 2.3 Model Distillation
>>>  * [ ] Learning Global Additive Explanations for Neutal Nets Using Model Distillation 
>>>  * [ ] Interpreting Blackbox Models via Model Extraction
>>>  * [ ] Faithful and Customizable Explanations of Black Box Models
>>### 2.4 Summaries of Counterfactuals
>>>  * [ ]  Beyond Individualized Recourse: Interpretable and Interactive Summaries of Actionable Recourses 
>## 3. Explanations in Different Modalities
>>### 3.1 Explanations in Structured Data
>>>  * [ ] Matthews 2019 (didnt find)
>>>  * [ ] Understanding Black-box Predictions via Influence Functions (Prototype based explantions)
>>>  * [ ] INTERPRETABLE CLASSIFIERS USING RULES AND BAYESIAN ANALYSIS: BUILDING A BETTER STROKE PREDICTION MODEL 
(Rule based)
>>>  * [ ] Interpretable Decision Sets: A Joint Framework for Description and Prediction (Rule based)
>>>  * [ ] Avoiding Disparate Impact with Counterfactual Distributions (Counterfactual)
>>### 3.2 Explanations in CV 
>>>  * [ ] None
>>### 3.3 Explanations in NLP
>>>  * [ ] Explaining Black Box Predictions and Unveiling Data Artifacts through Influence Functions (Prototypes)
>## 4. Evaluation of Explanations
>>### 4.1 Examples
>>>  * [ ] Towards A Rigorous Science of Interpretable Machine Learning
>>>  * [ ] An Evaluation of the Human-Interpretability of Explanation
>>### 4.2 Understand the Explanations' Behavior
>>>  * [ ] Visualizing Deep Networks by Optimizing with Integrated Gradients
>>>  * [ ] Data Shapley: Equitable Valuation of Data for Machine Learning
>>>  * [ ] Evaluating Explainable AI: Which Algorithmic Explanations Help Users Predict Model Behavior?
>>>  * [ ] Manipulating and Measuring Model Interpretability
>>### 4.3 How to Use the Explanations for Debugging
>>>  * [ ] “Why Should I Trust You?” Explaining the Predictions of Any Classifier
>>>  * [ ] FIND: Human-in-the-Loop Debugging Deep Text Classifiers
>>>  * [ ] Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications
>>### 4.4 Help Make Decisions
>>>  * [ ] On Human Predictions with Explanations and Predictions of Machine Learning Models: A Case Study on Deception Detection
>>>  * [ ] Teaching Categories to Human Learners with Visual Explanations
>## 5. Limitations of Post-Hoc Explainability
>>### 5.1 Faithfulness / Fidelity (explanations do not reflect the underlying model)
>>>  * [ ] LOCAL EXPLANATION METHODS FOR DEEP NEURAL NETWORKS LACK SENSITIVITY TO PARAMETER VALUES
>>>  * [ ] When Explanations Lie: Why Many Modified BP Attributions Fail
>>### 5.2 Fragility (explanations can be easily manipulated)
>>>  * [ ] Explanations can be manipulated and geometry is to blame
>>>  * [ ] Fooling LIME and SHAP: Adversarial Attacks on Post hoc Explanation Methods
>>>  * [ ] Interpretation of Neural Networks is Fragile
>>>  * [ ] Fairwashing Explanations with Off-Manifold Detergent (Against manipulation)
>>### 5.3 Stability (change in input casuse large changes in explanations)
>>>  * [ ] On the Robustness of Interpretability Methods
>>>  * [ ] On the (In)fidelity and Sensitivity for Explanations
>>>  * [ ] SAM: The Sensitivity of Attribution Methods to Hyperparameters
>>### 5.3 Usefulness
>>>  * [ ] Semantically Equivalent Adversarial Rules for Debugging NLP Models 
>>>  * [ ]  Interpretations are Useful: Penalizing Explanations to Align Neural Networks with Prior Knowledge

[1]:https://christophm.github.io/interpretable-ml-book/example-based.html






<!-- 1. Build inherently interpretable predictive models (e.g. Linear models, Decision Trees)

It certain settins, accuracy-interpretability trade offs may exist.
 
2. Explain pre-built models in a post-hoc manner (e.g. LIME, Teacher-student)


If you can build an interpretable model which is also adequately accurate for your setting, DI IT!


Otherwise, post hoc explanations come to the rescure!


What is an Explanation?

Defination: Interpretable description of the model behavior
Faithful: 
 :

Global explanation may be too complicated 
Defination: Interpretable description of the model behavior in a target neighborhood


Local Explanations vs. Global explanations
1. Explain individual predictions                                                 vs      explain complete behavior of the model 
2. Help unearth biases in the local neighborhood of a given instance              vs      Help shed light on big picture biases affeting larger subgroups
3. Help vet if individual predictions are being made for the right reasons        vs      Help vet if the model, at a high level, is suitable for deployment.


Feature Importances:
    LIME:
    SHAP:Shapley Values as Importabce 

Relu based:
     Anchors: Sufficient Conditions -->
