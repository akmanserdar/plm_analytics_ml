## Description

This repository contains a comprehensive analysis of change request (CR) approvals within a Product Lifecycle Management (PLM) system. The analysis includes Multiple Linear Regression as a machine learning (ML) model to optimize the approval process.

## Example Use Case
Using the model of Multiple Linear Regression we developed, you can predict the ***approval time*** for this request.   
Let's say we have a sample CR input with the following features:

**Change_Type:** Major  
**Complexity:** 8  
**Department:** Engineering  
**Requested_By:** UserA  

Results:  

   Train MSE: 8.30  
   Train R^2: 0.73  
   Test MSE: 10.27  
   Test R^2: 0.70  
   
   Predicted approval time for sample change request: 17.07 days  

   
    
## Analysis and Interpretation

+ Train MSE (8.30) and Test MSE (10.27) are relatively low, indicating that the model's predictions are, on average, close to the actual approval times.
+ Train R^2 (0.73) and Test R^2 (0.70) suggest that the model explains 73% of the variance in the approval times for the training data and 70% for the test data.
+ Feature Engineering might improve model performance. Adding some features such as *historical approval times*, *specific user workload*, or *project priority* might be convenient.

## Actionable Steps

+ **Assign Optimized KPI:** *Set realistic deadlines and expectations with CR owners.*  
+ **Improved Planning and Scheduling:** *Plan project phases with more accuracy, knowing when approvals are likely to be completed.*  
+ **Prioritize Review:** *Knowing that this request will take longer, prioritize its review to avoid project delays.*  
+ **Allocate Resources:** *Ensure that the necessary resources (e.g., reviewers, subject matter experts) are available to expedite the process.*  
+ **Communicate:** *Inform the relevant stakeholders about the expected approval time and any potential impacts on the project timeline.*  
+ **Monitor Progress:** *Track the progress of the approval process closely and prevent if any delays occur.*  

## Conclusion
The model performs reasonably well with a good balance between train and test performance. The predictions are useful for planning and resource allocation in PLM processes. Further improvements can be made by enhancing feature engineering and exploring more complex models.
