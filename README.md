# Conversational Language Understanding with Language Studio

This project demonstrates how to use Azure's Conversational Language Understanding (CLU) service to create and test a natural language processing (NLP) application. The goal of the project is to send instructions to devices such as lights or fans using natural language commands. By leveraging Azure Language Studio, the project highlights how AI can interpret spoken or typed commands and take appropriate actions.

## Overview

AI-powered systems are increasingly expected to understand natural language commands. This project explores how to configure and test a Conversational Language Understanding (CLU) application using **Azure Language Studio**. The project simulates a home automation system capable of recognizing and responding to user commands, such as:

- **"Switch on the light."**
- **"Turn the fan off."**

By configuring intents, entities, and utterances in CLU, the system can classify user input and take appropriate actions.

## Features

- **Intents**: Define the purpose or goal of a command (e.g., `TurnOn`, `TurnOff`).
- **Entities**: Extract specific items or objects from the command (e.g., `fan`, `light`).
- **Utterances**: Train the model with user phrases to recognize intents and entities.
- **Natural Language Understanding**: Use AI models to interpret and respond to user input.
- **Language Studio**: A no-code interface to design and test CLU applications.

## Project Workflow

1. **Create a Resource**:
   - Go to the Azure portal and create an **Azure AI Language** resource.
   - Note down the resource key and endpoint.

2. **Set Up a Project in Language Studio**:
   - Open [Language Studio](https://language.azure.com/).
   - Create a new **Conversational Language Understanding** project.
   - Define intents, entities, and sample utterances for your project.
   - Train the model to recognize intents and entities.

3. **Test the Project**:
   - Use the built-in test interface in Language Studio.
   - Submit sample commands (e.g., "Turn on the light") to see the predicted intents and extracted entities.

4. **Deploy the Model**:
   - Publish the trained model to a prediction endpoint.
   - Use the endpoint in client applications to process user input.

## How It Works

### Core Concepts
- **Utterances**: Examples of user input (e.g., "Switch the fan on").
- **Entities**: Specific items referred to in the input (e.g., "fan" or "light").
- **Intents**: The action or purpose of the input (e.g., `TurnOn` or `TurnOff`).

### Azure's Conversational Language Studio
1. The user enters a natural language command.
2. The CLU model predicts the intent (e.g., `TurnOn`) and extracts relevant entities (e.g., `light`).
3. The application takes the predicted intent and entity to perform an action (e.g., turning on the light).

#### Deploy and test the model

![test](https://github.com/user-attachments/assets/ef2e6c8e-bac0-4244-80ca-8a0c76217b5d)

## Key Learnings

- **Intuitive Language Modeling**: CLU makes it easy to interpret natural language commands using intents and entities.
- **Iterative Training**: Training and testing the model is an iterative process that refines accuracy.
- **No-Code AI Tools**: Language Studio simplifies the creation of language models without requiring programming skills.
- **Practical Use Cases**: The project can be extended for smart home automation, customer service bots, and more.

## References

https://learn.microsoft.com/en-us/training/modules/create-language-model-with-language-understanding/4-exercise-create-language-understanding-application

## Acknowledgments

- **Azure Language Studio**: For providing a user-friendly interface to build and test the CLU application.
- **Microsoft Learn**: For resources and tutorials on Azure AI services.
