# 🦅 HURASE CLI Ecosystem
### *Turning Node.js, bun.js Backend into a Professional Production Line*
**Hurase** is a powerful, context-aware CLI designed to build high-performance Backends using **Hono.js** with the architectural discipline of **NestJS**. It’s built for speed, scalability, and zero runtime overhead.
## 🚀 Key Features
 * ⚡ **Ultra Fast:** Project initialization and module generation in milliseconds.
 * 🏗️ **Modular Monolith:** Built-in support for isolated apps within a single project.
 * 🤖 **Context-Aware AI (Coming Soon):** Intelligent code generation that understands your project structure.
 * 🛠️ **Zero Runtime Overhead:** Hurase disappears after build; only pure, high-performance Hono.js remains.

## 📦 Installation
```bash
npm i -g @hurase/cli

```
## 🛠️ Quick Start
### 1. Initialize a new project
![Hurase init](https://raw.githubusercontent.com/nadline-c/-hurase-cli/refs/heads/main/assets/IMG-20260414-WA0001.jpg)
```bash
hurase init

```
### 2. Create a new micro-app
```bash
hurase create:app

```
### 3. Add a new router (Inside app directory)
```bash
hurase make:router

```
### 4. Overview your project
```bash
hurase info:project

```
## 📂 Project Structure
Hurase enforces a clean, industry-standard directory layout:
```text
./
├── apps/               # Your micro-applications (e.g., admin, api)
├── config/             # Centralized DB and Server configs
├── plugins/            # Shared logic and middlewares
├── schemas/            # Single Source of Truth for data
├── hurase.json          # Project DNA
└── main.js             # Entry point

```
## 🛡️ Architecture & Philosophy
Hurase follows the **Tooling vs Framework** philosophy. We provide the scaffolding and the automation, giving you full control over your code without any vendor lock-in.
## 🌐 Roadmap
 * [x] Core CLI Engine (v0.10.0)
 * [ ] Advanced Schema Injection (v0.15.0)
 * [ ] **Hurase AI Integration** (v0.21.0)
 * [ ] Official v1.0.0 Release
## 👨‍💻 Author

Proudly part of **SHG (Saad Hammam Group)**.
### **"Built for the World, Designed by an Architect."**
