# Pharmacy Assistant Voice Agent  

A voice-enabled AI assistant for pharmacies that can **look up order details**, **fetch medicine information**, and provide insights on **availability, usage, and cost** through natural voice interactions.  

This project integrates **speech-to-text, telephony, and AI-driven tool-calling** to create a seamless pharmacy assistant experience.  

---

## Features  
- **Voice Interaction** – Users can call and interact with the agent in natural language.  
- **Order Lookup** – Fetch order details by order ID or customer details.  
- **Medicine Information** – Get usage guidelines, availability, and pricing of medicines.  
- **Tool Calling** – Dynamically trigger functions to handle pharmacy-specific tasks.  
- **Cloud-Friendly** – Works with ngrok and Twilio for real-time voice calls.  

---

## Tech Stack  
- **Python** – Backend logic and API integration  
- **Deepgram** – Speech-to-Text transcription  
- **Twilio** – Voice calling and telephony integration  
- **ngrok** – Expose local server for testing voice calls  
- **UV** – Python Package Manager  
- **Tool Calling** – For dynamic workflows and task execution  

---
### Clone repository

```bash
git clone https://github.com/vallabhpatil777/Pharmacy-Assistant-Voice-Agent.git
cd pharmacy-assistant-voice-agent
```

### Setup API keys for Ngrok and Deepgram 

Ngrok : https://ngrok.com
Deepgram : https://deepgram.com
Twilio : https://www.twilio.com/en-us?utm_source=google&utm_medium=cpc&utm_term=twilio&utm_campaign=G_S_EMEA_Brand_UK&cq_plac=&cq_net=g&cq_pos=&cq_med=&cq_plt=gp&gad_source=1&gad_campaignid=21663289437&gbraid=0AAAAADcHgwVdXIdwxdpjHM9je-0GukDBw&gclid=CjwKCAjwt-_FBhBzEiwA7QEqyFG9E00xQU9QyHubU34ih7n8UtH16caXDDmQXCeqf2-0__kplsPLlxoC10oQAvD_BwE

### Run ngrok server

```bash
ngrok http 5000
```

### Run Application

```bash
uv run ./main.py
```
