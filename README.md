# 📊 CodeTrace

CodeTrace is a comprehensive coding profile tracking and performance analytics platform designed for college students. It aggregates coding platform data, evaluates performance, and presents leaderboards to encourage consistency, competition, and growth among students.

---

## 🚀 Features

- 🎓 **College-Based Registration**
  - Students register using their **college email ID**
  - Ensures authenticity and controlled access

- 🔗 **Coding Profile Integration**
  - Add profiles from popular coding platforms (e.g., LeetCode, CodeChef, Codeforces, HackerRank)
  - Centralized view of all coding activity

- 📈 **Performance Scoring System**
  - Scores are calculated based on:
    - Problem-solving activity
    - Contest participation
    - Platform-specific metrics
  - Fair and transparent scoring logic

- 🏆 **Leaderboards**
  - College-wide and branch-wise leaderboards
  - Rank students based on calculated scores

- 🧑‍💼 **Admin Controls**
  - Verify student accounts
  - Manage users and platform configurations
  - Control leaderboard visibility

- 🧭 **Clean Dashboard**
  - Simple and intuitive UI
  - Easy navigation between profiles, scores, and rankings

---

## 🛠️ Tech Stack

- **Backend:** ASP.NET Core Web API  
- **Frontend:** Angular  
- **Database:** SQL Server  
- **Authentication:**

---

## 🗃️ How CodeTrace Works

1. Student registers using a **college email ID**
2. Student adds links to their coding platform profiles
3. System fetches and processes profile data
4. Scores are calculated using predefined rules
5. Leaderboards are updated dynamically
6. Admins monitor and manage the platform

---

## 🔐 Security & Access

- Access restricted to verified college users
- Role-based access (Student / Admin)
- Secure APIs with authentication and authorization (planned)

---

## 🚧 Future Enhancements

- 🤖 Automated profile data scraping
- 📊 Detailed analytics & performance graphs
- 🔔 Notifications for contests and opportunities
- 🏅 Badges and achievement system
- 🌐 Multi-college support
- 📱 Mobile-friendly UI

---

## 🏗️ Setup & Installation

### Backend (ASP.NET Core API)

```bash
# Clone the repository
git clone https://github.com/your-username/codetrace.git

# Navigate to backend
cd codetrace/Backend

# Restore dependencies
dotnet restore

# Apply migrations
dotnet ef database update

# Run the API
dotnet run
