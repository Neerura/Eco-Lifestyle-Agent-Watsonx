# Eco-Lifestyle-Agent-Watsonx
An Eco Lifestyle Agent powered by RAG on IBM watsonx Orchestrate.
# Eco Lifestyle Agent (IBM watsonx Orchestrate)

An AI-driven Eco Lifestyle Agent powered by **RAG (Retrieval-Augmented Generation)** built on **IBM watsonx Orchestrate**. This assistant empowers users to adopt greener lifestyles by fetching sustainable tips, waste management guidelines, and everyday green habits from a custom knowledge base.

## 🚀 Features
- **RAG Architecture**: Pulls verified information directly from an uploaded custom knowledge base file (`eco_friendly_lifestyle_knowledge_base.pdf`).
- **Natural Language Understanding**: Uses the default watsonx Orchestrate AI model to interpret user queries.
- **Actionable Guidance**: Provides clear, cost-effective, and encouraging steps for sustainable living.

## 📁 Repository Structure
- `eco_friendly_lifestyle_knowledge_base.pdf`: The custom knowledge corpus uploaded to the agent.
- `README.md`: Project documentation.

## 🛠️ How It Was Built (Step-by-Step)
1. **Profile Configuration**: Set up agent details and tailored the greeting instructions within the 100-character welcome limit.
2. **Knowledge Base Feeding**: Linked the knowledge source using an intuitive description to establish the RAG lookup pipeline.
3. **Behavior Settings**: Specified strict instructional guardrails ensuring an optimistic, non-judgmental, and practical persona.
4. **Testing & Deployment**: Verified conversational behavior under the **Talk to Agent** debugger panel and successfully deployed.

## 💬 Sample Prompts Handled
- *"What should I do with my home generated waste?"*
- *"What is an eco friendly lifestyle looks like?"*
- *"What small changes and habits should I adopt to contribute to nature?"*
