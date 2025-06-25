
<div align="center">
  <h1>📁 Storage and File Sharing Platform</h1>
  <p>A modern web app for uploading, organizing, and sharing files with a responsive UI and secure Appwrite backend.</p>

  <div>
    <img src="https://img.shields.io/badge/-Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
    <img src="https://img.shields.io/badge/-Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" />
  </div>
</div>

---

## 📌 Overview

This is a fully-featured storage management and file-sharing platform built using the latest modern stack — including **Next.js 15**, **React 19**, **TailwindCSS**, and **Appwrite**. It enables users to:

- Upload and manage various file types
- Authenticate with secure login/register
- Share, view, rename, and delete files
- Monitor storage usage via a dynamic dashboard

---

## ⚙️ Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: TailwindCSS, ShadCN UI
- **Backend**: Appwrite (Authentication, Database, File Storage)
- **Package Manager**: npm

---

## 🚀 Features

- ✅ **Authentication**: Signup, Login, Logout via Appwrite
- ✅ **File Upload**: Images, Videos, Documents, Audio
- ✅ **File Management**: Rename, Delete, Preview, Download
- ✅ **File Sharing**: Generate shareable links
- ✅ **Dashboard**: Storage usage insights, recent uploads
- ✅ **Global Search**: Find files by name or type
- ✅ **Sorting**: Sort by date, size, or name
- ✅ **Modern UI**: Fully responsive and accessible layout

---

## ⚡ Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

### 🧾 Installation

1. **Clone the repository**

```bash
git clone https://github.com/JavaScript-Mastery-Pro/storage_management_solution.git
cd storage_management_solution
```

2. **Install dependencies**

```bash
npm install
```

3. **Configure environment variables**

Create a `.env.local` file in the root directory and add the following:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT="your-project-id"
NEXT_PUBLIC_APPWRITE_DATABASE="your-database-id"
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your-users-collection-id"
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your-files-collection-id"
NEXT_PUBLIC_APPWRITE_BUCKET="your-bucket-id"
NEXT_APPWRITE_KEY="your-appwrite-api-key"
```

You can find these values in your [Appwrite console](https://appwrite.io/).

4. **Run the development server**

```bash
npm run dev
```

Visit **http://localhost:3000** in your browser to view the application.

---

## 📎 Assets

You can find the UI assets and resources used in this project here:  
👉 [https://jsm.dev/gdrive-kit](https://jsm.dev/gdrive-kit)

---

## 📚 License

This project is for educational and personal use. Feel free to explore, modify, and build upon it!
