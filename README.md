# bitcoin_price_notification

Bitcoin Price Notification in Python
Introduction
Welcome to the Bitcoin Price Notification Python program! This program fetches the latest bitcoin price using the Coinbase API and sends desktop notifications when the price reaches a specified threshold. It helps you stay updated with the current bitcoin price and get notified when it hits a target value.

Requirements
This program requires Python 3.x to run.

You can install the required libraries using pip:

Copy code
pip install requests plyer
How to Use the Bitcoin Price Notification
Clone or download the repository to your local machine.
Navigate to the project directory containing the Python script (bitcoin_price_notification.py).
Set your desired price threshold by modifying the price_threshold variable in the script.
Set the interval for checking the price (in minutes) by modifying the interval_minutes variable.
Run the bitcoin_price_notification.py script using the following command:
Copy code
python bitcoin_price_notification.py
The program will continuously check the bitcoin price at the specified interval and send a desktop notification if the price reaches or exceeds the threshold.
Program Description
The Bitcoin Price Notification program fetches the latest bitcoin price from the Coinbase API and uses the plyer library to send desktop notifications. It checks the bitcoin price at regular intervals and sends a notification if the price is equal to or higher than the specified threshold.

Customization
You can customize the price_threshold variable to set your desired price threshold for receiving notifications.
Adjust the interval_minutes variable to set the frequency of price checks (in minutes).
..

