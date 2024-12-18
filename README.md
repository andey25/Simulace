# Simulace  
Simulace is an AI-powered platform that prepares lawyers for negotiations by simulating realistic case outcomes. Users upload case files in PDF format, which are analyzed alongside prior cases to extract critical legal insights. The platform simulates negotiation scenarios to create an advanced AI persona of opposing counsel, integrated with GPT-4 voice capabilities for verbal practice.  

## **High Level Overview**  
- **Case Analysis**: Extract legal data and relevant strategies by cross-referencing past cases and the current case.  
- **Simulated Negotiations**: Generate 100 potential negotiation paths between two AI agents representing opposing parties to explore various strategies and outcomes.  
- **AI Persona Integration**: Use the results to create an intelligent AI persona, which lawyers can verbally negotiate against via GPT-4 voice mode.  

## **RAG Engine**  
- Simulace leverages a **contextual summarization** technique inspired by Anthropic to efficiently extract legal strategies, outcomes, and precedents.  
- All information is stored in a **Pinecone vector database** for fast and accurate retrieval.  

## **Simulation Infrastructure**  
- **Agent Dynamics**: Two agents simulate the negotiation process, with each representing one party (e.g., Company A and Company B).  
- **Parallel Simulations**: The platform runs 100 negotiation pathways simultaneously, testing different approaches and responses.  
- **Outcome Analysis**: Each path is evaluated to identify risks, successful strategies, and optimal outcomes for preparation.  

## **Intelligent AI Persona Creation**  
- **Persona Development**: The insights from the simulations are synthesized into a highly skilled AI persona that mimics an experienced opposing counsel.  
- **Adaptive Behavior**: The persona adjusts its responses dynamically to match the user’s negotiation style, providing realistic, challenging practice.  

## **Voice Bot Integration**  
- **Realistic Conversations**: The AI persona is connected to the GPT-4 voice interface, enabling natural, spoken negotiations.  
- **Negotiation Practice**: Lawyers engage in live back-and-forth interactions, encountering counteroffers, challenges, and alternative strategies that mirror real-world negotiations.  


## Get Started
Clone the Repository: Clone the project.
Install Dependencies: Run pip install -r requirements.txt.
Set API Keys: Add OpenAI and Pinecone API keys to the .env file.
Run Backend: Execute python server.py in the root directory.
Start Frontend: Go to the UI/specter folder and run npm run dev.

## Credits
Frontend inspired by Harvey.ai
Voice capabilities powered by OpenAI GPT-4
Hosted via Outspeed
Special thanks to Cursor for support
