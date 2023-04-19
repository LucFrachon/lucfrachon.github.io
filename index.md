## Selected Public Projects

---

### Denoising Diffusion Probabilistic Model trained on TinyImageNet and Google Images data; MLOps and hyperparameter sweep using WandB  
I implement the "Denoising diffusion probabilistic models" paper (Ho _et al._) and train it on a TinyImageNet class. Additionally, I scrape about 500 images from Google Images to roughly double the size of the training set. The hyperparmeters are optimised with WandB Sweeps to minimise the Frechet Inception Distance. Artifacts and runs are logged with WandB. Even with only 1,000 images and limited data augmentation, the model is able to learn and produce evocative pictures.

<p align="center">
  <img src="images/diffusion.gif?raw=true"/>  
</p>  


<img src="images/Python-F7CC40.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/-Lightning AI-792EE5.svg"/> <img src="images/-WandB-darkgrey.svg"/> <img src="images/-Google Images-lightgrey.svg"/> <img src="images/PyCharm-20D38F.svg"/>  

[View on Github](https://github.com/LucFrachon/ddpm_tinyimagenet)  

---

### Reinforcement Learning for the Management of Invasive Species
This work-in-progress models an environment as a grid and uses stochastic life-cycle rules to represent an invasive species. An actor-critic agent is trained to balance treatment cost and population size/proliferation. The state and value learning models are deep neural networks trained with replay.

<p align="center">
  <img src="images/invasive_species.png?raw=true"/>   
</p>

<img src="images/Python-F7CC40.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/PyCharm-20D38F.svg"/>  

[View on Github](https://github.com/LucFrachon/actor-critic-for-ecology)


---

### Neural Radiance Fields
I implement a Neural Radiance Field model (Mildenhall _et al._) in PyTorch, i.e. a model able to generate novel views of a 3D scene after being trained on a collection of pictures of the scene from different angles. The model learns to predict the emitted colour and the density of each point in the scene from any angle, and accumulates these values along paths that reach each of the new view's pixels, resulting in a image.

<p align="center">
    <img src="images/cameras.png?raw=true"/> <img src="images/tractor.png?raw=true"/>
</p>

<img src="images/Python-F7CC40.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/-Lightning AI-792EE5.svg"/> <img src="images/-WandB-darkgrey.svg"/> <img src="images/Jupyter-lightgrey.svg"/>  

    
[View on Github](https://github.com/LucFrachon/nerf)

---

### A Step by Step Data Science Prototype for University Students
These notebooks are part of a course that I designed and taught to second year CS BSc students at NewGiza University. I present a step by step worked example of how to sanitise data, explore it, visualise it, engineer new features, and fit and evaluate simple ML models. 

The dataset contains eBay used car listings in the German market (found on Kaggle). It is fairly noisy,  contains some ambiguous variables that could be considered as either continuous or categorical, and requires significant domain knowledge to fully exploit. As such, it is a good representation of the tasks a real Data Scientist might have to perform.

<p align="center">
  <img src="images/car_price_heatmap.png?raw=true"/> 
</p>


<img src="images/Python-F7CC40.svg"/> <img src="images/NumPy-lightgrey.svg"/> <img src="images/-pandas-lightgrey.svg"/> <img src="images/Jupyter-lightgrey.svg"/> <img src="images/scikit--learn-45c5ff.svg"/>  

[View on Github](https://github.com/LucFrachon/ngu_data_science_course_used_cars)

---

### Anomaly Detection with a Variational Autoencoder

This notebook was originally developed to support a blog post (check out my Medium profile!). First, I explain what anomaly detection is. Then I give an intuitive explanation into variational autoencoders and why use them in anomaly detection (with animal analogies!).

Finally, I build a model and train it on a dataset to predict the failure of an industrial machine.

<p align="center">
    <img src="images/dog-and-sheep.png?raw=true"/>  <img src="images/anomaly-detection.png?raw=true"/> 
</p>

<img src="images/Python-F7CC40.svg"/> <img src="images/-PyTorch-lightgrey.svg"/> <img src="images/-Lightning AI-792EE5.svg"/> <img src="images/-WandB-darkgrey.svg"/> <img src="images/Colab-lightgrey.svg"/>  

[View the notebook on Google Colab](https://colab.research.google.com/drive/1BOjnuoNtznwdkFLf5Fv8ZSxAtnwI5q6Z?usp=sharing)

---

### Custom AutoML Pipeline for Financial Prediction

This presentation quickly summarises my approach to developing an account scoring system for one of our clients. For confidentiality reasons, I had to heavily redact it, but it will still give you an idea of the challenges and thoughtprocess to address them.

The model had to serve users from many different companies, each with different data nomenclatures. Therefore, I developed an automated ML (AutoML) pipeline that is able to perform model selection to train the best model for that company's data. The results were a substantial improvement over the previous model, with the user's estimated operating profitability improving by up to 5x.

<p align="center">
    <img src="images/scoring_model_performance.png?raw=true"
         width=500
    /> 
</p>

<img src="images/Python-F7CC40.svg"/> <img src="images/NumPy-lightgrey.svg"/> <img src="images/-pandas-lightgrey.svg"/> <img src="images/scikit--learn-45c5ff.svg"/> <img src="images/XGBoost-4eafe3.svg"/> <img src="images/Optuna-lightgrey.svg"/>  

[View the presentation](https://lucfrachon.github.io/pdf/Scoring_Model.pdf)

---

### A Story in Tableau: Predictive Factors of Math Proficiency

For something a bit different, I use 2012 OECD data from the Programme for International Student Assessment (PISA) to analyse how different factors were predictive of math proficiency among 15-year-old students worldwide. After collecting and sanitising the data, I import it into Tableau, manipulate it, and create a 10-page story (i.e., a collection of dashboards). I look into factors such as: socio-economics, personal and family situation, cultural variables, personal and teacher's attitudes and methods, class frequency vs duration, familiarity with and frequency of the use of computers and information technologies.


<p align="center">
    <img src="images/PISA Score Influencers-1.png?raw=true"
         width=750
    />
</p>

<img src="images/Python-F7CC40.svg"/> <img src="images/-pandas-lightgrey.svg"/> <img src="images/-Tableau-lightblue.svg"/>   

[View the story](https://public.tableau.com/shared/ZMW92D59Q?:toolbar=n&:display_count=n&:origin=viz_share_link)



---
<p style="font-size:11px">Page template provided by <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
