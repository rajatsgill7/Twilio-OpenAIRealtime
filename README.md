# Twilio-OpenAIRealtime
An application to make phone calls and connect to a AI assistant who will answer your questions in realtime

Sign up on Twilio and buy a phone number 
Sign up on OpenAI and create a project and generate a API KEY
Setup ngrok to listen to the port your python app is running on

On twilio console under 'Active Numbers' select the number you want to use and in the Voice configuration when call comes in set it to webhook and sent the URL to your ngrok url , appended with your enpoint ( /incoming-call )

Run your python app python app.py

run ngrok http {PORT app.py is running on )
