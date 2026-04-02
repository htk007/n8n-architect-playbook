# n8n Practice Tasks: Hands-on Projects

This is a living to-do list of practical workflows to build, ordered by difficulty. 

## Beginner Level
- [ ] **Task 1 (Echo Webhook):** Create a Webhook trigger that receives a JSON payload and returns the exact same payload as a response.
- [ ] **Task 2 (Data Filter):** Fetch dummy data from a public API (like JSONPlaceholder), filter users by a specific criteria using the `If` node, and format the output.
- [ ] **Task 3 (Simple Notification):** Create a scheduled trigger (Cron) that sends a daily "Good Morning" message to a Slack/Discord channel or via Email.

## Intermediate Level
- [ ] **Task 4 (API Pagination):** Build a workflow using the `HTTP Request` node that fetches multiple pages of data from an API until all records are retrieved.
- [ ] **Task 5 (Code Node Transformation):** Receive a deeply nested, messy JSON object via Webhook and use the `Code` node with JavaScript to flatten it into a clean, single-level array of items.
- [ ] **Task 6 (Sub-workflow Orchestration):** Create a "Main" workflow that triggers an "Email Formatting" sub-workflow, passes data to it, and waits for the formatted HTML response.

## Advanced Level (Architecture & AI)
- [ ] **Task 7 (Global Error Handler):** Build an independent Error Workflow that catches failures from other workflows, formats the error details, and sends an alert. Attach this as the default error handler for your workspace.
- [ ] **Task 8 (Stateful Polling):** Build a workflow that checks an API for new items every hour. Use n8n's `getStaticData()` to remember the last processed ID so it only processes truly new items.
- [ ] **Task 9 (Basic AI Agent):** Create an AI workflow that receives a user prompt, uses a tool/function to fetch real-time data (e.g., weather or stock price), and returns a natural language response based on that data.
