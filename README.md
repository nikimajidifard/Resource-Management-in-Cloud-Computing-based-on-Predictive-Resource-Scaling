# resource-management-in-cloud-computing-based-on-predictive-resource-scaling
## Concise abstract:
  Cloud computing has become pivotal in managing large-scale computing systems and services, necessitating efficient resource management strategies to handle its complexities effectively. The focus lieson improving 
  resource efficiency, cost reduction, performance enhancement, and energy optimization. This project explores the integration of predictive methodologies to enhance resource allocation and management in cloud 
  environments. Utilizing a real-world dataset, the project employs a stochastic model and machine learning techniques, including both traditional regression models and advanced neural network architectures, as 
  well as their combined approach. Each method's performance was assessed through a comprehensive set of metrics designed to evaluate improvements in CPU utilization prediction. It conducts broad assessments, 
  implementations, and comparisons of various methodologies to identify optimal resource management strategies.

## Introduction:
 Cloud computing provides a platform for developers to run their applications in the cloud without having toworry about installing and configuring a server.On the other hand, cloud computing provides the 
 possibility of resource sharing with greater productivity, scalability and maximum flexibility. One of the key aspects of cloud computing and virtualization is resource management. Resource management is the 
 allocation of resources such as processor, memory, storage and network bandwidth to virtualization units such as virtual machines in the cloud. By monitoring system performance, data can be extracted to analyze 
 program status. Statistical and machine learning methods can then be used to predict resource allocation and improve cloud management.

## Project Goal:
 This project aims to evaluate and compare statistical and machine learning methods for predicting resource allocation in cloud management. The ultimate goal is to improve cloud resource utilization by leveraging
 collected and processed data. By using these predictions, the project seeks to optimize resource allocation and management, leading to increased efficiency and reduced resource waste.

## Data Collection, Implementation and Results:
 This chapter begins by highlighting the crucial role of accurate data in effective server resource management. Theimportance of proper data collection and storage for future analysis is then emphasized. Pre- 
 processing was conducted to clean the data and analyze collection methods. The primary goal was to predict future processing power requirements based on factors like current time and request volume. To achieve 
 this, various statistical and machine learning techniques were planned for evaluation and performance comparison. This chapter will discuss the implementation of Markov models, linear regression, polynomial 
 regression, neural networks, and recurrent neural networks. Prediction results for different times will be examined. Ultimately, this analysis aimed to identify the most effective method for predicting future 
 processor needs and informing smarter server resource management decisions. Initially, I utilized a dataset from Kaggle, but encountered several issues. The dataset lacked a logical relationship between inputs 
 and outputs since it wasn't based on real-world data. Additionally, it contained numerous missing data points. Removing these data points could lead to significant issues with the analysis. Moreover, there was 
 insufficient documentation accompanying the dataset. With the surveys conducted on the monitoring data of a well-established company's servers, data needed to implement statistical algorithms and machine 
 learning were collected and extracted. Data from different panels were merged to obtain the required dataset. In the next step, Four features were extracted from the dataset for prediction purposes: time, number 
 of requests, amount of current memory, and response time. Then I analyzed the data and found trends and compared them.

 <img src="https://github.com/user-attachments/assets/09ae3fe3-b99a-41ac-9b0b-5c2cb4744385" width="300" height="300"/>
 <img src="https://github.com/user-attachments/assets/72dd370f-eb1a-4671-a6e6-73718dd4da89" width="300" height="300"/>
 <img src="https://github.com/user-attachments/assets/e1ed986b-bca0-4342-9b89-33afe9bc2d78" width="300" height="300"/>
 <img src="https://github.com/user-attachments/assets/2de1e08f-2103-4e1b-9d70-19a252f02217" width="300" height="300"/>
 <img src="https://github.com/user-attachments/assets/7f795a63-a096-44ac-8742-097efbb0acac" width="300" height="300"/>


## Implementations and Algorithms:
 The first model I implemented was a Markovmodel. The analysis began by defining CPU utilization categories: idle, low, and high. Based on the available data, a probability model was constructed to predict the 
 next state (CPU utilization) based on the current state. This involved iterating through the data once and calculating the transition probabilities between each category. Following the implementation of the 
 Markov algorithm, the prediction of the next state was performed considering the current state and the possible values obtained, both dependent on and independent of the previous state. The second method was 
 linear regression. This method utilizes a linear regression model to establish a linear relationship between the desired features (likely including factors influencing CPU consumption) and the output value, 
 which in this case is CPU consumption. The model essentially seeks the optimal linear mapping between inputs and outputs to minimize error. Then polynomial regression was applied due to the structure of the data 
 and observations from data visualizations, along with the identified polynomial structure. This method utilizes regression with 1st and 2nd degree features. The next model was a neural network. In this method, 
 by using the structure of neural networks, the amount of processor resource consumption was predicted. Layers and model details are available in the code. The last one was a recurrent neural model. Due to the 
 structure and temporal dependence observed in the data, a neural networks model was employed. The structure and temporal dependence of the data necessitated the use of a neural networks model. This model 
 considers both the current input features and the previous outputs when determining the output at each time step. In the final step of implementation, prediction combination approach was utilized. This involved
 combining the predictions from the Markov model with the outputs from the models presented earlier. The combined results were then used to make the final predictions. In the evaluation step, four model 
 evaluation criteria were employed to assess the performance and quality of the trained models. They were MAE (Mean Absolute Error), R-squared (R²), RMSE (Root Mean Squared Error), and MSE (Mean Squared Error). D 
 etailsregarding their selection are provided in my study.


## Prediction Results:
 I finally analyzed and compared the performance of the implemented models in predicting CPU consumption. This analysis allowed me to evaluate the suitability of each model based on their performance. The results 
 were then visualized for comparison.


 According to the graphs and above values, the R² polynomial regression model was better and was closer to the original data, although the neural network model had a slightly lower MAE value. In the Markov 
 decision-making methods, which are calculated with the criteria of 0 and 1 and without numerical difference, independent Markov has higher accuracy. Additionally, adding Markov probabilities to the features of 
 the linear model has significantly increased the R-squared of the model, as shown in the above table






