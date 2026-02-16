# Classmate
A app that helps students study better


# 🌸 Classmate 

**Classmate** is a personalized, AI-powered Learning Management System (LMS) and module planner designed to make studying organized, engaging, and highly effective. Built as a cross-platform desktop and mobile application, it takes your raw study materials and transforms them into an interactive, gamified learning journey.

## ✨ Features

* **📚 Dynamic Module Planning:** Set up your subjects and chapter counts, and let the app automatically generate a customized weekly study calendar.
* **🧠 AI Content Ingestion:** Upload your textbooks, lecture slides, and past papers (PDF, DOCX, Excel, or Images). Classmate automatically extracts subtopics and builds your daily/weekly focus lists.
* **🔒 Gated Progression & Testing:** You can't move forward until you understand the material. The built-in AI generates micro-tests from your uploaded content. Score 50%+ to unlock the next chapter, or switch to Exam Prep mode for tiered difficulty practice tests.
* **🤖 Strict AI Study Coach:** A read-only AI chatbot that analyzes your test scores and tells you exactly what to focus on. No distractions, just actionable study advice.
* **⏳ Focus & Gamification:** * Built-in Pomodoro timer.
  * Deep **Spotify Integration** (music only plays during active study modes).
  * Earn badges based on test success rates and maintain streaks by completing chapters in under two weeks.
* **🎨 Sweet & Customizable UI:** A non-formal, aesthetically pleasing design. Choose between Dark Mode, Light Mode, or fully Custom Mode (change fonts, colors, and icons). 
* **📝 Interactive Annotations:** Highlight and sticky-note your uploaded documents, saving all annotations to a central database.
* **📰 Social News Feed:** Stay updated with a curated feed of career and module-relevant posts from across social media.

## 🛠️ Tech Stack

This project is built using a modern, lightning-fast stack designed for cross-platform deployment:

* **Application Framework:** [Tauri](https://tauri.app/) (Rust-based backend for lightweight desktop/mobile binaries)
* **Frontend:** Vanilla JavaScript + [Vite](https://vitejs.dev/)
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Backend as a Service:** [Supabase](https://supabase.com/) (PostgreSQL, Authentication, and Storage for PDFs/Images)
* **AI Integration:** OpenAI / Anthropic API (Document parsing and test generation)

## 🚀 Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
1. **Node.js** (v18+)
2. **Rust** (Install via [rustup.rs](https://rustup.rs/))
3. **C++ Build Tools** (Windows only)

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/classmate.git](https://github.com/yourusername/classmate.git)
   cd classmate
