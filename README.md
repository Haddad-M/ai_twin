# AI Twin: Building a Personality-Capturing Chatbot Using Agentic AI
**Author:** Mariss Haddad

## Abstract
AI Twin is a personality-capturing chatbot built using agentic AI. The system uses OpenAI’s GPT-4.1 and a modular Gradio interface to construct a conversational agent that mirrors a user’s personality, values, and decision-making style.

The pipeline ingests pre-existing user data (e.g., resume, personal statement) and processes it through a series of prompts to extract:

- technical context  
- psychological traits  
- stylistic markers  

These insights generate a rapid-fire, personalized interview conducted in Gradio to deepen the personality profile. Interview results are synthesized into a multifaceted trait representation that powers the AI Twin, enabling text-based conversations that emulate the user’s tone, reasoning patterns, and affective tendencies.

## Evaluation
A reverse Turing test is implemented using a zero-shot classifier (BART-large-MNLI). Both the human and the AI Twin respond to probing questions, and the classifier attempts to distinguish between them.

In practice, the AI Twin built on my data produced answers that were misclassified as human in 2 of 3 trials, demonstrating high fidelity in personality emulation.

## Summary
AI Twin provides an accessible, lightweight framework for agent personalization that integrates psychological modeling with agentic LLM design. It explores the boundaries of human–AI identity blending and offers a foundation for future work in adaptive, user-specific conversational systems.

## Note
I have provided a generic resume and personal statement fabricated by ChatGPT for testing the system. They are intended to be replaced with your desired materials when you run the system.
