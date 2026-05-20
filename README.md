# Related Literature Reviews

## 1. [Image-based Measurement of Material Roughness using Machine Learning Techniques](https://www.sciencedirect.com/science/article/pii/S2212827120311422) (2020)

Dataset size: 4400 images total for training

Good: beautiful images design. Nice GUI design for real applications. Prediction is accurate. Real time (in-situ) detection. 

Downside: Task is simple. 

Relation: They proposed CNN method to predict Ra value for real time anomaly detection and build up a nice GUI.

Keywords: EDM machines, Electrical discharge machining (EDM), Optical methods, Convolutional Neural Network (CNN), surface roughness, Ra value, In-situ metrology, profilometer, haptic, optical, intelligent manufacturing cells, real time, anomaly detection

> One important advantage of optical methods is that they can be potentially integrated in the machining process. 
>
> given as input a small square picture -> returns the Ra value of that part of the surface
>
> Several related works also deal with the problem of measuring the characteristics of a surface using image processing techniques. A similar approach to ours also adopts machine learning using input images acquired by polarized microscopes [10]; different approaches based on traditional image-processing techniques rely on histograms [11] or grey level co-occurrence matrices [12] as features, or use specialized techniques to reconstruct the 3D topography [13]



<img src="/Users/ziyi/Library/Application Support/typora-user-images/image-20260519172118969.png" alt="image-20260519172118969" style="zoom:50%;" />

<img src="/Users/ziyi/Library/Application Support/typora-user-images/image-20260519172257038.png" alt="image-20260519172257038" style="zoom:67%;" />

---

## 2. [Machine learning approaches for recognition and classification of nanomaterial morphology](https://www.sciencedirect.com/science/article/abs/pii/S2352492824027995) (2024)

This is a paper review. Our goal is **high-throughput, automated** measurements with little human intervention.

Comment: Still using conventional Computer vision techniques; Starting from given electron microsopic result (SEM, TEM images) to do size prediction and pattern recognition. NOT applicable to our project (we are starting from Rheed video to predict AFM images) in methodology.



<img src="/Users/ziyi/Library/Application Support/typora-user-images/image-20260519190355797.png" alt="image-20260519190355797" style="zoom:50%;" />

ML models to predict nanoparticle size:

![image-20260519184201953](/Users/ziyi/Library/Application Support/typora-user-images/image-20260519184201953.png)

![image-20260519184323586](/Users/ziyi/Library/Application Support/typora-user-images/image-20260519184323586.png)

ML models to recognize and classify nanoparticle:

![image-20260519184849750](/Users/ziyi/Library/Application Support/typora-user-images/image-20260519184849750.png)

---

## 3. [Machine learning approach for surface morphology of nanoparticles: Image analysis and data mining techniques](https://pubs.aip.org/aip/acp/article-abstract/3157/1/080013/3344689/Machine-learning-approach-for-surface-morphology?redirectedFrom=fulltext)

investigate the the surface shape of nanoparticles (different in terms of their sizes, shapes, and types of surfaces).

Support vector machines (SVM), decision trees, and neural networks were trained with the feature dataset that was returned in order to identify and predict surface morphological traits

image analysis techniques like fractal analysis, form descriptors, and texture analysis were used to get full features from shots of nanoparticles

The models' accuracy, precision, memory, and F1-scgiore were looked at.

Downside: only use SVM and KNN clustering. No comparison with other methods. language, plots and style need to be improved. Not seeing any direct and clear images of AFM/TEM or dataset. 

Comment: the only usable information from the paper is how we can process AFM data, like feature extraction. But we can expect sources from other academically valid and clear paper other than this one. Overall it is worthy to check back when implementing detailed AFM processing work and happen to use SVM/KNN techniques. 

---

## 4. 





