# Prediction of  drink quantities in a party using streamlit

This Streamlit app serves as a tool to predict optimal drink quantities for events, leveraging a machine learning model. Here's an overview of its structure and functionality:

Key Features:
User Inputs:

Budget: Total event budget.
Number of Guests: Number of attendees.
# Demographics:
Gender distribution, percentage of non-drinkers, age range.
Event Duration: Hours for which the event will last.
Event Type: Weekend or not, style of the event, type of event (wedding or other).
Backend Processing:

# Scaling:
Uses scaler to standardize inputs before feeding them into the model.
Prediction: A pre-trained model (trained_model) predicts drink quantities based on the input features.
One-Hot Encoding: Encodes categorical variables like style_of_event and type_of_event for model compatibility.


# Responsive UI: 
Uses a form for user input and a spinner for processing, enhancing usability.
# Data Download: 
Provides a button to download predictions as a CSV file.

