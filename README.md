# Code Inspector

Code Inspector is an AI-powered code review tool that leverages Google Gemini to provide detailed, actionable feedback on your code. It features a modern React frontend and a Node.js/Express backend.

---

## Features

- **AI Code Review:** Get expert-level code reviews powered by Google Gemini.
- **Live Editor:** Write or paste code and get instant feedback.
- **Modern UI:** Clean, responsive interface with syntax highlighting.
- **Easy Integration:** Simple REST API for backend communication.

---

## Project Structure

```
Code_Inspector/
├── Backend/
│   ├── server.js
│   └── src/
│       ├── app.js
│       ├── controllers/
│       │   └── ai.controller.js
│       ├── routes/
│       │   └── ai.routes.js
│       └── services/
│           └── ai.service.js
├── Frontend/
│   └── src/
│       ├── App.jsx
│       ├── App.css
│       ├── main.jsx
│       └── index.css
└── README.md
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)
- [Google Gemini API Key](https://ai.google.dev/)

---

### 1. Clone the Repository

```sh
git clone https://github.com/1RN21CS056/Code_Inspector.git
cd Code_Inspector
```

---

### 2. Backend Setup

```sh
cd Backend
npm install
```

- Create a `.env` file in the `Backend` directory:
  ```
  GOOGLE_GEMINI_KEY=your_google_gemini_api_key_here
  ```

- Start the backend server:
  ```sh
  node server.js
  ```
  The backend runs on [http://localhost:3000](http://localhost:3000).

---

### 3. Frontend Setup

```sh
cd ../Frontend
npm install
npm run dev
```

- The frontend runs on [http://localhost:5173](http://localhost:5173) (default Vite port).

---

## Usage

1. Open the frontend in your browser.
2. Enter or paste your code in the editor.
3. Click **Review** to get an AI-generated code review.

---

## Technologies Used

- **Frontend:** React, Vite, PrismJS, react-simple-code-editor, react-markdown, highlight.js, axios
- **Backend:** Node.js, Express, @google/generative-ai


---



## Acknowledgements

- [Google Gemini API](https://ai.google.dev/)
- [PrismJS](https://prismjs.com/)
- [react-simple-code-editor](https://github.com/satya164/react-simple-code-editor)

---

## 👨‍💻 Author

**Eshwar K**  
[LinkedIn](https://www.linkedin.com/in/eshwar-k-21a05424b/)  
[GitHub](https://github.com/1RN21CS056)

---
## License

[MIT](LICENSE)

---