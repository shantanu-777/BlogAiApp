
# ✨ BlogAiApp

Welcome to **BlogAiApp** – an AI-powered tool designed to simplify the process of writing blogs, articles, and even books. Using **GPT-based AI models** and modern integrations, it helps you transform raw ideas into structured, SEO-friendly, and engaging content with ease.

## 🌟 Features

- **📝 Blog Post Generator**: Create complete, SEO-optimized blog posts in minutes.  
- **📚 Book Writer**: Generate multi-chapter books with consistent tone and style.  
- **📅 Content Planner**: Build content calendars, outlines, and topic clusters.  
- **🔍 Competitor Insights**: Spot content gaps and new opportunities.  
- **🔎 AI-Powered Research**: Enrich your content with up-to-date information.  
- **🔄 Smart Editing**: Proofreading, rewriting, and humanizing AI text.  
- **🔌 Integrations**: Connect with WordPress, GitHub, and Medium.  
- **🤖 Advanced AI Models**: Powered by the latest LLMs for reliable content generation.  

## 🗂️ Project Structure

```

BlogAiApp/
├── src/                      # Core backend modules
│   ├── blog/                 # Blog generation logic
│   ├── book/                 # Book generation logic
│   ├── blog\_sections/        # Section-level generators
│   ├── planning/             # Content planning tools
│   │   ├── content\_calendar.py
│   │   ├── competitor\_analysis.py
│   │   ├── topic\_clusters.py
│   │   └── content\_outline.py
│   ├── research/             # AI/web research utilities
│   ├── seo/                  # SEO tools
│   ├── integrations/         # Publishing integrations
│   │   ├── github.py
│   │   ├── medium.py
│   │   └── wordpress.py
│   ├── post\_processing/      # Polishing tools (proofreading, humanizing)
│   ├── text\_generation/      # AI text generation
│   └── types/                # Shared type definitions
├── tests/                    # Unit tests
├── frontend/                 # Web UI (Next.js)
├── .env                      # Local environment variables
├── .env.example              # Example env file
├── pyproject.toml            # Python project config
├── LICENSE                   # License file
└── README.md                 # Project docs

````

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/BlogAiApp.git
````


2. **Configure environment**:
   Copy `.env.example` into `.env` and add your API keys:

   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ANTHROPIC_API_KEY=your_anthropic_api_key   # optional
   SERP_API_KEY=your_serp_api_key             # optional
   SEC_API_API_KEY=your_sec_api_api_key       # optional
   ```

3. **Install dependencies**:
   With Poetry (recommended):

   ```bash
   poetry install
   ```

   Or with pip:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run backend server**:

   ```bash
   python server.py
   ```

   → Available at [http://localhost:8000](http://localhost:8000)

5. **Run frontend (optional)**:

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   → Available at [http://localhost:3000](http://localhost:3000)

✅ You’re ready to generate content with BlogAiApp!

## 🐳 Docker Setup

Run everything with Docker:

```bash
docker-compose up -d
```

* API runs at: [http://localhost:8000](http://localhost:8000)
* Frontend runs at: [http://localhost:3000](http://localhost:3000)

Stop containers:

```bash
docker-compose down
```

Extra Docker commands:

```bash
docker-compose logs -f          # View logs
docker-compose up -d --build    # Rebuild containers
docker-compose exec blog-ai bash # Open a shell inside container
```

## 💻 Usage

### Blog Post

```bash
python -m src.blog.make_blog "AI for Beginners" --keywords "AI,ML" --research
```

### Book

```bash
python -m src.book.make_book "AI Guide" --chapters 5 --sections 3 --output book.md
```

### Planning Tools

```bash
python -m src.planning.content_calendar "Tech Niche"
python -m src.planning.competitor_analysis "Marketing"
python -m src.planning.topic_clusters "AI" --clusters 3
```

### Publishing

```bash
python -m src.integrations.wordpress "Post" --url "https://yourblog.com"
python -m src.integrations.github "Post" --repo "username/repo"
python -m src.integrations.medium "Post" --token "medium_token"
```

## 🧪 Testing

```bash
python -m unittest discover tests
```

## ⚙️ Tech Stack & Dependencies

* **Backend**: FastAPI, Uvicorn, Websockets
* **AI Models**: OpenAI, Anthropic, Google Generative AI
* **Utilities**: Pydantic, Requests, Python-Dotenv
* **Frontend**: Next.js, TailwindCSS, ShadCN
* **Deployment**: Docker & Docker Compose

## 📜 License

This project is distributed under the [MIT License](LICENSE).


🎉 **BlogAiApp helps you write smarter, faster, and better content.**


