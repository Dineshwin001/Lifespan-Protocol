Lifespan Protocol Dashboard 🧬

An AI-powered, dynamic React web application that generates highly personalized, age-specific biological optimization plans, nutritional schedules, and superfood protocols.

Features ✨

Age-Specific Protocol Generation: Uses the Gemini AI API to dynamically generate a 20-food superfood arsenal and biological targets (neuroplasticity, bone density, longevity) tailored precisely to your exact age (1-120).

Dynamic Theming Engine: The UI automatically recolors itself based on the age group of the user (e.g., vibrant ambers for children, sleek indigos for adults, calming blues for seniors).

AI Synergy Recipe Creator: Click a button to instantly generate a custom recipe that combines the superfoods from the active tier.

Personalized Timeline Adjuster: Work night shifts? Fully vegan? Enter your constraints, and the AI rewrites your daily nutritional schedule while keeping the core biological goals intact.

Modern Tech Stack: Built with React, Tailwind CSS for beautiful styling, and lucide-react for iconography.

Getting Started Locally 🚀

Clone the Repository

git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME


Install Dependencies
Ensure you have Node.js installed, then run:

npm install
npm install lucide-react
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p


Setup Environment Variables
Create a .env file in the root of your project and add your Gemini API key:

VITE_GEMINI_API_KEY=your_gemini_api_key_here


Run the App

npm run dev


Open http://localhost:5173 in your browser.

Deployment 🌐

This project is perfectly suited for free deployment on Vercel or Netlify.

Connect your GitHub repository to Vercel/Netlify.

In the deployment settings, add your VITE_GEMINI_API_KEY as an Environment Variable.

Deploy!
