
## 🚀 LEARNIQAI – AI-Powered Learning Revolution
**LEARNIQAI** is an innovative AI-driven learning platform designed to personalize education, enhance career readiness, and boost productivity. It empowers students with adaptive learning, intelligent insights, and AI-powered tools, streamlining their academic and professional growth.

## 🌟 Features in Detail

## 1)🎯 Personalized Learning Hub

AI-powered course recommendations and adaptive learning pathways tailored to individual learning styles and knowledge gaps.
Dynamically generated study materials, ensuring students receive the most relevant and efficient learning experience.

## 2)📄 Interactive PDF Companion

Upload PDF documents, ask questions, and get context-aware AI responses instantly.
Converts static PDFs into an interactive knowledge source, enhancing comprehension and engagement.

## 3)🎥 Video Insight Generator

Summarizes YouTube videos into key takeaways, allowing students to grasp essential concepts quickly.
AI-powered chatbot enables direct interaction with video content, helping resolve doubts on demand.

## 4)📚 AI-Driven Research Summarizer

Converts complex research papers into concise, high-impact summaries.
Fetches related papers and provides audio-based summaries for an enhanced research experience.

## 5)📝 AI Content Creator

Generates essays, study plans, research papers, and blog content with AI assistance.
Ensures quality, relevance, and structure, saving students time while enhancing academic performance.

## 6)🎯 Career-Ready Resume Optimizer

Analyzes resumes against job descriptions to highlight skill gaps and recommend improvements.
AI-generated feedback and optimization suggestions enhance job application success rates.
Generates a detailed career report that helps students understand their strengths and weaknesses.

## 7)⏳ Personal Productivity Planner

Task management tools including a to-do list, focus timer, and calendar integration.
Helps students organize tasks, prioritize effectively, and maintain productivity.

## 8)💡 AI-Powered GitHub Assistant

Analyzes and summarizes code repositories, offering deep insights into project structure.
Helps students understand complex codebases and improve their contributions.



## 🏗️ Tech Stack


**● Frontend**-Next.js, Tailwind CSS, TypeScript

**● AI Integration**-Langchain, Gemini AI

**● Database & Storage**-Neon, Convex, Drizzle

**● Authentication**-Clerk

**● Web Loaders**-Langchain Web Loaders


## 🎯 How LearniQAI Solves the Problem

● **Tailored Learning Journeys**– AI adapts content to each student’s needs, maximizing efficiency and retention.

● **Effortless Research & Learning** – Transforms static content into interactive, digestible insights.

● **Bridging Education & Career** – AI-powered tools enhance career readiness by optimizing resumes and skill development.

● **Boosting Productivity** – Smart productivity tools ensure effective study planning and time management.


## 🚀 Getting Started

1️⃣ **Clone the Repository**
To get started, clone the LearniQAI repository using Git:



git clone https://github.com/Shr13050/LEARNIQAI.git

cd learniqai


**2️⃣ Create and Configure the .env.local File**

LEARNIQAI uses environment variables to securely store API keys and database URLs.

To set up the environment variables, create a .env.local file in the project root directory:


touch .env.local

Open the .env.local file in any text editor and add the following environment variables:


**NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key**

**CLERK_SECRET_KEY=your_clerk_secret_key**

**NEXT_PUBLIC_CLERK_SIGN_IN_URL=your_clerk_sign_in_url**

**NEXT_PUBLIC_CLERK_SIGN_UP_URL=your_clerk_sign_up_url**

**NEXT_PUBLIC_GEMINI_API_KEY_0=your_gemini_api_key_0**

**NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key**

**NEXT_PUBLIC_DRIZZLE_DB_URL=your_drizzle_db_url**

**CONVEX_DEPLOYMENT=your_convex_deployment_url**


**How to Get These Keys?**

**Clerk Keys:** Sign up at **Clerk.dev**, create an application, and obtain the publishable and secret keys.

**Gemini API Key:** Register at **Google AI Studio**, create an API key, and add it here.

**Drizzle DB URL:** Set up a database on **Neon.tech** or another Drizzle-compatible service and copy the connection URL.

**Convex Deployment URL:** Deploy your Convex backend and use the provided deployment URL.

**3️⃣ Install Dependencies**

Run the following command to install the required dependencies:


**npm install --force**

The --force flag ensures all dependencies are installed correctly, even if there are minor version mismatches.

**4️⃣ Run the Development Server**

Once dependencies are installed, start the development server:


**npm run dev**

**Your LearniQAI instance will now be running locally on:**

👉 **http://localhost:3000**

