# AI/ML Project: BoomBikes Share Prediction 🚲
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/146691034-7f7fa1ec-cf3d-48dd-bb1d-1adb2947a356.png" style="width: 1000px;"/></p>

### Description:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demand
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Bussiness Goal:
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Acknowledgement: 
The dataset is referred from Kaggle:\
https://www.kaggle.com/yasserh/bikeshare

### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the shares of bikes.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/146691064-10f8d26c-c580-4bec-9226-57b8e1b4cda1.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/146691067-80c66fbc-cc80-4fab-a629-d674567f2429.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/146691081-9222b1df-8475-47b7-9777-c3c627de010b.png)
![image](https://user-images.githubusercontent.com/54996245/146691084-e6b27ff8-3a91-470e-a5fa-5b2c8dc5ffc0.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/146691086-6ac7595d-5fec-4e54-8682-56e9e3dd10c6.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/146691092-9b590184-10c5-4e54-be08-895fc276803e.png)

**6. Correlation Plot**
  
![image](https://user-images.githubusercontent.com/54996245/146691102-165b8048-383b-411a-86a1-70f641101814.png)

**7. Feature Selection/Extraction - VIF, RFE & PCA Techniques:

![image](https://user-images.githubusercontent.com/54996245/146691108-6d43b1ce-9781-412a-9344-f81869ea4e32.png)
![image](https://user-images.githubusercontent.com/54996245/146691116-9ff2d2a6-475d-4c6f-8bc8-b0d287790c4a.png)
![image](https://user-images.githubusercontent.com/54996245/146691119-4e4a219f-e58e-400f-8c79-9431219facde.png)
![image](https://user-images.githubusercontent.com/54996245/146691123-2da7de98-37dd-4335-bf1a-e3f9b9a5b7b9.png)

**8. Multiple Linear Regression Prediction & Residual Normality Check**
  
![image](https://user-images.githubusercontent.com/54996245/146691133-d4ad29c1-84a8-45ab-a19a-9443cb6b3d79.png)

**9. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/146691143-3dfa7382-c42f-4872-bfc5-184a7c5cfc7b.png)

**10. Predictions**

![image](https://user-images.githubusercontent.com/54996245/146691151-3795f5d5-0f0c-49e7-8f4a-28c0405c5672.png)

**11. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/146691161-183e7894-39de-4e10-b560-4ae14957c604.png)
![image](https://user-images.githubusercontent.com/54996245/146691165-060bb060-080c-4b17-9cb8-69162ca48675.png)

### Here are some of the key outcomes of the project:
- The Dataset was quiet small with just 730 samples & after preprocessing 7.9% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had high multicollinearity, hence in Feature Extraction step, we shortlisted the appropriate features with VIF Technique.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) was the best choise, yet it is safe to use multiple regression algorithm, as their scores were quiet comparable & also they're more generalisable.
