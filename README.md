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
 of requests, amount of current memory, and response time. Then I analyzed the data and found trends and compared
 them.


