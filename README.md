# Online-Payments-Fraud-Detection-with-Machine-Learning
The introduction of online payment systems has helped a lot in the ease of payments. But, at the same time, it increased in payment frauds. Online payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting online payment fraud is very important for credit card companies to ensure that the customers are not getting charged for the products and services they never paid. I will take you through the task of online payments fraud detection with machine learning using Python.
For this task, I collected a dataset (https://www.kaggle.com/ealaxi/paysim1/download) from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:
            1. step: represents a unit of time where 1 step equals 1 hour
            2. type: type of online transaction
            3. amount: the amount of the transaction
            4. nameOrig: customer starting the transaction
            5. oldbalanceOrg: balance before the transaction
            6. newbalanceOrig: balance after the transaction
            7. nameDest: recipient of the transaction
            8. oldbalanceDest: initial balance of recipient before the transaction
            9. newbalanceDest: the new balance of recipient after the transaction
            10. isFraud: fraud transaction
