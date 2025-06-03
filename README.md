DeepSeek AI Clone – Full Stack AI Chat App

## Overview
This is a full-stack AI chat application built using Next.js, inspired by DeepSeek. It offers a powerful, real-time chat interface where users can ask AI questions and receive intelligent responses using the official DeepSeek API.The project features robust user authentication via Clerk, and stores user and chat data in MongoDB Atlas. It supports a fully interactive sidebar, allows renaming or deleting conversations, and is deployed live using Vercel.

---

🔥 Features
- 🔐 User Authentication with Clerk – Seamless login and session handling
- 💬 Prompt-Based AI Chat – Ask anything and get dynamic responses
- 🧠 Typing Animation – AI replies appear with a natural typing effect
- 📁 Sidebar Chat Management – Create, rename, and delete saved chats
- 🧾 Chat History – All chats stored securely in MongoDB
-📦 Clerk Webhooks Integration – Automatically stores user profile data in the database
- 🧑‍💻 VS Code-Like Code Rendering – Syntax-highlighted responses using Prism.js
- 📌 Fully Responsive Design – Built using Tailwind CSS for modern UI/UX
- 🚀 Live Deployment on Vercel

### 🛠️ Tech Stack
- Frontend: Next.js (v15.1.6), Tailwind CSS, prismjs – Code syntax highlighting, react-hot-toast – Toast notifications, react-markdown – Markdown formatting for AI responses
- Backend: Node.js + Express (via API routes in Next.js), axios – Making API calls, mongoose – MongoDB ODM for data modeling, openai – Accessing DeepSeek AI API, svix – Managing Clerk              webhooks and storing user data
- Authentication & Database: Clerk – User authentication and session management, MongoDB Atlas – Cloud-hosted database

---

### 🔧 Installation & Setup

## ✅ Prerequisites
Ensure you have the following installed:
- **Node.js** (LTS version recommended)
- **MongoDB Atlas** (or a local MongoDB instance)
- **Git** (for cloning the repository)
- **A code editor** (e.g., VS Code)

### Steps
  1. Clone this repository:
   ```bash
   git clone https://github.com/deepesh2596/deepseek-ai-clone.git
   cd deepseek-ai-clone
   ```
 2. Install dependencies:
   ```bash
   npm install
   ```
3. Set Up Environment Variables
- Create a .env.local file in the root directory and configure the following:

 **Public Environment Variables:**
   ```bash
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   ```
 **Private Environment Variables:**
   ```bash
   CLERK_SECRET_KEY=your_clerk_secret_key
   MONGODB_URI=your_mongodb_connection_string
   ```
 **Optional - DeepSeek / OpenAI Keys**
   ```bash
   OPENAI_API_KEY=your_deepseek_or_openai_key
   SVIX_SECRET=your_svix_webhook_secrett
   ```

4. Run the Application
     ```bash
     npm run dev
     ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the project.

---

### 🌐 Deployment
The project is fully deployed using Vercel, and uses MongoDB Atlas as the cloud database solution.

### 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork this repository
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature: your-description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Submit a pull request

---

### 📧 Contact
If you have any questions or suggestions, feel free to reach out:

Email: deepesh2596@gmail.com 🚀
GitHub: deepesh2596























