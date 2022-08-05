# Bike Sharing Predictions

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state

- Essentially the company wants to know that 
  * Which variables are significant in predicting the demand for shared bikes.
  * How well those variables describe the bike demands.
 
### Step-1 Understand the data (using the box plot and heatmap)
![download](https://user-images.githubusercontent.com/5464884/183070185-527bee57-2477-4634-b48f-16b94eba03e3.png)

### Step-2 Data Visulazition 
- Pair plot graphs between the numeric independent variables:
  * ![download](https://user-images.githubusercontent.com/5464884/183068800-46f2dc9d-be2c-415f-9a8f-2188e4f3aeb8.png)

### Step-3 Model Building  Process 
#### Split the Training Data and Test Data 
#### Scale the features 
#### Build Model using RFE 
#### Calculate the VIF 
#### Re-iterate the process to build model again by dropping the columns from previous data traning set
#### Finally do the Residual Analysis
![download](https://user-images.githubusercontent.com/5464884/183070116-ae7a172f-8f99-4d1b-a7ca-4b701f8860d6.png)

#### Now make final predicion from test data set

