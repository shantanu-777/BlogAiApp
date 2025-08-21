
# Blog-AI

This is a blog application built with **Next.js**, **Supabase**, and **AI integration** for smarter blogging.

---

## 🚀 Features

- 🔐 **Authentication & User Management** (Supabase Auth)
- 👤 **Role-based Access Control** (Admin, Editor, Author, Reader)
- ✍️ **Create, Edit, and Publish Blogs**
- 🤖 **AI Integration**  
  - Blog writing assistant  
  - Content suggestions  
  - Grammar corrections  
- 📜 **View Conversation History with AI**
- 🎨 **Modern UI with TailwindCSS & ShadCN**

---

## 📂 Project Structure

```

frontend/
├── app/                # Next.js App Router pages
│   ├── globals.css      # Global styles
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Landing page
├── components/          # Reusable UI components
├── lib/                 # Utility functions
├── public/              # Static assets
├── README.md
└── package.json

````

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/shantanu-777/blog-AI.git
cd blog-AI/frontend
````

Install dependencies:

```bash
npm install
```

Set up TailwindCSS & PostCSS:

```bash
npm install tailwindcss postcss autoprefixer @tailwindcss/postcss
```

---

## 🔑 Environment Variables

Create a `.env.local` file inside the `frontend/` folder and add:

```bash
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
```

---

## ▶️ Run Locally

Start the development server:

```bash
npm run dev
```

The app will be available at:

```
http://localhost:3000
```

---

## 🛠️ Tech Stack

* [Next.js](https://nextjs.org/)
* [Supabase](https://supabase.com/)
* [TailwindCSS](https://tailwindcss.com/)
* [ShadCN UI](https://ui.shadcn.com/)
* [TypeScript](https://www.typescriptlang.org/)

---

## 📌 Notes

* If TailwindCSS shows `@tailwind unknown rule` error → Install `@tailwindcss/postcss`
* Make sure `.env.local` is correctly set up
* AI features require proper API keys (to be added later)

---

## 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

MIT License © 2025 Shantanu Modhave

```

Do you want me to also **add exact setup steps for AI integration (LLM API key usage)** into this README, or keep it minimal for now?
```
