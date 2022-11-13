# Real life addition ➕🤖🟰
### Overview:  https://www.kaggle.com/competitions/real-life-addition/ 

Kaggle ML competition on digit recognition, but different to classic MNIST, ground truth is the sum of the numbers in the image. \
Multiclass classification problem, I used Python (Jupyter notebook) and took a CNN approach.  

Prerequisite for course on Predictive and Classification Modelling at McGill University.

### Data Sample:
![image](https://user-images.githubusercontent.com/47335322/201535685-acb08093-69e1-455b-897b-e98195dec6b2.png)  
6 + 3 + 5 = 14

![image](https://user-images.githubusercontent.com/47335322/201535749-eb8d12c8-8ecf-4e73-b2a1-739eaddacf59.png)  
5 + 0 + 4 = 9 

### Structure:
Multilayer CNN 

<img width="1081" alt="Screen Shot 2022-11-13 at 5 58 22 PM" src="https://user-images.githubusercontent.com/47335322/201549031-d86868de-d623-4202-9437-27fc2bec93d1.png">  

Diagram created using NN-SVG tool: http://alexlenail.me/NN-SVG/LeNet.html

### Overall results:
86.5% test accuracy (Kaggle performed testing evaluation on 30% original test data, 70% other private data)  
92.9% train accuracy  
Model significantly overfit, as training accuracy was 6% higher than test accuracy. 

### Possible improvements:
- Add L1/L2 Regularization
- Reduce model complexity (remove some convolution layers)
- Try dropout with a higher rate, or more dropout layers.
