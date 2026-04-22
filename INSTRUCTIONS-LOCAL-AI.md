# Instructions: Running a Local AI

This guide walks you through installing and running a large language model (LLM) directly on your laptop — no internet required after setup, no account needed, no one logging your prompts.

**Two options — pick one:**
- **Ollama** (recommended): runs in the Terminal; slightly more setup but more flexible
- **LM Studio**: desktop app with a graphical interface, no Terminal required

---

## Option A: Ollama

### Step 1: Download Ollama

1. Go to [ollama.com](https://ollama.com)
2. Click **Download**
3. Download the version for your operating system (Mac or Windows)

### Step 2: Install Ollama

**On Mac:**
1. Open the downloaded `.zip` file — it extracts an app called **Ollama**
2. Drag **Ollama** into your Applications folder
3. Double-click to open it — you will see a small llama icon appear in your menu bar (top right of screen)

**On Windows:**
1. Run the downloaded `OllamaSetup.exe` file
2. Follow the installer — it will install automatically
3. After installation, Ollama runs in the background (look for it in the system tray, bottom right)

### Step 3: Open the Terminal

You will type one command to start the model. This is the only time you need the Terminal.

**On Mac:**
1. Press **Cmd + Space** to open Spotlight
2. Type `Terminal` and press **Enter**
3. A white or black window with a text cursor appears — this is the Terminal

**On Windows:**
1. Press **Win + R** (the Windows key and R at the same time)
2. Type `cmd` and press **Enter**
3. A black window with a text cursor appears — this is the Command Prompt

### Step 4: Download and Run a Model

In the Terminal window, copy and paste the following line exactly, then press **Enter**:

```
ollama run llama3.2
```

> **What happens next:** Ollama will download the model — about 2 GB, one time only. This takes a few minutes depending on your internet speed. You will see a progress bar. Do not close the window.

When the download finishes, you will see:

```
>>> Send a message (/? for help)
```

This means the model is running. Type anything and press **Enter** to chat.

### Step 5: Chat with the Model

Type your message after `>>>` and press **Enter**. The model will respond in the same window.

**To exit when you are done:**

Copy and paste this and press **Enter**:
```
/bye
```

Or press **Ctrl + D** (hold the Ctrl key and press D).

---

### If Something Goes Wrong

| Problem | Fix |
|---------|-----|
| `ollama: command not found` | Ollama is not installed — go back to Step 1. On Mac, make sure you opened the app at least once after dragging it to Applications. |
| Download is very slow | This is normal for 2 GB — leave it running and check back in 10–15 minutes |
| The window closes immediately | Reopen Terminal and try again — the model may have downloaded already; `ollama run llama3.2` will start it instantly the second time |
| Out of memory error | Try a smaller model: replace `llama3.2` with `llama3.2:1b` |

---

## Option B: LM Studio (No Terminal Required)

LM Studio is a desktop application with a graphical interface — no Terminal needed.

### Step 1: Download and Install

1. Go to [lmstudio.ai](https://lmstudio.ai)
2. Click **Download** for your operating system
3. Install the application and open it

### Step 2: Download a Model

We will use the same model as Ollama — **Llama 3.2 3B** — which is about 2 GB and runs on most laptops. Avoid other Llama models in the search results; many are 40+ GB and will not run on a standard laptop.

1. Click the **Search** icon (magnifying glass) in the left sidebar
2. In the search bar, type exactly:
   ```
   llama3.2-3b-instruct
   ```
3. Look for the result called **Llama-3.2-3B-Instruct-GGUF** by **lmstudio-community**
4. Click it to open the model page — confirm the file size shown is around **2 GB** before downloading
5. Click **Download**

### Step 3: Start Chatting

1. Click the **Chat** icon in the left sidebar
2. At the top of the screen, click **Select a model to load** and choose the model you downloaded
3. Wait a few seconds for it to load, then type in the chat box at the bottom

---

## Using Both: Local vs. Cloud

Once your local model is running, you can compare it to a cloud-hosted model side by side:

| Local (Ollama or LM Studio) | Cloud |
|---|---|
| Runs on your computer | Runs on a company's server |
| No internet required after setup | Requires internet |
| Private — prompts are not logged | Prompts may be used for training |
| Slower on most laptops | Faster |
| Free, open source | Free tier with limits |

For the in-class activity, you will use **both** — see [INCLASS-ACTIVITIES.md](INCLASS-ACTIVITIES.md).
