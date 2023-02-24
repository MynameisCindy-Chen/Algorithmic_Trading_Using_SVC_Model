# Module 14 Assignment

### **Question 1: What impact resulted from increasing or decreasing the training window?**

Dateoffset has an impact on training window movement depending on the numbers of months choosing as training dataset. 3 months training data has the larger differences between Actual Returns and Strategy Returns. According to first graph, predicted and actual returns data are almost the same, the moving trends are duplicated. Starting from 2019, the gap appeared and there were some differences on cumulative return percentage. From second graph with 18 months training dataset, predicted return verus actural returns results are more closer and the gap is smaller compared with 3 months training dataset. The moving trend were always duplicated from 2015 to March 2020, After 2020-03-11, results were not matching. 

In general, the numbers of months setting as training data will affect the prediction results. The higher value of periods(months) being chosen, the prediction value is more closer to actual value. 


![Module_14_Assignment](./SVC%20Model%20-%20Actual%20Return%20vs%20Strategy%20Returns(3%20months).png)

![Module_14_Assignment](./SVC%20Model%20-%20Actual%20Return%20vs%20Strategy%20Returns(18%20months).png)


### **Question 2: What impact resulted from increasing or decreasing either or both of the SMA windows?**

Please see the line graph below. I try the way of increasing both long and short SMA windows. I increase short window from 4 to 10, long window from 100 to 120. the predicted and actual results are almost the same, which means the cumulative return percentage are very close.The prediction results are much more accurate now. 

![Module_14_Assignment](./SVC%20Model%20-%20Actual%20Return%20vs%20Strategy%20Returns(18%20Months%20%2B%20Increase%20window).png)

In comparison with these 3 graph, the last graph has the best performance on predicting cumulative returns. The last graph strategy I used is combining the condition of 18 months training dataset and increasing cumulative days of closed price moving average under both long and short window, which can improve the value of simple moving average and return percentage. 
