# 🚀 AI CODER DENNIS

![Dennis: AI-Powered Full-Stack Web Development in the Browser](https://raw.githubusercontent.com/JayashBhandary/Dennis/refs/heads/main/dennisgithub%20copy.png)

Welcome to **Dennis** – your blazing-fast, open-source 🧠👨‍💻 **AI coding assistant** for full-stack development **right in your browser**!

✨ With Dennis, you can choose your favorite **LLM** for every prompt — including:
- 🔮 OpenAI
- 🧠 Anthropic
- 🔧 Ollama
- 🌈 Gemini
- ⚡️ Groq
- 🤖 LM Studio
- 🦙 Mistral
- 🚀 xAI
- 🧬 HuggingFace
- 🔍 DeepSeek
- 🧭 OpenRouter

...and you can even extend it to any other model supported by the **Vercel AI SDK**!

---

📚 **Check out the [Dennis Docs](https://github.com/JayashBhandary/Dennis)** for official installation instructions and more!

💬 Also, don’t miss the **pinned post in our community** – packed with resources to help you run and deploy Dennis like a pro.

---

🛠️ **Originally created by [Jayash Bhandary](https://www.instagram.com/jayashbhandary_/)**, Dennis has quickly grown into a passionate, global community effort to build the **BEST** open-source AI dev tool out there!

---

## 📑 Table of Contents

- [🌍 Join the Community](#join-the-community)
- [📌 Requested Additions](#requested-additions)
- [✨ Features](#features)
- [🔧 Setup](#setup)
- [🚀 Run the Application](#running-the-application)
- [📜 Available Scripts](#available-scripts)
- [🤝 Contributing](#contributing)
- [❓ FAQ](#faq)

---

## 🧠 Project Management

Dennis is a growing, community-driven initiative. Our core team is committed to organizing the project so contributors like YOU 🚀 can easily jump in, explore active development areas, and make an impact!

---

## 📌 Requested Additions

✅ means already implemented!  
Here's what the community has helped build so far:

- ✅ OpenRouter Integration  
- ✅ Gemini Integration  
- ✅ Autogenerate Ollama models  
- ✅ Filter models by provider  
- ✅ ZIP project downloads  
- ✅ Prompt enhancements in `prompts.ts`  
- ✅ DeepSeek API  
- ✅ Mistral API  
- ✅ OpenAI-compatible API  
- ✅ Local folder file sync  
- ✅ Docker containerization  
- ✅ Publish to GitHub  
- ✅ API key UI editor  
- ✅ xAI Grok Beta  
- ✅ LM Studio  
- ✅ HuggingFace  
- ✅ Bolt Terminal  
- ✅ Code output streaming  
- ✅ Revert code history  
- ✅ Chat backup & restore  
- ✅ Cohere integration  

---

## ✨ Features

🔥 AI-powered full-stack web development (Node.js)  
🧩 Multi-LLM support with pluggable architecture  
🖼️ Attach images to prompts  
🖥️ Integrated terminal for LLM command outputs  
🕒 Code version history & rollback  
🗂️ ZIP export for portability  
🐳 Docker support for seamless setup

---

## 💻 Quick Setup

### 📥 [Download Latest Release](https://github.com/JayashBhandary/Dennis/releases/latest)

1. Click **source.zip**
2. Extract and follow the steps below!

---

## ⚙️ Prerequisites

Make sure you’ve got:

### 🟢 Node.js  
👉 [Download Node.js](https://nodejs.org/en/download/) (LTS recommended)

---

## 🛠️ Running the Application

### 🔹 Option 1: Direct Install (Great for Beginners)

```bash
npm install -g pnpm
pnpm install
pnpm run dev
```


## Configuring API Keys and Providers

### Adding Your API Keys

Setting up your API keys in Dennis is straightforward:

1. Open the home page (main interface)
2. Select your desired provider from the dropdown menu
3. Click the pencil (edit) icon
4. Enter your API key in the secure input field

### Configuring Custom Base URLs

For providers that support custom base URLs (such as Ollama or LM Studio), follow these steps:

1. Click the settings icon in the sidebar to open the settings menu

2. Navigate to the "Providers" tab
3. Search for your provider using the search bar
4. Enter your custom base URL in the designated field

> **Note**: Custom base URLs are particularly useful when running local instances of AI models or using custom API endpoints.

### Supported Providers

- Ollama
- LM Studio
- OpenAILike

## Setup Using Git (For Developers only)

This method is recommended for developers who want to:

- Contribute to the project
- Stay updated with the latest changes
- Switch between different versions
- Create custom modifications

#### Prerequisites

1. Install Git: [Download Git](https://git-scm.com/downloads)

#### Initial Setup

1. **Clone the Repository**:

   ```bash
   # Using HTTPS
   git clone https://github.com/JayashBhandary/Dennis.git
   ```

2. **Navigate to Project Directory**:

   ```bash
   cd Dennis
   ```

3. **Switch to the Main Branch**:
   ```bash
   git checkout main
   ```
4. **Install Dependencies**:

   ```bash
   pnpm install
   ```

5. **Start the Development Server**:
   ```bash
   pnpm run dev
   ```

#### Staying Updated

To get the latest changes from the repository:

1. **Save Your Local Changes** (if any):

   ```bash
   git stash
   ```

2. **Pull Latest Updates**:

   ```bash
   git pull origin main
   ```

3. **Update Dependencies**:

   ```bash
   pnpm install
   ```

4. **Restore Your Local Changes** (if any):
   ```bash
   git stash pop
   ```

#### Troubleshooting Git Setup

If you encounter issues:

1. **Clean Installation**:

   ```bash
   # Remove node modules and lock files
   rm -rf node_modules pnpm-lock.yaml

   # Clear pnpm cache
   pnpm store prune

   # Reinstall dependencies
   pnpm install
   ```

2. **Reset Local Changes**:
   ```bash
   # Discard all local changes
   git reset --hard origin/main
   ```

Remember to always commit your local changes or stash them before pulling updates to avoid conflicts.

---

## Available Scripts

- **`pnpm run dev`**: Starts the development server.
- **`pnpm run build`**: Builds the project.
- **`pnpm run start`**: Runs the built application locally using Wrangler Pages.
- **`pnpm run preview`**: Builds and runs the production build locally.
- **`pnpm test`**: Runs the test suite using Vitest.
- **`pnpm run typecheck`**: Runs TypeScript type checking.
- **`pnpm run typegen`**: Generates TypeScript types using Wrangler.
- **`pnpm run deploy`**: Deploys the project to Cloudflare Pages.
- **`pnpm run lint:fix`**: Automatically fixes linting issues.

---

## Contributing

We welcome contributions! Check out our Contributing Guide to get started.

---

## FAQ

For answers to common questions, issues, and to see a list of recommended models, visit our [FAQ Page](FAQ.md).
