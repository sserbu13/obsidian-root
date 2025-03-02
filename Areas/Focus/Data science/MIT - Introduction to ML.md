## Chapter 1
---
### Introduction

> [!NOTE]
> The main focus of machine learning is making decisions or predictions based on data

- **Economics and psychology** focus on finding **causal processes** (i.e., understanding the "why" behind events or behaviors).
- **Statistics** focuses on building models that **fit data well**, often prioritizing accuracy over explaining causality.
- **Machine learning** tends to focus on creating models that can **predict** outcomes from data, often without concern for underlying causality.
---
### The two main problems addressed

• estimation: When we have data that are noisy reflections of some underlying quantity of interest, we have to aggregate the data and make estimates or predictions about the quantity. How do we deal with the fact that, for example, the same treatment may end up with different results on different trials? How can we predict how well an estimate may compare to future results? 

• generalization: How can we predict results of a situation or experiment that we have never encountered before in our data set?

---
### Problems and Solutions

> [!NOTE]
> We can describe problems and their solutions using six characteristics, three of which characterize the problem and three of which characterize the solution: 

#### Problem Characteristics

1. **Problem class:** What is the nature of the training data and what kinds of queries will be made at testing time? 
2. **Assumptions:** What do we know about the source of the data or the form of the solution? 
3. **Evaluation criteria:** What is the goal of the prediction or estimation system? How will the answers to individual queries be evaluated? How will the overall performance of the system be measured?

#### Solution Characteristics:

4. **Model type**: Will an intermediate model be made? What aspects of the data will be modeled? How will the model be used to make predictions? 
5. **Model class:** What particular parametric class of models will be used? What criterion will we use to pick a particular model from the model class? 
6. **Algorithm:** What computational process will be used to fit the model to the data and/or to make predictions?

> [!NOTE]
> Without making some assumptions about the nature of the process generating the data, we cannot perform generalization.

---
### Problem Class

There are many different problem classes in machine learning. They vary according to what kind of data is provided and what kind of conclusions are to be drawn from it

#### Supervised learning

The idea of supervised learning is that the learning system is given inputs and told which specific outputs should be associated with them. We divide up supervised learning based on whether the outputs are drawn from a small finite set (classification) or a large finite or continuous set (regression).

##### Classification



#data_science 