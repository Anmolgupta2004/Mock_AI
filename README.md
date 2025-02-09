AI Mock Interview 🎤🤖

🚀 Features

Home Page: Introduction and overview of the platform.

Contact Us Page: Allows users to reach out for support and inquiries.

Services Page: Details about the interview preparation services offered.

Take an Interview Route: Interactive form to start a mock interview.

Collects Job Role, Experience Level, and Tech Stack from the candidate.

Generates 5 AI-powered interview questions.

Candidate provides responses to each question.

AI evaluates answers and provides feedback and ratings.

🛠 Tech Stack

AI Model: Google Gemini for question generation and response evaluation.

Backend: Firebase for real-time database and authentication.

Authentication: Clerk for user management and secure login.

Frontend: React.js / Next.js for UI.

Database: Firestore for storing user interactions and results.

🏁 Getting Started

Clone the repository:

git clone https://github.com/your-username/ai-mock-interview.git

Navigate to the project directory:

cd ai-mock-interview

Install dependencies:

npm install

Start the application:

npm start

🎯 How It Works

User selects job role, experience level, and tech stack.

AI generates 5 relevant interview questions.

User answers the questions.

AI analyzes responses and provides feedback and a rating.

🤝 Contributing

Feel free to fork this repository, submit issues, or contribute by opening pull requests.

📜 License

MIT License

🔗 Live Demo: your-demo-link.com

📖 README.md File

This file serves as documentation for the AI Mock Interview application, outlining its features, technology stack, and setup instructions. It ensures that new developers and contributors can quickly understand and deploy the project.


Authentication: Clerk for user management and secure login.

Frontend: React.js / Next.js for UI.

Database: Firestore for storing user interactions and results.

Getting Started 🏁

Clone the repository:

git clone https://github.com/your-username/ai-mock-interview.git

Navigate to the project directory:

cd ai-mock-interview

Install dependencies:

npm install

Start the application:

npm start

How It Works 🎯

User selects job role, experience level, and tech stack.

AI generates 5 relevant interview questions.

User answers the questions.

AI analyzes responses and provides feedback and a rating.

Contributing 🤝

Feel free to fork this repository, submit issues, or contribute by opening pull requests.

License 📜

MIT License

🔗 Live Demo: your-demo-link.com

nfigs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
