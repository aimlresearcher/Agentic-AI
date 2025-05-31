# Building an AI Agent Using the Agent Loop

This lesson explains how to turn a simple conversation with an AI into a fully autonomous agent that can take actions, make decisions, and adapt to new information. The key concept here is the **agent loop**, a simple but powerful programming structure that allows an AI to operate step-by-step until it completes a task.

## From Chat to Autonomous Agent

### The Problem
- Manual interaction is slow and inefficient.
- We want the AI to **act** on its own after receiving a task.

### The Goal
- Give the AI a task (like "help me add a travel expense").
- Let it figure out the steps and complete the task by interacting with a computer system automatically.

## What Is an Agent Loop?

An **agent loop** is a repeated process that lets the AI:
1. Generate a plan or action.
2. Execute that action.
3. Get feedback from the result.
4. Use that feedback to decide the next step.

### Simple Example: Cooking Instructions
- You say: *"Help me cook this, one step at a time."*
- AI: *"Get these ingredients."*
- You: *"I'm out of beans."*
- AI: *"Skip the beans or use corn instead."*

The AI adapts based on what you tell it. That’s the agent showing **agency**—it makes decisions and adjusts its plan.

## How the Loop Works

Here's the basic process for an AI agent loop:

1. **Construct a Prompt**  
   - Example: *"Add a travel expense. Here are the available actions..."*

2. **Send the Prompt to the Language Model**  
   - The AI responds with an action to take.

3. **Parse the Response**  
   - Extract the specific action from the AI’s reply (like "call this API").

4. **Take the Action**  
   - The system executes the action (e.g., making an API call or updating a file).

5. **Collect Feedback**  
   - Example: response message, HTTP status code, or error message.

6. **Loop or Stop**  
   - Decide if the loop should continue.
   - If yes, build a new prompt with the latest feedback added and go back to Step 1.

### Agent Loop in Action

Imagine you're logging a travel expense. Here's how the loop could look:

1. **Initial Prompt**: "Add travel expense."
2. **AI Response**: "Check if an entry already exists."
3. **System Action**: Queries the spreadsheet.
4. **Feedback**: "No entry found."
5. **Next AI Response**: "Add a new row with the following details..."
6. **System Action**: Adds the row.
7. **Feedback**: "Row added successfully."
8. **Loop Ends**: Task complete.

Each step builds on the last. The prompt grows as feedback is added.

## Key Benefits

- **Autonomy**: Once the task is given, the AI can act on its own.
- **Adaptability**: It changes plans when things don’t go as expected.
- **Scalability**: The same loop structure can work for many different tasks.

## Practical Use Cases

- Adding expenses
- Booking meetings
- Updating records
- Answering customer service queries

## Summary of the Six Core Steps

1. **Construct the prompt**  
   Design the instructions for the AI carefully.

2. **Send to the LLM**  
   Let the model generate a response.

3. **Parse the response**  
   Understand what the AI wants to do.

4. **Take the action**  
   Perform the task on the system.

5. **Get the feedback**  
   Gather results or errors from the action.

6. **Repeat or finish**  
   Continue the loop or stop if the task is done.

This simple structure is the foundation of most powerful AI agents.

---

## Glossary

- **Agent Loop**: A repeated cycle where the AI chooses an action, performs it, checks the result, and decides what to do next.
- **Agency**: The ability of an AI to make decisions and adapt to changing situations.
- **Prompt**: The instruction or message you give to the AI.
- **Parse**: To break down and understand the AI’s response in a way a computer can use.
- **API (Application Programming Interface)**: A way for software to talk to other software.
- **Transformer Model**: A type of AI model that's very good at understanding and generating language.
- **LLM (Large Language Model)**: AI trained on large amounts of text to understand and produce human-like language.
