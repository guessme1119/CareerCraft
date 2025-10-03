CareerCraft
CareerCraft is a next-generation career management and job search platform combining intelligent resume-building, AI-powered analysis, and smart job matching for Indian professionals and HR teams.

✨ Stunning Landing & Role-Based Authentication
Users are greeted with a beautiful gradient landing page offering seamless navigation. Choose to enter as an HR or a User, then proceed through a secure, OTP-based email authentication flow with persistent session management.


👤 Custom User Dashboard
Every user gets a personalized dashboard featuring a welcome message, quick stats (applications, resumes built, jobs saved), and direct access cards to your most powerful features—Jobs, Resume Builder, AI Analyser, and Profile.

🔎 Intelligent Job Search & Management
CareerCraft’s Jobs module uses the Adzuna API to fetch real-time Indian listings, presenting them in a beautifully designed, responsive grid. Filter by title, location, and salary. A proprietary algorithm smartly recommends jobs, displaying match percentages and allowing bookmarking and fast application—all with a modern, intuitive UI.

Smart profile-based matching using skills and resume data

Visual compatibility badges for quick insight

One-click save/bookmark with persistent storage

📝 Interactive Resume Builder
Create professional resumes with a WYSIWYG dual-panel layout. The left panel offers easy-to-use, dynamic forms; the right side updates live with a sleek, printable template. Adding education, experience, projects, and skills is effortless, all with print-optimized design and PDF export.

Instant live preview as you type

Dynamic add/remove for sections and skills

Print/PDF export for a clean, recruiter-ready CV

🦾 AI-Powered Resume Analyser
Upload your resume (PDF/DOCX) for instant, actionable feedback. Get a professional score (0–100), see detected skills, ATS compatibility, and receive structured suggestions to boost your career prospects. Analysis is visually presented for maximum clarity, and suggestions are tailored for improvement.

Section, skills, and format scoring

Keyword scanning for top tech skills

Suggestions for better ATS performance

Updates your user profile for even smarter job matching

🙍‍♂️ Profile Management
Easily edit your personal info, update skills/experience, view history of all resume analyses with scores, and manage your profile for optimal job recommendations. CareerCraft auto-syncs resume skills and stats, keeping your profile one step ahead.

🛡️ Security, Integrations & Technology
Role-based authentication, hashed passwords, OTP verification

File upload validation—secure naming and automatic clean-up

Gmail SMTP for verification and notifications

Responsive, mobile-first CSS with gradients, cards, and touch-friendly elements

Backend: Flask (Python), SQLAlchemy, Flask-Mail, Werkzeug

Frontend: Pure JS/CSS, CSS grid/flexbox, print-specific styles

🚀 Getting Started
Clone this repo

pip install -r requirements.txt

Set up your DB and email configuration

flask run and open localhost:5000

🤝 Contributing
Pull requests and feedback are always welcome. Raise issues for bugs or feature requests to help us grow CareerCraft.

