# Strapi Task – Local Setup

This repository contains my task submission for setting up **Strapi locally**, exploring its structure, creating a sample content type, and pushing the setup to GitHub with proper documentation.

---

## 🔧 Prerequisites

Before starting, the following tools were installed:

- **Node.js** (v20.x)
- **npm**
- **Git**
- **Strapi**


Project Setup Steps
Create Strapi Application
bash
npx create-strapi-app my-strapi-app
cd my-strapi-app

npm run develop
http://localhost:1337
http://localhost:1337/admin

 Explore Project Folder Structure
Key folders explored:
config/ – project configuration
src/ – APIs and content types
public/ – public assets
database/ – local database files
README.md – documentation

Initialize Git Repository
git init
git branch -M main
git checkout -b sakshi-strapi

git add .
git commit -m "Initial Strapi setup"
git push origin sakshi-strapi

Pull Request
Pull Request raised from sakshi-strapi → main


