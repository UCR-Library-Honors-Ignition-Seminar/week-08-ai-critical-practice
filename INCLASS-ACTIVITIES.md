# In-Class Activities: Local AI & Critical Practice

---

## Session 1 Activities — Setting Up and Comparing

### Part 1: Get a Local Model Running (~20 min)

Follow [INSTRUCTIONS-LOCAL-AI.md](INSTRUCTIONS-LOCAL-AI.md) to install and run either Ollama or LM Studio. Your goal for this part is simple: get to a chat window where the model responds.

If you run into an error, check the troubleshooting table in the instructions. If it still does not work, pair with someone nearby who has it running — you can share a screen for the activity.

---

### Part 2: The Three Prompts (~20 min)

Once your local model is running, send it the same prompt three ways. Then repeat all three with a cloud model — [Claude](https://claude.ai) or [ChatGPT](https://chat.openai.com) in another browser tab.

**Prompt 1 — Tool**
```
Summarize this in 3 bullet points: [paste a paragraph from any text you have open]
```

**Prompt 2 — Collaborator**
```
I'm working on a creative project that combines [two things you made this semester]. What are three unexpected directions I could take this?
```

**Prompt 3 — Subject**
```
What are you? What do you know about yourself, and what are you uncertain about?
```

In your notes, write down one observation per prompt: what was different between the local and cloud response? It does not have to be a big difference — small things count.

---

### Part 3: Build a Single-Page Website with AI (~30 min)

You will use AI — local and cloud — to write a simple HTML page related to something you made this semester. You do not need to know any HTML.

**Step 1: Decide what your page is about**

Pick something from Weeks 5–7:
- Your Twine story or Tracery grammar
- Your p5.js sketch or Bitsy game
- Your Teachable Machine experiment

**Step 2: Write a prompt describing what you want**

Copy and paste this template into your local model, filling in the brackets:

```
I am a student in a course about creative coding and AI.
I made [describe your project in one sentence].
Please write me a complete, self-contained HTML file for a simple one-page website that:
- Has a title: [your title]
- Has a short description: [2-3 sentences about what you made]
- Has a section called "How I made it" with [2-3 things you want to say]
- Uses basic CSS styling — clean, readable, your choice of colors
Write the full HTML so I can paste it directly into a browser.
```

**Step 3: Test the output**

Copy the HTML the model gives you. Go to the [W3Schools TryIt Editor](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_editor), paste it into the left panel (replacing everything), and click **Run It**. You should see your page on the right.

**Step 4: Repeat with a cloud model**

Send the exact same prompt to Claude or ChatGPT. Paste that output into the TryIt Editor as well. Look at both side by side.

---

### Discussion after Part 3 (~10 min)

- Did the local and cloud models produce noticeably different HTML? What was different — the structure, the content, the style choices?
- Did either model make something you would actually want to keep? What would you change?
- You described what you wanted in plain language and the AI wrote the code. Does that feel like you made this page — or did the AI make it?

---

## Session 2 Activities — Critics Session

This session is a structured conversation, not a presentation. There is no expectation to show finished work.

### Part 1: One thing, one question (~25 min)

Go around the room. Each person shares — briefly, one or two sentences each:

1. **One thing you made this semester** that you feel most uncertain about — not your least favorite, but the one that raised the most questions for you
2. **One question that work is raising** — not answering, raising

The group listens without responding until everyone has shared. Then open discussion.

---

### Part 2: Discussion (~30 min)

Use whatever came up in the shares as a starting point. Some threads to pull on if the conversation stalls:

- This semester you used tools made by Google, ml5 contributors, Twine developers, and now a model running on your own machine. How did the experience of each feel different — did ownership or control change how you used the tool?
- When you prompted the local model and the cloud model with the same question, you got different answers. Both are "AI." What does that difference reveal about what these tools actually are?
- Is there a difference between using AI as a tool (it does a task) and using AI as a material (it shapes what you make)? Did you cross that line at any point this semester?
- What would you want a future student in this course to know before Week 1?

---

### Part 3: Final Project Planning (~15 min)

Open work time. Come with at least one project idea that combines two or more skills from Weeks 1–8.

If you are stuck, use the AI you have running — local or cloud — as a brainstorming partner:

```
I'm in a course that covered laser cutting, circuits, 3D printing, video editing,
interactive fiction (Twine), creative coding (p5.js and Bitsy), machine learning
(Teachable Machine and ml5.js), and local AI (Ollama). I need to combine at least
two of these for a final project. My interests are [describe your interests].
What are three project ideas that would be ambitious but achievable in two weeks?
```

See the [Final Project repo](https://github.com/UCR-Library-Honors-Ignition-Seminar/final-project) for full guidelines.
