📄 REPORT.md — LokKala: The Cultural Clipbook
________________________________________
1. 🧑🤝🧑 Team Information
•	Team Name: [THE HIGH FIVE]
•	Organization: viswam.ai — Summer of AI 2025
•	Team Members:
o	[Vignesh Yadala ]– Full Stack Developer
o	[Sri vidhya] – AI Integration Lead
o	[Noshitha] – Product & UI/UX Designer
o	[Nithin] – Community Outreach & Testing Lead
o	[Shasan] – DevOps & Deployment
________________________________________
2. 🌍 Application Overview
App Name: LokKala – India’s Cultural Clipbook
Problem Statement:
India’s diverse cultural and linguistic heritage is underrepresented in digital AI training corpora. There is a lack of accessible tools for everyday people, especially from low-connectivity areas, to contribute meaningful, culturally rich data in their own languages.
Solution Overview:
LokKala is a lightweight, multilingual web app that enables users to contribute folk stories, local proverbs, or humorous captions (memes) in their native languages. It works offline-first and syncs when connected. These contributions help build a diverse dataset for AI models aligned with viswam.ai’s mission.
Core MVP Features (built in Week 1):
•	Simple mobile-friendly UI
•	Add a folk story/proverb or meme caption
•	Choose language and region
•	Offline contribution support (local save and sync)
•	AI suggestions (e.g., translations, caption boosters)
________________________________________
3. 🤖 AI Integration Details
•	Backend AI Tools Used: Hugging Face Transformers (for language detection, caption suggestion, etc.)
•	Optional Enhancements: Auto-tagging stories with themes (e.g., “wisdom,” “humor”) via NLP
•	Offline Consideration: Suggestions are cached or generated from a local lightweight model (or disabled when offline)
________________________________________
4. 🏗️ Technical Architecture & Development
Tech Stack:
•	Frontend: Streamlit
•	Backend/API: FastAPI (optional)
•	AI: Hugging Face Transformers
•	Database: JSON-based file or Firestore (depending on access)
•	Offline Support: PWA + IndexedDB for offline-first UX

Code Repository:
git clone git clone https://code.swecha.org/Vigneshbabu/summer-of-ai.git
________________________________________
5. 🧪 User Testing & Feedback (Week 2)
Recruitment Strategy:
•	WhatsApp groups (students, teachers, Swecha)
•	Telegram channels
•	Street interviews with simplified user flow demo
Testing Methodology:
•	Users asked to submit 1 proverb/story or meme
•	Devices: 2G/3G mobile phones in rural areas
•	Data logged with timestamps, language selection
Sample Feedback:
•	“App loads well even with low signal”
•	“Would like voice input for elderly users”
•	“Meme captioning was fun, added 5 memes!”
Bug Fixes & Changes:
•	Font size increased for readability
•	Added preview for captions before upload
•	Offline save logic refined for delayed syncing
________________________________________
6. 📅 Project Lifecycle & Roadmap
Week 1: MVP Development Sprint
•	✅ Defined MVP scope
•	✅ Completed UI and backend integration
•	✅ Implemented offline functionality
•	✅ Deployed to Hugging Face Spaces
Week 2: Testing & Iteration
•	✅ Recruited 30 beta users
•	✅ Collected 100+ test contributions
•	✅ Performed UI/UX iterations based on feedback
Weeks 3–4: User Acquisition & Corpus Growth Campaign
Target Audience:
•	Rural school students
•	Local folklore enthusiasts
•	WhatsApp community admins
Outreach Methods:
•	Flyers (in Telugu, Tamil, Hindi)
•	WhatsApp posters with QR links
•	Reels on Instagram and YouTube Shorts
•	Community leader outreach (teachers, NGOs)
Metrics Collected:
•	Total unique users: [e.g., 412]
•	Contributions: [e.g., 620 text + 142 memes]
•	Top languages: Telugu (42%), Tamil (25%), Hindi (20%), Others (13%)
________________________________________
7. 🌱 Post-Internship Vision & Sustainability Plan
Next Steps:
•	Add voice input & text-to-speech for accessibility
•	Integrate community leaderboard for gamification
•	Enable tagging and filters (e.g., “festival stories”)
Sustainability Strategy:
•	Partner with rural schools and local cultural clubs
•	Launch monthly content challenges with small prizes
•	Empower local champions to collect content offline and sync
Scaling Plan:
•	Integrate other open-source tools (e.g., Whisper for speech)
•	Expand into northeast languages and tribal dialects
•	Enable multi-modal submissions (images + stories)
