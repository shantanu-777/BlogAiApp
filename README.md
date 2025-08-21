# BlogAiApp

Welcome to Blog generator Generator – a powerful tool that helps you create high-quality blogs, books, and other long-form content with ease. Built with modern AI models like GPT-4, this project speeds up the writing process and ensures your content is polished, structured, and SEO-friendly.

✨ Features

📝 Blog Writing – Generate complete blog posts that are optimized for search engines.

📚 Book Creation – Draft full-length books with chapters, sections, and consistent flow.

📅 Planning Tools – Build content calendars, topic clusters, and outlines.

🔍 Competitor Insights – Analyze existing content to uncover opportunities.

🔎 Research Support – Enrich your text with web-based research.

🔄 Post-Editing – Proofread, reformat, and humanize the content.

🔌 Integrations – Publish directly to platforms like WordPress, Medium, or GitHub.

🤖 Powered by Modern AI – Built on GPT-4 for reliable and natural outputs.

📂 Project Layout

ai-content-generator/
├── src/                      
│   ├── blog/                 # Blog generation modules
│   ├── book/                 # Book generation modules
│   ├── planning/             # Planning utilities (calendars, outlines, etc.)
│   ├── research/             # Research helpers
│   ├── seo/                  # SEO support
│   ├── integrations/         # Publishing integrations
│   ├── post_processing/      # Cleanup and editing tools
│   ├── text_generation/      # Core AI generation logic
│   └── types/                # Data types & schemas
├── tests/                    # Automated tests
├── frontend/                 # Next.js frontend
├── .env                      # Environment variables
├── pyproject.toml            # Python dependencies
└── README.md                 # Documentation

⚡ Getting Started
1. Clone the repo
git clone https://github.com/yourusername/ai-content-generator.git

2. Add environment variables

Create a .env file and include your API keys:

OPENAI_API_KEY=your_key_here
ANTHROPIC_API_KEY=optional
SERP_API_KEY=optional
SEC_API_API_KEY=optional

3. Install dependencies

Using Poetry (recommended):

poetry install


Or with pip:

pip install -r requirements.txt

4. Run the backend
python server.py


👉 Backend will run at: http://localhost:8000

5. Run the frontend (optional)
cd frontend
npm install
npm run dev


👉 Frontend will run at: http://localhost:3000

🐳 Docker Setup

If you prefer Docker:

docker-compose up -d


API: http://localhost:8000

Frontend: http://localhost:3000

Stop containers:

docker-compose down

🎯 Usage
Blog generation
python -m src.blog.make_blog "My Blog Topic" --keywords "ai,tech,startup" --research

Book creation
python -m src.book.make_book "My Book Idea" --chapters 6 --sections 4 --output "my_book.md"

Planning tools
python -m src.planning.content_calendar "Tech Niche" --timeframe month --frequency 7

Publishing
python -m src.integrations.wordpress "My Blog Post" --url "https://mysite.com" --username "me" --password "pass"

🧪 Run Tests
python -m unittest discover tests

🛠️ Tech Stack

FastAPI – Backend API

Next.js – Frontend

OpenAI, Anthropic, Gemini – AI models

TailwindCSS – Styling

Docker – Deployment

📜 License

This project is released under the MIT License
.

✨ With AI Content Generator, you can focus on ideas while the AI handles the heavy lifting.
