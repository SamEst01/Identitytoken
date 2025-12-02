# ai-childrens-books

Private GitHub repository scaffold for AI-generated children's books. Development is intended to run fully in Codex Web (cloud-based) with no local dependencies.

## Repository setup
1. Create a **private** GitHub repository named `ai-childrens-books` (or `livros-infantis-ai`).
2. Enable cloud-based development through Codex Web; no local environment is required.
3. Include the provided `.gitignore` and optional MIT License from this scaffold.

## Project overview
- Explore and prototype AI-assisted generation of children’s book content and illustrations.
- Maintain notebooks, prompts, and assets within this repo.

## Structure
- `.gitignore` — Combined Node.js and Python ignores for hybrid workflows.
- `LICENSE` — MIT License (optional; use if you want to share the code).

## Getting started
The scaffold files live in this directory now; they will not appear in GitHub until you push them. Use the steps below (from inside this folder) to publish to your private repo:

```bash
git init                # if this folder is not already a repo
git remote add origin <your-private-repo-url>
git add .
git commit -m "Initial scaffold"
git push -u origin main
```

- After pushing, the files (`README.md`, `.gitignore`, `LICENSE`) will show up in GitHub.
- Add notebooks or source code under directories such as `notebooks/`, `src/`, or `assets/` as the project evolves.
- Document workflows and prompts in additional README files as needed.
