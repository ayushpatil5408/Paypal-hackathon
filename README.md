# PayPal Hackathon

Welcome to the team repository for the PayPal Hackathon!

---

## 👥 Team & Branches

| Collaborator | GitHub Profile | Dedicated Branch |
| :--- | :--- | :--- |
| **Ayush Patil** (Lead) | [@ayushpatil5408](https://github.com/ayushpatil5408) | `ayushpatil5408` |
| **LAMBO163** | [@LAMBO163](https://github.com/LAMBO163) | `LAMBO163` |
| **Michael Camill** | [@MichaelCamill](https://github.com/MichaelCamill) | `MichaelCamill` |
| **Manan Gwalani** | [@MananGwalani22](https://github.com/MananGwalani22) | `MananGwalani22` |

---

## 🚀 Collaborator Workflow

All collaborators must work in their dedicated branches. Direct pushes to `main` are restricted — all changes must be merged via **Pull Requests (PR)** reviewed by `@ayushpatil5408`.

### 1. Clone the Repository
```bash
git clone https://github.com/ayushpatil5408/Paypal-hackathon.git
cd Paypal-hackathon
```

### 2. Switch to Your Assigned Branch
Replace `<your-branch>` with your branch name (`LAMBO163`, `MichaelCamill`, `MananGwalani22`, or `ayushpatil5408`):
```bash
git checkout <your-branch>
git pull origin <your-branch>
```

### 3. Work, Commit, and Push
```bash
# Add modified/new files
git add .

# Commit with a clear message
git commit -m "feat: description of work done"

# Push to your remote branch
git push origin <your-branch>
```

### 4. Open a Pull Request (PR)
1. Go to the repository on GitHub: [ayushpatil5408/Paypal-hackathon](https://github.com/ayushpatil5408/Paypal-hackathon).
2. Click on **Pull requests** > **New pull request**.
3. Set **base: `main`** $\leftarrow$ **compare: `<your-branch>`**.
4. Submit the PR for review. Once approved, it will be merged into `main` by Ayush.

---

## 🔄 Keeping Your Branch Updated with `main`
Whenever updates are merged into `main`, update your local branch to stay in sync:
```bash
git checkout main
git pull origin main
git checkout <your-branch>
git merge main
git push origin <your-branch>
```
