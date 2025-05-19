# Programming for AI (2)

Material for the second part of the Programming for AI course on the "Applied Artificial Intelligence and its Mathematical Foundations" at UPV/EHU.

# Objectives

 - Get familiar with the latest and most advanced techniques and tools for programming AI systems.

# Schedule

## Session 1: Neural Network programming
 - Neural Network programming. Abstractions, API and low-level components (tensor operations + architecture definition). Connection with last sessions from Mikel (standard Keras API). A bit of history about DL frameworks.

   ★ Basic examples using Keras. Different data types (feature based, raw images, time series). Model assessment.


## Session 2: DL Frameworks. JAX
 - Tensorflow, PyTorch and JAX: Comparative analysis, similarities and differences. Strong points of each one.
 - JAX as a target for low-level coding. Steeper learning curve, so better to do it in a guided way.

   ★ JAX fundamentals: Autodiff, JIT, vectorization. Intro to functional programming. Optimizing with Optax.


## Session 3: Advanced JAX programming.
 - Developing on session 2 fundamentals, we will focus on advanced cases and techniques to make code suitable for JIT and get the highest possible performance.

   ★ Advanced JIT, VMAP and automatic differentiation in JAX.


## Session 4: Building a model from scratch (I)
 - Data preparation: capture, cleaning, feature extraction.

   ★ Preparing time series data from scratch (ECG signals).
   
   ★ Splitting the data in a correct manner. Data leakage and i.i.d assumption violation.


## Session 5: Building a model from scratch (II)
 - Design of experimental validation:
   - Choose a model or set of models to evaluate.
   - Define an optimization problem: Loss function, metrics, optimizer, hyperparameters.
   - Run the experiments and extract conclusions.

   ★ Build models to solve the problem depicted in session 4.

   ★ Validate the results. Overfitting assessment.


## Session 6: Customizing Keras
 - Keras tuning with JAX. Progressive disclosure of complexity. How things fit with what we saw in the previous session.

   ★ Create custom Layers, Metrics and Losses.

   ★ Customizing what happens in fit(): train_step, compute_loss_and_updates. More advanced customization of the loss function. Standard data-oriented interface vs. more complex cases (requiring access to the model).

   ★ Callbacks.


## Session 7: Leveraging on existing models
 - Up to now most practical tasks in AI are related to data preparation and model development. However, it is more and more frequent to use existing models (specifically foundational LLMs) and integrate them into a custom pipeline.

   ★ How to install DeepSeek locally and query it programmatically.

   ★ Transfer learning and fine tuning in Keras.

   ★ Embeddings. General embeddings vs. domain-specific ones: Example of MediTron from EPFL.


## Session 8: Structured Generation
 - Structured Generation on LLMs. Motivation, what it is, benefits.

   ★ Tutorial on structured generation.







