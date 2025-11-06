# 🌱 M-Restore — AI-Powered Soil & Land Analysis from Images

**M-Restore** is a web application that lets farmers and landowners upload photos of their **soil or farmland** to receive **instant AI-powered insights**, including:

- Detected soil type (e.g. *Clay*, *Sandy*)
- Soil improvement recommendations
- Best crops to grow for that soil type
- Detected features (e.g. vegetation, water)

It helps support smarter farming and land restoration using modern technology.

**Live Demo:** [https://m-restorefarmapp.onrender.com](https://m-restorefarmapp.onrender.com)

---

## 📸 How It Works

1. **Log in** securely via [Supabase](https://supabase.com).
2. **Upload a photo** of your farm, soil, or land.
3. Optionally, **share your location** (GPS).
4. The AI model (powered by **Gemini**) analyzes the image and returns:
   - ✅ **Soil Type**
   - 🛠️ **Recommendations** (how to improve it)
   - 🌾 **Suggested Crops**
   - 🌳 **Detected Features** (like vegetation)

---

## ✅ Example Output

```
🔍 Soil Type: Clay soil detected

🛠️ Recommendations:
• Add sand and organic matter for better drainage
• Remove large rocks and debris

🌾 Suggested Crops: Wheat, Barley, Tomatoes, Lettuce

🧠 Detected Objects: Vegetation
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** package manager
- **Git** - [Download here](https://git-scm.com/)
- A **Supabase account** - [Sign up here](https://supabase.com)
- A **Google Gemini API key** - [Get one here](https://makersuite.google.com/app/apikey)

### 📥 Clone the Repository

```bash
# Clone the repository
git clone https://github.com/feisaladen/m-restore.git

# Navigate into the project directory
cd m-restore
```

### 📦 Install Dependencies

```bash
# Using npm
npm install

# Or using yarn
yarn install
```

### ⚙️ Environment Setup

Create a `.env` file in the root directory and add your credentials:

```env
# Supabase Configuration
SUPABASE_URL=your_supabase_project_url
SUPABASE_ANON_KEY=your_supabase_anon_key

# Google Gemini API
GEMINI_API_KEY=your_gemini_api_key

# Server Configuration
PORT=3000
NODE_ENV=development
```

**How to get your credentials:**

1. **Supabase:**
   - Go to your [Supabase Dashboard](https://app.supabase.com/)
   - Select your project
   - Go to Settings → API
   - Copy the `Project URL` and `anon public` key

2. **Gemini API:**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create or select a project
   - Generate an API key

### 🏃 Run the Application

```bash
# Start the development server
npm start

# Or with yarn
yarn start
```

The app will open automatically at [http://localhost:3000](http://localhost:3000)

### 🏗️ Build for Production

```bash
# Create an optimized production build
npm run build

# Or with yarn
yarn build
```

The production-ready files will be in the `build/` directory.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, Tailwind CSS
- **Backend:** JavaScript (Node.js)
- **Authentication:** Supabase Auth
- **Database:** Supabase (PostgreSQL)
- **AI Model:** Google Gemini Vision API
- **Deployment:** Render

---

## 📱 Features

- ✅ Secure user authentication
- 📷 Image upload and analysis
- 🗺️ GPS location tracking
- 🤖 AI-powered soil type detection
- 🌾 Crop recommendations
- 💾 History of past analyses
- 📊 Dashboard with insights

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Feisal Aden**
- Email: feisaladen32@gmail.com

---

## 🙏 Acknowledgments

- [Supabase](https://supabase.com) for authentication and database
- [Google Gemini](https://deepmind.google/technologies/gemini/) for AI image analysis
- [Render](https://render.com) for hosting

---

## 📞 Support

If you encounter any issues or have questions, contact via email: **feisaladen32@gmail.com**

---

**Made by human  to serve humanity** 🌍❤️

