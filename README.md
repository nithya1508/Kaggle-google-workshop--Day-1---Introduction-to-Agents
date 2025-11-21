**Vertex AI Agents – Day 1 Labs**

This repository contains my implementations of the Google Cloud Vertex AI Agents Day-1 hands-on labs. The notebooks demonstrate how to build, configure, and interact with AI agents using Vertex AI Agent Engine, including prompt execution, agent deployment, and asynchronous/streaming queries.

These labs are part of my continuous learning in Cloud AI, Agentic Systems, and Applied Machine Learning.

**Repository Structure**
File	Description
day-1a-from-prompt-to-action.ipynb	Introduces the basics of Vertex AI Agents including project setup, initializing the SDK, prompt execution, synchronous agent queries, and environment configuration.
day-1b-agent-architectures.ipynb	Explores agent architectures, deployed agent retrieval, remote agent interaction, async queries, streaming responses, and architectural patterns.
⚙️ Key Topics Covered
**1. Environment & Project Setup**
Setting up PROJECT_ID

Defining deployed_region

Initializing Vertex AI using vertexai.init()

Handling environment variables and authentication

**2. Agent Engine Basics**
Listing existing agents

Loading a deployed agent programmatically

Executing prompt-based interactions

Understanding input/output structures

**3. Async & Streaming Queries**

Using async_stream_query() for real-time token streaming

Iterating over streamed outputs

Managing user sessions (user_id)

Handling exceptions and async execution patterns

**4. Agent Architectures**

Local vs. remote agents

Modular agent architecture patterns

Interaction flows between components

Best practices for scalable agent design

**5. Troubleshooting & Debugging**

The notebooks include solutions to common issues such as:

NameError: remote_agent is not defined

NameError: deployed_region is not defined

Incorrect indentation

Missing environment configuration

 **Getting Started
Prerequisites**

Python 3.10+

Google Cloud Project

Vertex AI API enabled

Appropriate IAM permissions or service account credentials
📘 Learning Outcomes

After completing these labs, you will understand:

How to initialize and configure Vertex AI Agents

How to run synchronous and asynchronous queries

How to use streaming outputs for real-time response generation

How deployed agents are managed via Agent Engine

How to structure agentic workflows effectively

**🛠 Technologies Used**

Vertex AI

Python

Jupyter/Colab

Google Cloud SDK

Agent Engine (Preview/Beta)

 **License**

This project is licensed under the MIT License.

📬 Contact

If you're interested in AI, analytics, cloud computing, or agentic systems, feel free to connect.

Nithyashree Babu
MSc Business Analytics | AI & Data | Cloud
GitHub:https://github.com/nithya1508 
LinkedIn:https://www.linkedin.com/in/cognitiveinsight/

