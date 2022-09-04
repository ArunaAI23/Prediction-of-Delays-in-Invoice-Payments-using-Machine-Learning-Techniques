# Prediction-of-Delays-in-Invoice-Payments-using-Machine-Learning-Techniques
Accounts Receivable (AR), is the most valuable asset of an organization. If it is not managed effectively, it can cause the firm serious financial hardships. To gain an understanding of AR, it is necessary to recognize data patterns in order to forecast whether an invoice will be paid on time or will experience a delay. It is extremely important for large organizations that deal with thousands of vendors to fulfill their service level agreements with them to avoid penalties.

**Purpose**

The purpose of this project is to present a supervised modeling solution that can be used to build models for predicting the payment outcomes of newly created invoices, thus enabling collection actions tailored for each invoice or customer. Since this is a classification problem, an ensemble method of Random Forest and Extreme Gradient Boosting algorithms has been applied and has achieved an accuracy of 81%, if an invoice will be paid on time or not and can
provide estimates of the magnitude of the delay which can improve the prioritization of customers and facilitates the daily work of collection personnel. 


**How to execute**

In order to execute the code, upload the "Historical Records" and "New Records" excel files. 

**Application**


Project demo can be done on https://arunaproject.pythonanywhere.com/. The application predict the delays of invoice payments in the output file. 
Choose the "Predict" option and click on "Run both classifier"
Upload "New Records" excel file to predict the delay in payments and categorization of invoices into the delay buckets. Invoice delays in weeks has been capped to 10 weeks. 
Click on "Train" for prediction. The output files provide the delay in weeks for each records. 

This can help the collection team to proactively follow up for payments well in advance to reduce the delays.


