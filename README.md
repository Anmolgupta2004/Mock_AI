 # AI Mock Interview 🎤🤖

Welcome to **AI Mock Interview**, your AI-powered interview preparation platform! 🚀

## 🔥 Features

- **Home Page**: Overview and introduction to the platform.
- **Contact Us Page**: Reach out for support and inquiries.
- **Services Page**: Details about our interview preparation services.
- **Take an Interview Route**:
  - Collects **Job Role, Experience Level, and Tech Stack** from the candidate.
  - Generates **5 AI-powered interview questions**.
  - Candidate provides responses to each question.
  - AI evaluates answers and provides **feedback and ratings**.

---

## 🛠 Tech Stack

- **AI Model**: Google Gemini for question generation and response evaluation.
- **Backend**: Firebase for real-time database and authentication.
- **Authentication**: Clerk for user management and secure login.
- **Frontend**: React.js / Next.js for UI.
- **Database**: Firestore for storing user interactions and results.

---

## 🏁 Getting Started

### Clone the Repository:
```sh
git clone https://github.com/your-username/ai-mock-interview.git
```

### Navigate to Project Directory:
```sh
cd ai-mock-interview
```

### Install Dependencies:
```sh
npm install
```

### Start the Application:
```sh
npm start
```

---

## 🎯 How It Works

1. User selects **Job Role, Experience Level, and Tech Stack**.
2. AI generates **5 relevant interview questions**.
3. User submits answers.
4. AI **analyzes responses** and provides **feedback and a rating**.

---

## 🤝 Contributing

We welcome contributions! Feel free to:
- **Fork** the repository.
- **Submit issues** for feature requests or bug reports.
- **Open pull requests** to improve the project.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🔗 Live Demo

[Live Demo](your-demo-link.com) 🚀

---

## 🛠 ESLint Configuration

For better code quality, follow these ESLint configurations:

```js
// eslint.config.js
import tseslint from '@typescript-eslint/eslint-plugin';
import react from 'eslint-plugin-react';

export default tseslint.config({
  settings: { react: { version: '18.3' } },
  plugins: {
    react,
  },
  rules: {
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
});
```

---

Happy Coding! 💻✨
