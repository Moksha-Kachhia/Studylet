# Studylet

**AI-powered study tool** for students to upload textbooks, notes, and practice materials, generate summaries and flashcards, and actively master concepts. Designed to be **mobile-friendly** and lightweight—perfect for studying on the go. This project was fueled by my desire to make my commutes to school more productive!

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Future Roadmap](#future-roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### Phase 1 - MVP
- **User Authentication**: Secure sign-up and login via Firebase Auth.
- **Document Uploads**: PDFs and Word (.docx) files.
- **AI-powered Summaries & Flashcards**: Generate concise summaries and flashcards for uploaded materials using OpenAI API.
- **Dashboard**: View and organize uploaded files, summaries, and flashcards.
- **Public Flashcards**: Share select flashcard sets with the community.
- **Premium (Stripe-ready)**: Stub for subscription model, allowing extra storage and early access to new features.

### Phase 2 - Ongoing
- **Voice & Feynman Mode**: Practice concepts through conversational AI or voice-assisted recall.
- **Active Recall / Spaced Repetition**: Track flashcard usage and set reminders to optimize learning.
- **Interview Prep Mode**: Apply Studylet tools to coding or technical interview questions.
- **Database Upgrade**: Move to PostgreSQL + Supabase for more scalable storage and analytics.

---

## Tech Stack

- **Frontend:** React, Tailwind CSS, ShadCN/UI  
- **Backend:** Firebase Auth & Firestore  
- **AI/ML:** OpenAI API (summaries, flashcards)  
- **Payments (future):** Stripe  
- **Hosting:** Vercel  

---

## Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/Moksha-Kachhia/StudyLet.git
cd Studylet
```

2. **Install dependencies:**
```bash
npm install
```

3. **Create a .env.local file with:**
```
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_OPENAI_API_KEY=your_openai_api_key
```

4. **Run the app locally:**
```bash
npm start
```

---

## Future Roadmap

* Google Drive, OneNote, and GoodNotes integration for seamless file import.

* Canvas / Google Classroom integration for educational institutions.

* Custom flashcard sets with repetition scheduling.

* Voice-enabled learning modes for accessibility and active recall.

* Premium subscription with unlimited storage and advanced features.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or new feature suggestions.

---

## License

This project is licensed under the [`MIT License`](https://chatgpt.com/c/LICENSE)
