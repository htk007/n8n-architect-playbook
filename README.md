# 🏗️ n8n Architect Playbook

An open-source, prompt-driven learning framework and architectural playbook for mastering **n8n** automation using Claude.

![n8n](https://img.shields.io/badge/n8n-FF6D5W?style=for-the-badge&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_3-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## 📖 About the Project

Learning automation tools often consists of simple "drag-and-drop" tutorials. However, as workflows scale, true engineering standards like robust error handling, modularity (sub-workflows), and performance optimization become absolutely essential.

The **n8n Architect Playbook** is an AI-assisted (LLM) learning environment designed to help you master n8n not just as a standard user, but with the discipline of a **Software Architect**. By leveraging Claude's "Projects" feature, you can instantiate a 24/7 expert n8n mentor tailored to a strong engineering background.

## 📂 Repository Contents (Project Memory)

This repository provides 4 core files carefully designed to give your AI mentor continuous context:

1. `ruleset.md`: Your team's architectural standards, coding conventions, and naming protocols for n8n workflows.
2. `learning_path.md`: A theoretical curriculum ranging from core n8n fundamentals to Advanced Agentic AI and Multi-Agent systems.
3. `n8n_practice_list.md`: A hands-on, progressive to-do list of lab exercises to put theory into practice.
4. `learning_experience.md`: Your developer log. A place to document solved "gotchas," milestones, and architectural epiphanies.

## 🚀 How to Use (Setup)

To set up this playbook, you need a **Claude Pro** account (or any LLM interface that supports "Projects" or robust system instruction features).

### Step 1: Create a Project in Claude
1. Navigate to the **Projects** section in the left menu of the Claude interface and create a new project (e.g., `n8n Mastery`).
2. Go to the **Project Instructions**.
3. Copy the contents of the `system_instructions.md` file from this repository and paste it into Claude's instruction box. *(Don't forget to customize the bracketed `[ ]` areas to fit your current goals).*

### Step 2: Upload the Project Memory
1. Download or clone the following 4 files from this repository:
   - `ruleset.md`
   - `learning_path.md`
   - `n8n_practice_list.md`
   - `learning_experience.md`
2. Upload these files to the **Files** (Project Knowledge) section of your Claude project.

### Step 3: Start Learning!
Everything is set up. You can now send your first message to Claude:
> *"Let's begin. Starting with Phase 1 of the Learning Path, explain n8n's 'Array of Items' structure to me as if I were a software architect."*

## 🔄 The Workflow (Continuous Improvement)

This playbook is not static; it evolves as your skills do:

* **Practice:** After teaching you a concept, Claude will prompt you to complete the relevant task in the `n8n_practice_list.md`.
* **Update the Rules:** Whenever you solve a complex problem or establish a new architectural rule together, Claude will generate a new markdown snippet and instruct you to update `ruleset.md` or `learning_experience.md`.
* **Sync the Files:** Copy Claude's updated outputs, update your local markdown files, and re-upload them to your Claude Project. This ensures your mentor's knowledge stays perfectly synced with your progress.

## 🤝 Contributing

This project is open-source. We welcome pull requests (PRs) for new n8n practice tasks (especially for AI/Advanced levels), new architectural rules, or improved system prompts!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingNewRule`)
3. Commit your Changes (`git commit -m 'Add new rule for Webhook auth'`)
4. Push to the Branch (`git push origin feature/AmazingNewRule`)
5. Open a Pull Request

---
*Happy automating with engineering discipline! 🚀*
