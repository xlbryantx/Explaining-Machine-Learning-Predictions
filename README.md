# Explaining Machine Learning Predictions
Book: [Interpretable Machine Learning][1]
>## 1. Local Explanations
>>### 1.1 Feature Importance
>>>  * [ ] LIME-``Why Should I Trust You?" Explaining the Predictions of Any Classifier 
>>>  <p><input type="checkbox"/>LIME-``Why Should I Trust You?" Explaining the Predictions of Any Classifier</p>  
>>>  <p><input type="checkbox"/>SHAP-A Unified Approach to Interpreting Model Predictions</p>  
>>### 1.2 Rule Based
>>>  <p><input type="checkbox"/>Anchors: High-Precision Model-Agnostic Explanations</p>  
>>### 1.3 Saliency Maps
>>>  <p><input type="checkbox"/>How to Explain Individual Classification Decisions</p>  
>>>  <p><input type="checkbox"/>Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps</p>
>>>  <p><input type="checkbox"/>SmoothGrad: removing noise by adding noise</p>  
>>>  <p><input type="checkbox"/>Axiomatic Attribution for Deep Networks</p>
>>>  <p><input type="checkbox"/>Towards better understanding of gradient-based attribution methods for Deep Neural Networks</p>  
>>>  <p><input type="checkbox"/>Contextual Prediction Difference Analysis for Explaining Individual Image Classifications</p>
>>>  <p><input type="checkbox"/>Learning important features through propagating activation differences</p>  
>>>  <p><input type="checkbox"/>Learning Deep Features for Discriminative Localization</p>  
>>### 1.4 Prototypes/Example Based
>>>  <p><input type="checkbox"/>Examples are not enough, learn to criticize! Criticism for Interpretability</p>
>>>  <p><input type="checkbox"/>Representer Point Selection for Explaining Deep Neural Networks</p>
>>>  <p><input type="checkbox"/>Evaluating Explanations: How much do explanations from the teacher aid students?</p>
>>### 1.5 Counterfactuals
>>>  <p><input type="checkbox"/>Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR</p>
>>>  <p><input type="checkbox"/>Interpretable Counterfactual Explanations Guided by Prototypes</p>
>>>  <p><input type="checkbox"/>Explaining machine learning classifiers through diverse counterfactual explanations</p>
>>>  <p><input type="checkbox"/>Model-agnostic counterfactual explanations for consequential decisions</p>
>## 2. Global Explanations



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