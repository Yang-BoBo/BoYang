---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Greetings! I’m Bo Yang, a MSc student specializing in Electronic Engineering. My research interests are primarily focused on Deep Learning for audio and speech related challenges, computer vison, and signal processing. Presently, I am gaining research experience as an intern at NXP within the RAISE project. My MSc thesis centers around the optimization of the innovative Complex-Real Value Neural Network (CRVNN) developed by NXP. My primary focus lies within the realm of autoML, particularly in areas such as Hyperparameter Optimization (HPO) and Neural Architecture Search (NAS). I leverage autoML frameworks like Optuna to enhance both the architecture and other hyperparameters of the CRVNN. Then use optimized NN to do audio related application such as speech enhancement. We are at an AI carnival, a transformative era akin to the advent of steam engines and electricity, reshaping the fabric of human society. My aspiration is not to stand on the sidelines but to actively engage as a participant in this dynamic celebration. That’s why I am actively seeking a PhD position.

# 🔥 News
- *2023.12*: &nbsp;🎉🎉 I will be an intern at **[NXP](https://www.nxp.com/)** for 9 months, supervised by Prof. [Ronald Aarts(TU/e)](https://scholar.google.com/citations?user=4YkmIdIAAAAJ) and Prof. [Frans Widdershoven(Tud)](https://scholar.google.com/citations?user=hjoNDEcAAAAJ)
- *2023.07*: &nbsp;🎉🎉 I will be an intern at **[IMEC](https://www.imec.be/nl)** for 5 months, supervised by Dr. [Alireza Sheikh(IMEC)](https://scholar.google.com/citations?user=cFi3oTsAAAAJ) and Prof. [Hamdi Joudeh(TU/e)](https://www.tue.nl/en/research/researchers/hamdi-joudeh/)
- *2022.09*: &nbsp;🎉🎉 I started my master's study at TU/e in Electrical Engineering (Signal Processing System).
- *2022.07*: &nbsp;🎉🎉 I am graduated from Shandong University with a bachelor’s degree, supervised by [Jifang Tao](https://scholar.google.com.sg/citations?user=s_cKVGgAAAAJ&hl=en).


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2024</div><img src='images/ECAI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hybrid Real- and Complex-valued Neural Network Architecture](under submission)

**Bo Yang**, Luan, Boris, Alex

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JC&S 2024</div><img src='images/JCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Successive Threshold-Based Multipath Mitigation Aided by Neural Network for UWB Ranging](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

 Alireza Sheikh, **Bo Yang**, Mohieddine El Soussi, Amirashkan Farsaei, and Peng Zhang

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com),  **JC&S 2024**


- *2021,* A wireless intelligent sensor and its application. patent number: CN202110094598.5
</div>
</div>
  

# 📖 Educations
- *2022.09 - now*, Master in Eletrical Engneering(track:Signal Processing System), **Eindhoven University of Technology**, Netherlands

	*GPA*: 8.4/10

	*Relevant Course*:
  
Statistical signal processing, Non-linear optimization, Bayesian machine learning and information processing ,
					Adaptive array signal processing, Techniques for video compression & analysis, 
					Convolutional neural networks for computer vision, Advanced sensing using deep learning.

- *2018.09 - 2022.07*, Bachelor in Electronic Engineering, **Shandong University**, Qingdao, China
	
	*GPA*: 84.76/100 (TOP 22%)


# 💬 Invited as TPC reviewer
- *2024.03*, Invited as TPC reviewer for IEEE JC&S 2024.


# 💻 Internships
- *2023.12 - 2024.09, Research Intern*, **NXP**, Eindhoven NL

	I am a part of the ML&AI department at NXP, where my role centers around the optimization of the
innovative Complex-Real Value Neural Network (CRVNN) developed by NXP. My primary focus lies within the
 realm of autoML, particularly in areas such as Hyperparameter Optimization (HPO) and Neural Architecture
 Search (NAS). I leverage autoML frameworks like Optuna and NNI to enhance both the architecture and other
 hyperparameters of the CRVNN. Additionally, I am actively involved in crafting automated procedures for the
 design of this novel network. My responsibilities extend to the development of an architecture optimization
 framework, followed by efforts to enhance the interpretability and explainability of the network. Once the CRVNN
 architecture is refined, I apply it to specific tasks, such as optimizing its performance for applications like hearing
 aids

- *2023.07 - 2023.12, Research Intern*, **IMEC**, Eindhoven NL

	I am working in UWB4z Group. My work as follow:
	- Research relative papers about ranging estimation using UWB signals. 
	- Use deep learning to empower exsisting algorithm to achieve better performance.
	- Design the architecture of neural network and train it on IMEC simulation data set.
	- Test the performance on various criterions and write paper.

- *2021.09 - 2022.01, Research Intern*, **DiDi Global**, China
	
	Assisting with the development and execution of test plans and test cases for software applications or websites.
Participating in the testing of software releases to identify bugs, defects, and usability issues. Documenting and
tracking defects and issues found during testing, and working with developers to resolve them. Conducting
regression testing to ensure that previously identified defects have been fixed and do not reoccur.


# 🔥 Project
- *2023.07 - 2023.12*, **UWB signal Range Estimation by STMnet**
	
	- Use a successive threshold-based multipath mitigation algorithm (STM) that improves the ranging performance in multipath conditions.
	- Then further improve the ranging performance of STM in multipath conditions by aiding the STM with STMnet as a  Neural network that estimates the ranging error of the STM.

      
- *2023.03 - 2023.06*, **DOA Estimation By Deep Learning**
	
	- Propose a solution for the estimation of number of sources together with their corresponding DOAs. 
	- Combine neural network with maximum likelihood estimation (MLE) to obtain a good results and save computation resources. Test the solution by different scenarios and the performance is great for signals with low SNR.


- *2023.01 - 2023.03,* **Anomaly Detection with Autoencoder**

	- Implement, run and analyze an autoencoder architecture from scratch for anomaly detection purpose on MNIST dataset.


- *2022.11 - 2023.01,* **Cityscapes Pixel-Level Segmentation Benchmark and Robust Segmentation**

	- create a network that performs semantic segmentation on the Cityscapes dataset.
 	- implementation of a trainable network which successfully evaluates on the cityscapes dataset.
	- Neural networks degrade in performance when unexpected things occur. We Finetune the network to become a robust solution for various conditions, to overvcome the degrade in performance when unexpected things occur.
	- Use two robustness benchmarks(Degrading of image quality and Generalization) to evaluate the NN.

