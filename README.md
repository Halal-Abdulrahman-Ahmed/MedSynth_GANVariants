# MedSynth_GANVariants-
This repository contains implementations of multiple Generative Adversarial Network (GAN) approaches for generating medical synthetic data. 

Generative Adversarial Networks for Generating Medical Synthetic Data

This repository contains implementations of multiple Generative Adversarial Network (GAN) approaches for generating synthetic data. The implemented GAN variants include:
	GAN (Generative Adversarial Network)
	CGAN (Conditional Generative Adversarial Network)
	CTGAN (Conditional Tabular Generative Adversarial Network)
	CRAMERGAN (Cramer Generative Adversarial Network)
	DRAGAN (Deep Regret Analytic Generative Adversarial Network)
	WGAN (Wasserstein Generative Adversarial Network)


Datasets/Raw Data

The project includes three medical datasets used for training and testing the GAN models. The datasets include:

-	Breast Cancer Wisconsin (Diagnostic)
-	Lung Cancer Patient  
-	Fetal Cardiotocography (CTG) 

We employed the YData-Synthetic package to implement GAN, CGAN, CRAMER GAN, DRAGAN, and WGAN. For CTGAN implementation, we utilised the pre-existing CTGAN library. Additionally, we used other standard Python libraries such as Pandas, NumPy, Random, Seaborn, Matplotlib, and Scikit-learn.
