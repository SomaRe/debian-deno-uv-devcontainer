# 🐧 Debian Dev Container Template

This is a **GitHub template repository** for quickly setting up a **Dev Container** environment based on **Debian**, pre-configured with useful tools and features for modern development.

> Use this template to spin up consistent development environments in seconds using [Dev Containers](https://containers.dev/).

---

## ✨ Features

- 📦 **Base Image**: `mcr.microsoft.com/devcontainers/base:bullseye`
- ⚙️ **Features Included**:
  - [`uv`](https://github.com/va-h/devcontainers-features/tree/main/src/uv): Python packaging tool
  - [`deno`](https://deno.land/): A modern runtime for JavaScript and TypeScript
- 🧩 **VS Code Extensions**:
  - `ms-python.python`
  - `bradlc.vscode-tailwindcss`
  - `denoland.vscode-deno`
- 🧰 **Post-creation tools**:
  - Installs `xclip`, `wl-clipboard`
  - Installs [`CodeSnap`](https://github.com/SomaRe/codesnap): a utility for capturing and sharing code

---

## 🖼️ About CodeSnap

**CodeSnap** is a utility that helps you quickly capture and share code structure from your projects. It's available in both **Go** and **Python** implementations (Python support to be deprecated soon).

**Features:**
- 📁 Capture content from multiple folders and files
- 🚫 Supports ignore patterns (e.g., `node_modules`, `*.test.js`)
- 📋 Automatically copies to clipboard
- 🔧 YAML-based configuration
- ⏱️ Shows performance metrics

📌 Installed automatically in the container via the latest release binary.

---

## 🚀 Getting Started

1. Click **"Use this template"** on GitHub to create a new repository.
2. Open the new repo in [VS Code](https://code.visualstudio.com/).
3. Install the **Dev Containers** extension if you haven’t already.
4. Reopen the folder in the Dev Container:  
   `F1 → Dev Containers: Reopen in Container`

That's it! You're ready to code.

---

## 🧪 Notes

- Clipboard utilities (`xclip`, `wl-clipboard`) are installed for compatibility with `codesnap`.
- The container runs as the default `vscode` user (not root) for best practice.

---

## 📚 Resources

- [Dev Containers Documentation](https://containers.dev)
- [Deno](https://deno.land)
- [uv](https://github.com/astral-sh/uv)
- [CodeSnap](https://github.com/SomaRe/codesnap)

---

## 📄 License

MIT
