# HTAT - Human Tracking & Tagging System

## 🎯 Overview

**HTAT** (Human Tracking & Tagging) is an intelligent attendance management system that revolutionizes how educational institutions track student attendance. The system, branded as **A-SYST**, leverages artificial intelligence and computer vision to provide automated, real-time attendance monitoring through strategically placed cameras.

## ✨ Features

### 🤖 AI-Powered Attendance
- **Real-time monitoring** through camera systems at entry/exit points
- **Computer vision** algorithms for accurate student identification
- **Automated tracking** eliminates manual attendance taking

### 👥 Multi-User System
- **Instructor Portal**: Schedule classes and view attendance reports
- **Admin Dashboard**: Comprehensive system management and oversight
- **Student Tracking**: Seamless attendance recording without disruption

### 📊 Data Management
- **Attendance Reports**: Detailed analytics and reporting
- **Class Scheduling**: Efficient class management tools
- **Data Analysis**: Insights into attendance patterns and trends
- **Record Generation**: Customizable attendance records

### 🔒 Security & Reliability
- **Secure tracking** mechanism
- **Fair attendance** system preventing manipulation
- **Efficient processing** for large student populations

## 🏗️ System Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Camera Feed   │───▶│   AI Processing │───▶│   Web Portal    │
│  (Entry/Exit)   │    │  (Recognition)  │    │ (Dashboard/UI)  │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         ▼                       ▼                       ▼
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Image Capture  │    │  Student ID &   │    │  Attendance     │
│   & Streaming   │    │   Verification  │    │   Reports       │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- OpenCV
- TensorFlow/PyTorch (for AI models)
- Web framework (Flask/Django)
- Database system (MySQL/PostgreSQL)


## 📋 Usage

### For Instructors
1. **Login** to the instructor portal
2. **Schedule classes** using the class management interface
3. **View attendance reports** for real-time and historical data
4. **Export records** in various formats (PDF, Excel, CSV)

### For Administrators
1. **Access admin dashboard** with full system privileges
2. **Manage users** (instructors and students)
3. **Configure system settings** and camera parameters
4. **Monitor system performance** and generate comprehensive reports

### For Students
- **Automatic attendance** - simply enter/exit monitored areas
- **No manual check-in** required
- **Real-time status** updates



## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*This project was developed as a Final Year Project to demonstrate the potential of AI in educational technology.*
