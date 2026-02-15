# Spaghetti (OpenAPI Renderer)

Spaghetti is a modern, intuitive, and customizable **API documentation renderer for VS Code**, designed for developers who want more flexibility and a better in-editor experience than traditional tools like Swagger UI, ReDoc, Postman, or RapidAPI.

![Spaghetti Screenshot](screenshots/Screenshot%202026-02-02%20085702.png)

---

## 🚀 Overview

Spaghetti provides a smooth and interactive interface for exploring, testing, and understanding APIs **directly inside VS Code**. It is inspired by existing API tools but built with a strong focus on usability, performance, and developer workflow.

Instead of switching between browsers and external tools, Spaghetti keeps your API documentation and exploration where you write your code.

Whether you’re working with **FastAPI, Express, Django, Laravel**, or any backend framework that exposes an OpenAPI specification, Spaghetti helps you visualize and work with your API efficiently.

---

## ✨ Features

- 🧭 **Clean and modern UI** – Easy to navigate and visually focused.
- ⚡ **Fast and responsive** – Optimized for smooth interactions inside VS Code.
- 📚 **OpenAPI rendering** – View endpoints, schemas, and models clearly.
- 🧩 **Complex schema support** – Supports `oneOf`, `anyOf`, `allOf`, and nested models.
- 🗂️ **Multi-project support** – Load and switch between multiple OpenAPI projects.
- 🔄 **Project reload** – Re-fetch API specs from file or URL when changes occur.
- 🧠 **State-aware panels** – Automatically closes stale views when project data changes.
- **Search enpoint** - Easy search for endpoint
- **Offline note** - Keep note per endpoint and track note status.

> More features such as request execution, environments, and variables are actively planned.

---

## 📦 Installation

1. Open **VS Code**
2. Go to the **Extensions Marketplace**
3. Search for **Spaghetti (API Doc Renderer)**
4. Install and reload VS Code

---

## 🛠️ Getting Started

1. Open the **Spaghetti** sidebar
2. Add a new project using:
   - a local OpenAPI JSON/YAML file, or
   - a remote OpenAPI URL
3. Explore endpoints and schemas directly in VS Code

Detailed usage documentation is coming soon.

---

## 💡 Motivation

My first exposure to API documentation was through **FastAPI’s built-in Swagger UI**, which later led me to tools like ReDoc, Postman, and RapidAPI.

While these tools are powerful, I wanted:

- tighter VS Code integration
- better control over presentation
- a smoother, more focused developer experience

Spaghetti is built to solve those needs—and to grow based on real developer feedback.

---

## 📄 License

MIT License
