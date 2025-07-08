# Hello Captain – Docker Demo

This is a minimal Docker project that prints **"Hello, Captain!"** to the console and exits.

## 🐳 Project Overview

The container is configured with a single `CMD` instruction using JSON array syntax to ensure proper behavior when run. It demonstrates best practices for simple command execution in Docker.

## 📄 Dockerfile

```dockerfile
CMD ["echo", "Hello, Captain!"]


https://roadmap.sh/projects/basic-dockerfile  