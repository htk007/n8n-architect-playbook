# n8n Learning Path: Beginner to Advanced Architecture

This document outlines the theoretical roadmap for mastering n8n.

## Phase 1: Core Fundamentals
- [ ] n8n Architecture: How it works under the hood (Node.js based, Execution Engine).
- [ ] The n8n Data Structure: Understanding the core concept of "Array of Items" (`[{json: {...}}]`).
- [ ] Triggers vs. Regular Nodes: Polling vs. Webhooks.
- [ ] Execution Modes: `Run Once for All Items` vs. `Run Once for Each Item`.

## Phase 2: Data Manipulation & Logic
- [ ] The `Item Lists` Node: Splitting, aggregating, and sorting data without writing code.
- [ ] The `Set` (Edit Fields) Node: Modifying data structure and using expressions.
- [ ] The `Code` Node: Writing custom JavaScript for complex data transformations.
- [ ] Routing: `Switch`, `If`, and `Merge` nodes for controlling workflow logic.

## Phase 3: Integrations & External Systems
- [ ] The `HTTP Request` Node: Making GET/POST requests, handling headers, query parameters, and pagination.
- [ ] Webhook Configurations: Receiving incoming data, handling authentication, and dynamic responses.
- [ ] Credential Management: Securely storing and using API keys and OAuth2 tokens.

## Phase 4: Enterprise Architecture & Reliability
- [ ] Sub-workflows: Using the `Execute Workflow` node for modularity and reusability.
- [ ] Error Handling Strategies: `Error Trigger` nodes, `try/catch` in Code nodes, and "Continue on Fail".
- [ ] State Management: Using the `Static Data` feature to save states between workflow runs (e.g., remembering the last fetched ID).

## Phase 5: Advanced & AI Ecosystem (Agentic AI)
- [ ] Advanced AI Nodes: Connecting LLMs (OpenAI, Anthropic).
- [ ] Memory Management: Window buffer memory and chat history nodes.
- [ ] Multi-Agent Workflows: Designing flows where different AI agents perform specialized tasks and pass data.
