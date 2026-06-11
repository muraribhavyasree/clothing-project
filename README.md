# 🧵 FitCraft — Custom-Fit Clothing Platform

FitCraft is a modern, premium web application designed to solve the fashion industry's "fixed size" problem by enabling direct customer-to-tailor garment personalization through body measurements.

---

## 📖 Project Wiki & Documentation

We have moved all project details, architecture outlines, features, and deployment configurations to our **[FitCraft Project Wiki](../../wiki)**.

For a comprehensive understanding of the platform, database schemas, feature roadmap, and development updates, please visit:
👉 **[Go to the Project Wiki](../../wiki)**

---

## 🚀 Quick Start

To run the project locally, run a single install command:

### 1. Installation & Auto-Setup
Run the following command at the root of the project:
```bash
npm install
```
> [!NOTE]
> Running `npm install` automatically triggers our **interactive environment setup utility** under the hood. It will configure the environment variables (`.env`) for both the frontend and backend with default/custom values automatically.

### 2. Run the Application
Start the frontend and backend servers concurrently:
```bash
npm run dev
```
- **Frontend URL**: [http://localhost:5173](http://localhost:5173)
- **Backend API URL**: [http://localhost:5001](http://localhost:5001)

---

## 🛠️ Project Structure

- `apps/frontend`: React (Vite) client application
- `apps/backend`: Express.js API server
