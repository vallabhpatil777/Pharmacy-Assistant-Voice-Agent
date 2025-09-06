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
git clone https://github.com/vallabhpatil777/pharmacy-assistant-voice-agent.git
cd pharmacy-assistant-voice-agent
```

### Run ngrok server

```bash
ngrok http 5000
```

### Run Application

```bash
uv run ./main.py
```
