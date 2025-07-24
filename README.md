<<<<<<< HEAD
# 🎯 AI Talent Sourcing - React Frontend

A modern, beautiful React application for AI-powered candidate matching and skill extraction.

## ✨ Features

### 🚀 **Modern UI/UX**
- **Beautiful Design**: Gradient themes, smooth animations, and modern styling
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Framer Motion animations for enhanced user experience
- **Material-UI**: Professional component library with custom theming

### 🎯 **Candidate Matching**
- **Dual Input Methods**: Upload PDF files or enter text directly
- **Top 10 Analysis**: Detailed analysis of top 10 candidates
- **Strengths & Weaknesses**: AI-powered analysis of candidate strengths and areas for improvement
- **Smart Recommendations**: Personalized recommendations for each candidate
- **Missing Skills Detection**: Identifies skills gaps compared to job requirements

### 🔍 **Skill Extraction**
- **AI-Powered Extraction**: Advanced skill extraction from any text
- **Skill Categorization**: Automatic classification into technical and soft skills
- **Visual Analytics**: Beautiful charts and metrics for skill analysis
- **Real-time Processing**: Instant skill extraction with loading states

### 📊 **Analytics Dashboard**
- **System Metrics**: Real-time performance indicators
- **Match Distribution**: Visual breakdown of candidate scores
- **Skill Demand Analysis**: Market demand for different skills
- **Performance Tracking**: Processing time and success rate monitoring

## 🛠️ Technology Stack

- **React 18** with TypeScript
- **Material-UI (MUI)** for components
- **Framer Motion** for animations
- **React Dropzone** for file uploads
- **Axios** for API communication
- **Custom CSS** with modern styling

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ 
- npm or yarn
- Backend API running on `http://localhost:8000`

### Installation

1. **Navigate to the React app directory:**
   ```bash
   cd cv_frontend/react-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Navigate to `http://localhost:3000`

## 📱 Pages & Features

### 🏠 **Dashboard**
- System overview with key metrics
- Real-time status monitoring
- Feature highlights with beautiful cards

### 🎯 **Match Candidates**
- **File Upload Mode**: Drag & drop PDF files
- **Text Input Mode**: Direct text entry for quick testing
- **Top 10 Analysis**: Detailed candidate breakdown
- **Strengths & Weaknesses**: AI-powered insights
- **Recommendations**: Personalized suggestions

### 🔍 **Extract Skills**
- Text input for skill extraction
- Real-time processing
- Skill categorization (Technical vs Soft)
- Visual skill display with animations

### 📊 **Analytics**
- System performance metrics
- Match distribution analysis
- Skill demand trends
- Processing performance tracking

## 🎨 Design Features

### **Color Scheme**
- Primary: `#667eea` (Blue)
- Secondary: `#764ba2` (Purple)
- Success: `#4caf50` (Green)
- Warning: `#ff9800` (Orange)
- Error: `#f44336` (Red)

### **Animations**
- Page transitions with Framer Motion
- Hover effects on cards and buttons
- Loading states with spinners
- Staggered animations for lists

### **Typography**
- Inter font family
- Gradient text effects
- Responsive font sizing
- Proper hierarchy

## 🔧 Configuration

### **API Configuration**
The app connects to the backend API at `http://localhost:8000`. To change this:

1. Edit `src/services/api.ts`
2. Update the `API_BASE_URL` constant

### **Theme Customization**
To customize the theme:

1. Edit `src/App.tsx`
2. Modify the `theme` object
3. Update colors, typography, and component styles

## 📊 Candidate Analysis Features

### **Top 10 Candidates**
- Score-based ranking
- Visual score indicators
- Expandable details for each candidate

### **Detailed Analysis**
- **Matched Skills**: Skills that align with job requirements
- **Missing Skills**: Skills gaps identified by AI
- **Strengths**: Candidate's strongest areas
- **Weaknesses**: Areas needing improvement
- **Recommendations**: AI-generated suggestions

### **Score Breakdown**
- **90-100%**: Excellent match
- **80-89%**: Very good match
- **70-79%**: Good match
- **60-69%**: Fair match

## 🚀 Deployment

### **Build for Production**
```bash
npm run build
```

### **Serve Production Build**
```bash
npm install -g serve
serve -s build -l 3000
```

## 🔗 API Integration

The React app integrates with the FastAPI backend:

- **POST** `/match-cvs/` - Match candidates from PDF files
- **POST** `/extract-skills/` - Extract skills from text
- **GET** `/health` - Health check endpoint

## 🎯 Key Features Summary

1. **🎨 Modern UI**: Beautiful gradients, animations, and responsive design
2. **📊 Top 10 Analysis**: Detailed breakdown of best candidates
3. **🔍 Missing Skills**: AI identifies what candidates lack
4. **💪 Strengths Analysis**: Highlights candidate strengths
5. **💡 Smart Recommendations**: Personalized suggestions
6. **📱 Dual Input**: PDF upload + text input options
7. **⚡ Real-time Processing**: Instant results with loading states
8. **📈 Analytics**: Comprehensive system insights

## 🎉 Ready to Use!

The React frontend is now ready with all the features you requested:
- ✅ Modern, beautiful UI with animations
- ✅ Top 10 candidate analysis
- ✅ Detailed strengths and weaknesses
- ✅ Missing skills identification
- ✅ Smart recommendations
- ✅ Professional styling and themes

Start the app and enjoy the modern AI talent sourcing experience! 🚀
=======
# AI_Talent_Sourcing
AI_Talent_Sourcing
>>>>>>> fdb9e4251839bf0716a1225bd2957274ea5e5eb4
