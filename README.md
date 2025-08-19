# Tiktok Videos Processor
A sophisticated AI-powered video analytics platform designed to help content creators and marketers analyze TikTok video performance, extract insights, and optimize content strategy.

---

## 🌟 Features

### 🎯 Core Functionality
- **Video Import & Analysis**: Import TikTok videos via URL for comprehensive AI analysis  
- **Performance Analytics**: Detailed engagement metrics and performance insights  
- **AI-Powered Summaries**: Automated video content analysis and key takeaways  
- **Smart Collections**: Organize videos with custom collections and tags  
- **Global Analytics**: Cross-video library insights and trend analysis  

---

### 🎨 Design System
- **Modern Dark UI**: Professional Bloomberg Terminal-inspired interface  
- **Application Color Scheme**: Consistent pink and dark theme throughout  
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices  
- **Smooth Animations**: Enhanced user experience with thoughtful transitions  

---

### 🤖 AI Capabilities
- **Content Analysis**: Automatic video content categorization and summarization  
- **Engagement Scoring**: Performance prediction and optimization recommendations  
- **Trend Identification**: Pattern recognition across your video library  
- **Chat Interface**: Natural language queries about your video analytics  

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router  
- **TypeScript** - Type-safe development  
- **Tailwind CSS** - Utility-first styling with custom SKYLAR theme  
- **shadcn/ui** - Beautifully designed components  
- **Lucide React** - Consistent iconography  

### Backend
- **Python** - AI and data processing  
- **FastAPI** - RESTful API endpoints  
- **PostgreSQL** - Relational database  
- **Redis** - Caching and real-time features  

### AI/ML
- **Computer Vision** - Video content analysis  
- **NLP** - Transcript processing and summarization  
- **Predictive Analytics** - Performance forecasting  

## 📦 Installation

### Prerequisites
- **Node.js 18+**
- **PostgreSQL 12+**
- **Python 3.9+**
- **Redis**

---

### ⚡ Frontend Setup

```bash
# Clone the repository
git clone https://github.com/haziq-Ali5/tiktok_insights  
cd ask-skylar

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your configuration

# Run development server
npm run dev 

### ⚙️ Backend Setup

# Navigate to backend directory
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Edit .env with your configuration

# Run the API server
uvicorn main:app --reload --host 0.0.0.0 --port 8000
