# Machine Learning and Pattern Recognition  
## Lab 5 – Distance-Based Classification & KNN  
Spring Semester 2026  

### Aim  
The objective of this lab was to understand distance-based classification techniques,
various distance metrics, and the K-Nearest Neighbors (KNN) algorithm.

---

### Methodology  

The following tasks were performed:

- Face detection using OpenCV
- Feature extraction using HSV color space (Hue & Saturation)
- Clustering using K-Means
- Visualization of feature space
- Template image classification
- Analysis of distance metrics and KNN behavior

---

### Key Concepts Explored  

- Euclidean Distance    
- Bias vs Variance in KNN  

---

### Results & Observations  

- Faces were successfully detected and features extracted
- K-Means clustering grouped faces based on color features
- Feature scaling importance observed
- KNN sensitivity to K value demonstrated

---

### Conclusion  

Distance metrics play a critical role in similarity-based learning.
KNN performance depends heavily on feature scaling and choice of K.

---

### Visualizations  

### Face Detection Output
Detected faces highlighted using Haar Cascade classifier.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2749aba1-400c-4f16-850a-dbb7a688d174" />

### K-Means Clustering Result
Faces clustered based on Hue & Saturation features.
<img width="861" height="467" alt="image" src="https://github.com/user-attachments/assets/b4595b7b-5c1a-4b54-8f19-00f426125ab7" />
<img width="861" height="468" alt="image" src="https://github.com/user-attachments/assets/86f10f6f-a237-4d34-af90-9bbd451d12f5" />

### Template Face Classification
Template image projected into feature space and assigned to nearest cluster using trained K-Means model.
<img width="868" height="464" alt="image" src="https://github.com/user-attachments/assets/e166a6d6-64cd-4bd3-8eeb-631a2da39529" />

### Cluster Visualization with Centroids
Cluster centroids and template sample visualized to interpret grouping behaviour.
<img width="870" height="464" alt="image" src="https://github.com/user-attachments/assets/a0a5151c-d494-4c88-bba1-85973315887d" />
