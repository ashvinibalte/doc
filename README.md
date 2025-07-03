What is this whole Agent Space about?
You are building an AI-powered assistant specifically for foreign exchange (FX) trade documentation.

The assistant uses a Conversational Playbook (an orchestrated flow of instructions) to:

Guide the conversation

Leverage document retrieval (RAG = retrieval-augmented generation) to pull relevant info from trade documents

Handle clarifications if the question is vague

It is integrated with:

a tool for document search (FXTradeDocumentSearch)

a generative model (Gemini-2.0)

You preview and refine how the agent responds through this interface before deploying it in production.
