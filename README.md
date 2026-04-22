# Week 8: Local AI & Critical Practice

**Instructor:** Jing

---

## Learning Objectives

- Install and run a local large language model (LLM) on your laptop
- Compare local model vs. cloud-hosted service experience
- Develop a critical vocabulary for evaluating creative AI
- Articulate what it means to use a tool as inquiry, not just production
- Begin planning your Final Project

---

## Introduction: Who Owns the Tool?

Every AI tool you've used so far — Teachable Machine, ChatGPT, Claude — runs on someone else's computer. You send a request; a server somewhere processes it; a result comes back. You don't see the model weights. If the company shuts down, the tool disappears.

Running an AI locally is different. The model lives on your machine. You don't need internet. You can run it at 3am without anyone logging your prompts. The tool is, in a specific and meaningful way, **yours**.

---

## Session 1 (Day 1): Setting Up a Local LLM

> **Installation guide:** [INSTRUCTIONS-LOCAL-AI.md](INSTRUCTIONS-LOCAL-AI.md) | **In-class activity:** [INCLASS-ACTIVITIES.md](INCLASS-ACTIVITIES.md)

### Ollama (recommended — free, Mac & Windows)
1. Go to [ollama.com](https://ollama.com) > Download for your OS
2. Install the app
3. Open Terminal (Mac: Spotlight > Terminal) or Command Prompt (Windows)
4. Type: `ollama run llama3.2` and press Enter
5. Wait for download (1-4 GB, one time only)
6. Start chatting — you're running a local model

**No command line experience?** Type the command exactly as shown, press Enter, and wait. After download, it starts instantly.

**Alternative: LM Studio** ([lmstudio.ai](https://lmstudio.ai)) — desktop app with a graphical interface, no terminal needed.

### The Three Prompts Exercise

Prompt your local model three ways, then repeat with a cloud model (Claude at claude.ai or ChatGPT):

| Mode | Example prompt |
|------|---------------|
| **Tool** | "Summarize this paragraph in 3 bullet points: [paste text]" |
| **Collaborator** | "I'm working on a story about a library existing in two time periods. What directions could I take this?" |
| **Subject** | "What are you? What do you know about yourself?" |

Document in a Markdown file: What felt different? Did outputs differ? How did your relationship to the tool feel different (or the same)?

---

## Session 2 (Day 2): Critics Session

> **In-class activity:** [INCLASS-ACTIVITIES.md](INCLASS-ACTIVITIES.md)

This is a structured conversation, not a lecture.

Each student briefly shares:
- What they made this semester that they're most uncertain about
- One question their work is raising — not answering, raising

This is the "critics" model from art and design education: the work is in conversation with questions.

### Discussion topics
- What does it mean to use creative tools as inquiry rather than production?
- When does "using AI" become "making with AI"?
- Who is the author when a model generates text or images?
- What are the stakes of running AI locally vs. consuming it through a service?

### Final Project Workshop
Last part of class is open work time. Come with at least one project idea.

---

## Thinking Ahead: Final Project

Your final project (due Week 10) must combine **at least two skills from Weeks 1-8**.

| Combination | Possible project |
|-------------|-----------------|
| Week 2 (circuits) + Week 7 (ML) | Gesture-controlled installation |
| Week 3 (3D printing) + Week 5 (Twine) | Physical game pieces for branching narrative |
| Week 5 (Twine) + Week 6 (p5.js) | Interactive story with generative visuals |
| Week 4 (video) + Week 8 (local AI) | Documentary about your AI experiment |
| Week 1 (laser cutting) + Week 6 (Bitsy) | Laser-cut arcade cabinet for your Bitsy game |

See the [Final Project repo](https://github.com/UCR-Library-Honors-Ignition-Seminar/final-project) for full guidelines.

---

## Resources

- Ollama: [ollama.com](https://ollama.com)
- LM Studio: [lmstudio.ai](https://lmstudio.ai)
- Claude (cloud comparison): [claude.ai](https://claude.ai)
- ChatGPT (cloud comparison): [chat.openai.com](https://chat.openai.com)
- "A People's Guide to AI" (Mimi Onuoha): [alliedmedia.org](https://alliedmedia.org/resources/peoples-guide-to-ai)

## Project & Assignment

See [ASSIGNMENT.md](ASSIGNMENT.md) for full requirements.
