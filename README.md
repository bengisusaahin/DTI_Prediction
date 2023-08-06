# DTI_Prediction
<a href="https://www.linkedin.com/in/bengisu-sahin/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://www.linkedin.com/in/aybarsduran/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>

  We are two students who studying computer science and engineering at Akdeniz University. This is term project for our Introduction to Bioinformatics course. Subject is about the drug target interaction prediction.

<!-- ABOUT THE PROJECT -->
## About The Project
  We describe the process used to predict drug-target interactions (DTIs) using graph convolutional networks (GCNs). In our method, a drug-protein interaction graph is built, informative characteristics are extracted, and the GCN model architecture is designed.
  In this study, we presented a novel methodology for drug-target interaction (DTI) prediction using graph convolutional networks (GCNs). 
	Our approach exhibited good results in properly predicting DTIs and showed potential for enhancing the field of drug development by utilizing the strength of graph-based representation and deep learning.
	We visualized the intricate network of interactions between drugs and their target proteins by creating an extensive drug-protein interaction graph. The graph representation was enhanced by the addition of informative characteristics obtained from similarity matrices, which also gave the GCN model crucial data for forecasting. Our technology successfully learned and utilized the complex relationships and interactions inside the DTI network by fusing feature learning with graph structure.

## Contribution
![image](https://github.com/bengisusaahin/DTI_Prediction/assets/74653216/fa7504e8-5cb8-427f-88d0-681cf764d798)
1) Learning Rate
The learning rate is a crucial hyperparameter that determines the step size during the optimization process. To select an optimal learning rate for our model, we conducted a parameter search by evaluating the performance of the model on a validation set. 
2) Weight Decay
Weight decay, also known as L2 regularization, helps prevent overfitting by adding a penalty term to the loss function.
3) Epochs
The number of epochs determines the number of times the model iterates over the entire training dataset. We conducted experiments to determine the appropriate number of epochs for our model. 

## Result
![image](https://github.com/bengisusaahin/DTI_Prediction/assets/74653216/bcd301ac-ee27-4065-877d-679243df8a32)

To investigate the impact of different learning rates on the performance of our model, we conducted experiments using three distinct learning rates: 0.01, 0.02, and 0.005. 
Based on these results, we can infer that the learning rate significantly affects the model's performance. A learning rate of 0.02 produced the best performance in terms of both AUROC and AUPR scores. Therefore, we selected a learning rate of 0.02 for further experiments and analysis.

![image](https://github.com/bengisusaahin/DTI_Prediction/assets/74653216/066c94e1-196a-46da-80dd-979adcad9312)

![image](https://github.com/bengisusaahin/DTI_Prediction/assets/74653216/8dd43076-8c8c-4437-ab35-837dfed5ea21)

To explore the impact of different weight decay values on the performance of our model, we conducted experiments using two distinct weight decay values: 0.0005 and 0.0002. 
Based on these results, we can infer that the weight decay value has an impact on the model's performance. Therefore, we selected a weight decay value of 0.0005 for further experiments and analysis.




