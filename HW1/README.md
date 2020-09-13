# 6020_Machine-Learning Homework 1
## Group Members:
- Arup Ghosh: ghosha20@students.ecu.edu
- Ping Wang: wangp19@students.ecu.edu
## Quick Start
- Clone the repository
- Open " hw1-KNN.ipynb" file in Jupyter Notebook and run the code
## Discussion about "K"
- **The relationship between"K" and the model accuracy:**

![Model accuracy VS K](images/line-chart.png) 

- **Best K?**
- As in the above line chart, accuracy score are similar as k falls in (1,20). The reason is that the samples of this dataset are almost perfectly seperated into 3 clusters depending on their types, so the accuracy scores are within(0.92,0.98) which is high, no matter how many neighbors we choose. In this case, we will assign n^(1/2) which is around 12 to be he value of k.
