# 🎉 CoolWriteAI – LangChain Blog Generator

A sleek web app built with **LangChain** and **Next.js** that helps you generate blog content effortlessly. Just add a topic, and let AI craft polished, human-like posts instantly!

[🌐 Live Demo](https://cool-write-ai.vercel.app/) • [📗 GitHub Repo](https://github.com/debanganghosh08/CoolWriteAI.git)

![image](https://github.com/user-attachments/assets/d8c13cce-f0cf-4451-95df-686ab096d261)


---

## ✨ Features

* **Fast & Intuitive UI**: Built with Next.js and Tailwind CSS for clean UX.
* **LangChain Integration**: Utilizes OpenAI API through LangChain to generate structured content.
* **Customizable Output**: Fully editable blog posts with humanized tone and structure.
* **Efficient Workflow**: Paste topics, click "Generate", and watch AI craft your article.
* **Ready-to-Extend**: Easily add features like image embedding, SEO tags, or publishing hooks.
---
![image](https://github.com/user-attachments/assets/e03b48c4-c445-4857-8522-a7e3954b23d0)

---

## 💻 Tech Stack

* **Frontend**: Next.js, React, Tailwind CSS
* **Backend**: LangChain orchestrating OpenAI API calls
* **Deployment**: Hosted on Vercel (serverless, fast, and easy to scale)

---

## 🚀 Quick Start

1. **Clone & Install**

   ```bash
   git clone https://github.com/debanganghosh08/CoolWriteAI.git
   cd CoolWriteAI
   npm install
   ```

2. **Env Setup**

   Create a `.env.local` file:

   ```
   OPENAI_API_KEY=your_openai_key_here
   ```

3. **Run Locally**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to preview.

---

## 📂 Project Structure

```
├── components/      # UI and form components
├── pages/           # Next.js routes and pages
│   └── api/         # API endpoints for blog generation
├── styles/          # Tailwind configuration & global styles
├── langchain/       # Chain logic with prompts and templates
└── utils/           # Helpers for formatting and validations
```

---

## 🛠 How It Works

1. **User Input**: Topic or blog title in UI.
2. **API Call**: Next.js `api/generate` invokes LangChain.
3. **Prompt Creation**: LangChain builds the content-generation chain.
4. **OpenAI Execution**: Sends prompts, receives formatted blog text.
5. **Render Output**: Returns the structured blog post to UI.

---

## 🧩 Customization Ideas

* Add **tags**, **images**, or **SEO metadata**.
* Let users define **tone**, **length**, or **format**.
* Add a **preview button** and **download/export** options.
* Integrate with CMS (e.g., WordPress) or social platforms for direct publishing.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

* Submit issues or feature ideas
* Open pull requests
* Suggest improvements or optimizations

We use a standard GitHub flow. Please add tests if applicable 👍.

---

## 🧠 Credits & License

* Powered by **OpenAI** via **LangChain**
* Built on **Next.js**, **Tailwind CSS**, and **Vercel**
* **MIT License** – feel free to use, modify, and share!

---

## 💬 Connect

Made by **Debangan Ghosh**. Let’s connect on **LinkedIn**, **Twitter**, or open an issue in the repo.
Want features or have ideas? I’m all ears!
