# AI-to-Prevent-Stampede-Incidents
📝 Overview

This is an AI-powered real-time people counting system built with React, TypeScript, Vite, and TensorFlow.js. It uses a webcam to detect people using the COCO-SSD AI model, updates the count dynamically, and allows manual adjustments if necessary.

✨ Features

📷 Live Webcam Feed: Enables/disables the camera.
🤖 AI-Based Detection: Uses TensorFlow.js (COCO-SSD) to detect and count people.
📊 Real-Time Updates: Automatically updates the count as people enter/exit.
🛠️ Manual Controls: Buttons to manually increase, decrease, or reset the count.
📜 History Tracking: Logs previous count changes.
🎨 Styled with Tailwind CSS for a modern UI.

🏗️ Tech Stack

Frontend: React (TypeScript, Vite)
AI Model: TensorFlow.js (COCO-SSD)
Stylng: Tailwind CSS

🚀 Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the Repository
git clone <your-repo-url>
cd project

2️⃣ Install Dependencies
npm install

3️⃣ Start the Development Server
npm run dev

Then open http://localhost:5173/ in your browser.

📂 Project Structure

project/
│── src/                 # Source Code
│   ├── App.tsx         # Main React Component
│   ├── main.tsx        # Entry Point
│   ├── index.css       # Styles
│── public/              # Static Assets
│── package.json         # Dependencies & Scripts
│── vite.config.ts       # Vite Configuration
│── tailwind.config.js   # Tailwind Configuration
│── tsconfig.json        # TypeScript Configuration

🛠️ How It Works

1️⃣ Loads AI Model (COCO-SSD) using TensorFlow.js.
2️⃣ Captures Frames from the webcam.
3️⃣ Detects People using the AI model.
4️⃣ Updates Count dynamically.
5️⃣ Allows Manual Adjustments if needed.
6️⃣ Logs Past Counts for tracking.
7️⃣ Displays UI with status updates.

🎯 Future Enhancements

🔍 Improve AI detection accuracy.
📊 Add charts to visualize count trends.
📡 Deploy as a hosted web app.

📜 License
This project is open-source. Feel free to modify and enhance it!
