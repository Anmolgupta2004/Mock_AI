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

## 🎯 How It Works

1. User selects **Job Role, Experience Level, and Tech Stack**.
2. AI generates **5 relevant interview questions**.
3. User submits answers.
4. AI **analyzes responses** and provides **feedback and a rating**.

---

## 🛠 Tech Stack

- **AI Model**: Google Gemini for question generation and response evaluation.
- **Backend**: Firebase for real-time database and authentication.
- **Authentication**: Clerk for user management and secure login.
- **Frontend**: React.js / Next.js for UI.
- **Database**: Firestore for storing user interactions and results.


---

##  Login Page
![login](https://github.com/user-attachments/assets/b1bf8439-90af-4ca3-b3a7-bb00674be27f)


---

## 🏡 Home Page 
![home](https://github.com/user-attachments/assets/f346f7a3-540f-4c12-9f87-df8580facb8f)

---



##  Dashboard
![dashboard](https://github.com/user-attachments/assets/5623ab07-4859-48fd-8d2b-9e9b97ddf015)


---
---

##  Interview
![interview](https://github.com/user-attachments/assets/ebccbcbc-0345-403c-afaa-e5fead52fa77)

---

##  Feedback
![feedbsack](https://github.com/user-attachments/assets/3b593c3d-10b7-49bd-ba73-3d0a2d973d4d)

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


## 🤝 Contributing

We welcome contributions! Feel free to:
- **Fork** the repository.
- **Submit issues** for feature requests or bug reports.
- **Open pull requests** to improve the project.

---







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
