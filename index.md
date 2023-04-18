## Selected Public Projects

---

### Denoising Diffusion Probabilistic Model trained on TinyImageNet and Google Images data; MLOps and hyperparameter sweep using WandB  
I implement the "Denoising diffusion probabilistic models" paper (Ho _et al._) and train it on a TinyImageNet class. Additionally, I scrape about 500 images from Google Images to roughly double the size of the training set. The hyperparmeters are optimised with WandB Sweeps to minimise the Frechet Inception Distance. Artifacts and runs are logged with WandB. Even with only 1,000 images and limited data augmentation, the model is able to learn and produce evocative pictures.

<p align="center">
  <img src="images/diffusion.gif?raw=true"/>  
</p>  


<img src="images/-Python-lightblue.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/-Lightning AI-792EE5.svg"/> <img src="images/-WandB-darkgrey.svg"/> <img src="images/-Google Images-lightgrey.svg"/> <img src="images/PyCharm-20D38F
.svg"/>  

[View on Github](https://github.com/LucFrachon/ddpm_tinyimagenet)  

---

### Reinforcement Learning for the Management of Invasive Species
This work-in-progress models an environment as a grid and uses stochastic life-cycle rules to represent an invasive species. An actor-critic agent is trained to balance treatment cost and population size/proliferation. The state and value learning models are convolutional neural networks trained with replay.

<p align="center">
  <img src="images/rewards.png?raw=true"/> <img src="images/episode_lengths.png?raw=true"/>    
</p>

<img src="images/-Python-lightblue.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/PyCharm-20D38F.svg"/>  

[View on Github](https://github.com/LucFrachon/actor-critic-for-ecology)


---

### Neural Radiance Fields
I implement a Neural Radiance Field model (Mildenhall _et al._) in PyTorch, i.e. a model able to generate novel views of a 3D scene after being trained on a collection of pictures of the scene from different angles. The model learns to predict the emitted colour and the density of each point in the scene from any angle, and accumulates these values along paths that reach each of the new view's pixels, resulting in a image.

<p align="center">
    <img src="images/cameras.png?raw=true"/> <img src="images/tractor.png?raw=true"/>
</p>

<img src="images/-Python-lightblue.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/-Lightning AI-792EE5.svg"/> <img src="images/-WandB-darkgrey.svg"/> <img src="images/Jupyter-lightgrey.svg"/>  

    
[View on Github](https://github.com/LucFrachon/nerf)

---

### A Step by Step Data Science Prototype for University Students
These notebooks are part of a course that I designed and taught to second year CS BSc students at NewGiza University. I present a step by step worked example of how to sanitise data, explore it, visualise it, engineer new features, and fit and evaluate simple ML models. 

The dataset contains eBay used car listings in the German market (found on Kaggle). It is fairly noisy,  contains some ambiguous variables that could be considered as either continuous or categorical, and requires significant domain knowledge to fully exploit. As such, it is a good representation of the tasks a real Data Scientist might have to perform.

<p align="center">
  <img src="images/car_price_heatmap.png?raw=true"/> 
</p>


<img src="images/-Python-lightblue.svg"/> <img src="images/NumPy-lightgrey.svg"/> <img src="images/-pandas-lightgrey.svg"/> <img src="images/Jupyter-lightgrey.svg"/> <img src="images/scikit--learn-45c5ff.svg"/>  

[View on Github](https://github.com/LucFrachon/ngu_data_science_course_used_cars)


---

### Custom AutoML Pipeline for Financial Prediction


---
<p style="font-size:11px">Page template provided by <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
