🌾 Bindisa Agritech - Complete Frontend Setup
Welcome to the Bindisa Agritech website repository! This guide will help you set up the project locally using VS Code.

📋 Quick Setup Instructions for VS Code
1. Prerequisites
Make sure the following tools are installed:

Node.js (v18+)

VS Code

Git

2. Create New Project Folder
bash
Copy
Edit
mkdir bindisa-agritech-website
cd bindisa-agritech-website
3. Copy Project Files
Copy all project files into this folder. Your directory should look like this:

pgsql
Copy
Edit
bindisa-agritech-website/
├── public/
│   └── bindisa-agritech-logo.png
├── src/
│   ├── components/
│   ├── contexts/
│   ├── data/
│   ├── lib/
│   ├── pages/
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── index.html
├── package.json
├── tailwind.config.ts
├── tsconfig.json
├── vite.config.ts
└── README.md
4. Install Dependencies
In VS Code terminal:

bash
Copy
Edit
npm install
5. Start Development Server
bash
Copy
Edit
npm run dev
The site will be available at: http://localhost:3000

🎯 Available Scripts
npm run dev - Start development server

npm run build - Build for production

npm run preview - Preview production build

npm run lint - Lint and check code quality

🔧 Recommended VS Code Extensions
ES7+ React/Redux/React-Native Snippets

Tailwind CSS IntelliSense

TypeScript Importer

Auto Rename Tag

Prettier - Code Formatter

🌟 Features Included
✅ 12 Complete Pages
✅ 3 Languages (English, Hindi, Marathi)
✅ Interactive Soil Analysis Tool
✅ AI Chatbot
✅ Authentication System
✅ Team Management
✅ Mobile Responsive Design
✅ Company Contact Form
✅ Google Maps Integration

🎨 Color Scheme
Name	Color Code
Primary Green	#16a34a
Secondary Brown	#92400e
Accent Yellow	#fde68a

📱 Responsive Design
Fully optimized for:

📱 Mobile Phones

📱 Tablets

💻 Laptops

🖥️ Desktop Computers

🌍 Multilingual Support
Supports the following languages:

English (en)

हिंदी (hi)

मराठी (mr)

🔐 Demo Login Credentials
For testing the authentication system:

Email: demo@bindisaagritech.com

Password: demo123

📞 Contact Information
Company: Bindisa Agritech Pvt. Ltd.
Location: Gaya, Bihar, India
Phone: +91 9631157174
CIN: U46539BR2025PTC073688

🔧 Troubleshooting
Node.js version: Ensure Node.js 18+ is installed

Clear cache: Delete node_modules and package-lock.json, then run npm install

Port conflict: Dev server auto-switches to the next available port if 3000 is occupied

TypeScript issues: Run npm run build to surface errors

📚 Technology Stack
React 18 + TypeScript

TailwindCSS for styling

Vite for fast development

shadcn/ui for components

Lucide React for icons

React Router for routing

🚀 Happy Coding!
Built with ❤️ for modern agriculture in India.
