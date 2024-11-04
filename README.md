Coffee Shop Customer Service Chatbot 

Welcome to the Coffee Shop Customer Service Chatbot project! This repository provides everything you need to build an AI-powered chatbot that enhances customer experiences in a coffee shop app. Using Large Language Models (LLMs), Natural Language Processing (NLP), and RunPod's infrastructure, our chatbot can help take orders, answer menu questions, and make personalized recommendations—all within a React Native mobile app.

Project Goals

The aim of this project is to develop an intelligent chatbot capable of:
- Real-Time Interactions: Engage with customers as they place orders.
- Detailed Menu Assistance: Provide answers about menu items, including ingredients and allergens, using a Retrieval-Augmented Generation (RAG) system.
- Personalized Recommendations: Suggest products based on user preferences through market basket analysis.
- Streamlined Order Process: Guide customers step-by-step to ensure accurate order details.
- Safe Interactions: Filter out irrelevant or harmful queries with a Guard Agent.

 Learning Outcomes

 By participating in this project, you will gain practical skills in:
 - Deploying a personal LLM with RunPod.
 - Setting up an agent-based architecture with specialized agents for various tasks.
 - Implementing a vector database for menu and product data storage.
 - Utilizing Retrieval-Augmented Generation (RAG) for precise responses.
 - Training and deploying a recommendation engine.
 - Creating a React Native app that integrates this dynamic chatbot.

Core Agents in the System

This chatbot employs a modular architecture where each agent specializes in specific functions:
- Guard Agent: The first line of defense, filtering incoming queries to ensure they are safe and relevant.
- Order Taking Agent: Helps customers place orders, using advanced prompt engineering for logical interaction and accurate order gathering.
- Details Agent (RAG System): Delivers specific information about menu items, accessing a vector database for quick, accurate answers.
- Recommendation Agent: Analyzes user orders and suggests complementary products to enhance the customer experience.
- Classification Agent: Identifies the intent behind customer queries, routing them to the appropriate agent for efficient handling.

Interaction Flow

The agents work together in a structured pipeline to process user inquiries: 
- A customer query is evaluated by the Guard Agent.
- If the query is appropriate, the Classification Agent determines its intent (e.g., placing an order, seeking details, or requesting a recommendation).

The query is directed to the relevant agent:
- The Order Taking Agent addresses order-related inquiries and may refer to the Recommendation Agent for additional suggestions.
- The Details Agent retrieves specific information about menu items.
- The Recommendation Agent offers product suggestions based on the customer's current selections.

The React Native Coffee Shop App serves as the user-friendly interface for customers to engage with the chatbot and explore menu options.
Key Features 
- Landing Page: An inviting entry point to the coffee shop experience.
- Home Page: Showcases featured menu items and product categories.
- Item Details Page: Offers in-depth descriptions, including ingredients and allergens.
- Cart Page: Lets users review and modify their orders before checkout.
- Chatbot Interface: Facilitates direct interaction with the AI chatbot for assistance and inquiries.
