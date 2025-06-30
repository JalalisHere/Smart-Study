# Smart-Study
An intuitive cross-platform (Android &amp; iOS) mobile app designed to help students plan their study sessions, manage deadlines, and stay productive with built-in reminders and progress tracking.



---

## 🎯 Purpose

This app empowers students to take control of their academic life by:
- Organizing study schedules
- Setting timely reminders for tasks, exams, and deadlines
- Monitoring their progress and productivity

Built using **React Native**, the app runs smoothly on both Android and iOS devices.

---

## 🚀 Features

- 📅 **Create and manage tasks** (title, subject, due date, reminder time)
- 🔔 **Push notifications** for upcoming tasks (using Firebase Cloud Messaging)
- ✅ **Mark tasks as complete**
- 📊 **Progress tracker**: See how many tasks you’ve completed
- 🔍 **Filter tasks** by status, date, or subject
- 🌓 **Dark mode** for night owls
- 🔐 **Secure login system** using Firebase Authentication

---

## 🛠️ Tech Stack

| Area         | Tech Used                     |
|--------------|-------------------------------|
| Mobile UI    | React Native                  |
| Backend      | Firebase (Firestore + Auth + Messaging) |
| Notifications | Firebase Cloud Messaging (FCM) |
| State Mgmt   | React Context or Redux        |
| Styling      | React Native Paper / Tailwind / Styled Components |

---

## 📱 Screenshots  
> _(Add these after you build a few screens)_  
- Home screen with task list  
- Task creation form  
- Reminder pop-up  
- Progress dashboard  

---

## 🧑‍💻 Getting Started

### Prerequisites
- Node.js & npm
- Expo CLI (`npm install -g expo-cli`)
- Firebase account

### Run Locally
```bash
git clone https://github.com/your-username/smart-study-planner.git
cd smart-study-planner
npm install
expo start
