# Forex Agent
The Forex Agent is an open-source app designed to fetch the daily forex rate of a certain currency pair and send it as a WhatsApp message. The agent runs entirely on DBOS cloud and is scheduled to execute daily at 9:00 AM using Twilio for WhatsApp notifications. This project is lightweight, cost-effective, and ideal for staying updated with forex rates.

# Features
* Fetches JPY to INR forex rates from Google Finance via web scraping.
* Sends daily WhatsApp alerts using Twilio API.
* Scheduled execution at 9:00 AM every day using DBOS cloud.
* Fully automated and open-source.
  
# Tools Used 
1) Twilio : Provides programmable communication tools for making and receiving phone calls, sending and receiving text messages, and performing other communication functions using its web service APIs
2) DBOS Cloud : Deploys the app and executes the forex alert communication based on the specified time intervals

# Prerequisites
- Python: Version 3.8 or higher.
- Twilio Account:
  - Sign up for Twilio and set up a WhatsApp sandbox.
  - Get your Twilio Account SID and Auth Token.
- DBOS Cloud Account:
  - Create an account on DBOS cloud to host and schedule the script.
- Dependencies:
  - requests
  - beautifulsoup4
  - twilio
 
# Contact
For questions or support, please contact:
- Name: Tejdeep Reddy Hunabad
- Email: teja1494reddy@gmail.com
- GitHub: tejdeep94
