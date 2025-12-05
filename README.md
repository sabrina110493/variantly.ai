variantly.ai

AI-powered impact simulation for PMs & Designers
Ship faster but with greater confidence by weighing in the potential metric impact of your product decisions — before you build.

![ezgif-5db2990858d9068a](https://github.com/user-attachments/assets/a2d922fa-ef70-4c18-8fc0-412efe484c3c)


🚀 Overview

Design and product teams often need to ship fast and faster (oh, hello Ai!) but build features based on intuition, not evidence. variantly.ai helps you validate ideas early by letting you:

Drop in your prototype (Figma, image, or Lovable UI)

Describe your change

Simulate its potential impact on key product metrics (activation, engagement, drop-offs, conversion, etc.)

Compare variants instantly

Share results with stakeholders for alignment

This enables more rigorous, data-aware decision making without needing analysts, experiments, or engineering time.

🎯 Why This Project Exists

Product decisions cost time, money, and engineering resources. Most teams lack the ability to estimate downstream impact until after shipping, leading to:

Costly rework

Slow experimentation cycles

Pressure to ship without validation

Stakeholders relying on gut feel instead of evidence

variantly.ai fills this gap by giving PMs and Designers an early signal of impact—fast, accessible, and interactive.

✨ Key Features

🔮 Impact Simulation Engine
AI predicts how your proposed UI change may influence user behavior flows and product metrics.

📊 Variant Comparison
Compare multiple concept versions side-by-side.

🖼 Prototype Input Support
Works with screenshots, Figma exports, or prebuilt UI in Lovable.

🔗 2-way GitHub Sync
Your Lovable-generated code is synced between the Lovable editor and this repo.

🧠 Natural Language Inputs
Just describe the change you’re exploring — the system handles interpretation.

🧵 Shareable Results
Export impact summaries for your stakeholders.

🧩 Tech Stack

Frontend: Vite + React + TypeScript

UI Components: shadcn/ui

AI Layer: OpenAI GPT models (connected via Lovable’s backend)

State Management: React hooks & Context

Build System: Lovable.dev

Deployment: (Optional) Vercel or Netlify

Repository Sync: Lovable-dev GitHub app (2-way sync)# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/a28fbd76-1d29-448e-98cd-cf4253cf9725

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/a28fbd76-1d29-448e-98cd-cf4253cf9725) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/a28fbd76-1d29-448e-98cd-cf4253cf9725) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)

💡 How It Works (High-Level)

User uploads or selects a UI variant

User describes intended product change

AI model interprets UI + natural language

Simulation engine predicts behavioral shifts

Metrics impact summary is generated

User compares variants and exports insights
