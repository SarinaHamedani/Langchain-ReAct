# 🧠 LangChain ReAct Agent
LangChain ReAct Agent is a Python-based implementation that combines the ReAct (Reasoning and Acting) framework with LangChain to create intelligent agents capable of complex decision-making. This project demonstrates how to build agents that can reason through problems, take actions using tools, and iteratively arrive at solutions.

## 🚀 Features
**ReAct Framework:** Integrates reasoning and acting capabilities, allowing agents to think step-by-step and perform actions like API calls or calculations.

**LangChain Integration:** Utilizes LangChain's modular components for building and managing language model applications.

**Custom Callbacks:** Implements callbacks to monitor and control the agent's behavior during execution.

## 📁 Project Structure
**main.py:** The main script that initializes and runs the ReAct agent.

**callbacks.py:** Contains custom callback functions to handle events during the agent's operation.

**Pipfile & Pipfile.lock:** Define the project's dependencies and virtual environment configuration.

## 🛠️ Installation
1. Clone the Repository:
    ```bash
    git clone https://github.com/SarinaHamedani/Langchain-ReAct.git
    cd Langchain-ReAct
2. Activate the Virtual Environment:
Ensure you have Pipenv installed. Then run:
    ```bash
    pipenv shell 
3. Install Dependencies:
    ```bash
    pipenv install


## ⚙️ Usage
1. Set Up Environment Variables:
Create a .env file in the project root and add your OpenAI API key:
    ```ini
    OPENAI_API_KEY=your-api-key-here

2. Run the Agent:
    ```bash
    python main.py
The agent will start and await your input. You can type in queries, and it will reason through them, taking actions as necessary to provide answers.

## 🧪 Example
User: What is the capital of France?

Agent: Let's think step by step...

Agent: The capital of France is Paris.