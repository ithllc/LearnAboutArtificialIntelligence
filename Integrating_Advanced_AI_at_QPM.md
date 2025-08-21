### **Playbook: Integrating Advanced AI at QPM**

*This playbook provides a simple framework and examples for deploying the technologies from this course. It is a guide for turning concepts into action.*

**1. Choosing Your AI Workforce: A Two-Model Strategy**

At QPM, we will use a hybrid approach. We will use a powerful **Large Language Model (LLM)** for strategic tasks like market analysis, content creation, and complex R&D brainstorming. For our factory floor, we will deploy dozens of specialized **Small Language Models (SLMs)** for real-time tasks like summarizing machine errors, voice commands for equipment, and initial quality control checks. This balances power with efficiency and cost.

> **Get AI Help to Strategize:**
> **Sample Prompt:** "We need to analyze customer feedback from emails and surveys. Would a Large Language Model or a Small Language Model be better for this task? Explain your reasoning in a short paragraph."

**2. The QPM Prompting Guide: The "Clarity is Kindness" Protocol**

Every instruction given to an AI at QPM must follow a simple template: Role, Task, Context, and Format. For example, instead of "write about our new gear," we will use: "**Role:** You are a marketing expert. **Task:** Write a product description. **Context:** The product is a new, lightweight, high-tensile steel gear for the aerospace industry. **Format:** A professional, one-paragraph description." This ensures we get high-quality, consistent results every time.

> **Get AI Help to Build Prompts:**
> **Sample Prompt:** "I need to ask an LLM to generate a safety checklist for operating our new CNC machine. Using the 'Role, Task, Context, Format' structure, create an effective prompt for me."

**3. Deploying Our First AI Agent: The "Smart Inventory Manager"**

Our first agentic AI project will be an inventory manager. We will give it one clear goal: "Ensure we never run out of the top 20 critical manufacturing components." We will provide it with tools: read-only access to the inventory database, access to the supplier ordering system API, and the ability to send email alerts. All orders above a certain threshold will require human approval, providing a crucial human-in-the-loop safety control.

> **Get AI Help to Scope Agents:**
> **Sample Prompt:** "We want to create an AI agent to manage our factory's energy consumption. What are three key 'tools' (like access to data or control over systems) that this agent would need to do its job effectively?"

**4. Red Teaming Our Agents: The "Assume It Will Go Wrong" Test**

Before deploying the Smart Inventory Manager, our red team will test it. They will simulate scenarios to challenge its logic, such as a supplier's API providing incorrect data or two critical components running low at the exact same time. They will also attempt prompt injection attacks on its alert system to see if it can be tricked. This proactive testing is mandatory for any autonomous system at QPM to ensure we have built robust and reliable agents.

> **Get AI Help to Red Team:**
> **Sample Prompt:** "Act as a red teamer. My AI agent's goal is to automatically re-order supplies when they are low. Brainstorm three scenarios where its simple logic could fail and lead to a negative business outcome (e.g., ordering the wrong thing, ordering too much)."
