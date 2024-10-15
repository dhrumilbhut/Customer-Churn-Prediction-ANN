# 🚀 Customer-Churn-Prediction-ANN
This project focuses on predicting customer churn using a deep learning model. The goal is to identify customers who are likely to stop using a company's services, helping businesses take proactive steps to retain them.

# 🔍 Project Overview
Customer churn refers to the loss of customers over a specific period. Predicting churn can help companies take preventive actions such as offering incentives or improving service quality. In this project, we built a deep learning model using **TensorFlow/Keras** to predict customer churn based on historical data such as demographics, service usage, and customer support interactions.

# 🧠 Model Architecture
The deep learning model for this project was built using TensorFlow/Keras. The model architecture includes:

- Input Layer: Consisting of several input features.
- Hidden Layers: Two fully connected (Dense) layers with ReLU activation function.
- Output Layer: A single unit with a sigmoid activation function for churn probability

## Model Summary:
```
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_1 (Dense)              (None, 64)                832      
_________________________________________________________________
dense_2 (Dense)              (None, 32)                2080       
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 33        
=================================================================
Total params: 2945
Trainable params: 2945
Non-trainable params: 0

```

# 📝 Input Features
- Geography: Country of the customer (e.g., France, Germany, Spain)
- Gender: Male/Female
- Age: customer's age
- Tenure: Duration (in years) of the customer’s relationship with the company
- Balance: Account balance of the customer
- Credit Score: Customer's credit score
- Estimated Salary: Customer's estimated salary
- Has Credit Card: Whether the customer has a credit card (Yes/No)
- Is Active Member: Whether the customer is an active member (Yes/No)
- Number of Products: Total number of products used by the customer

# 📊 Result Interpretation

- Churn Probability: A score between 0 and 1 indicating the likelihood of customer churn.
  - **> 0.5**: The customer is likely to churn.
  - **≤ 0.5**: The customer is not likely to churn.
 
# 📜 License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

# 📬 Contact
Feel free to reach out if you have any questions or suggestions:

Email: dhrumilbhut@gmail.com

X: @[BhutDhrumil](https://x.com/BhutDhrumil)

LinkedIn: [dhrumilbhut](https://www.linkedin.com/in/dhrumilbhut?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)

# 💬 Feedback
Your feedback is valuable! If you check out the project, I'd love to hear your thoughts, ideas for improvement, or even bug reports. Let's make this project better together!
