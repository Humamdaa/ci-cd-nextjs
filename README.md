### 🚀 Auto‑Deploy to Vercel (CI/CD)

This project demonstrates how to automatically deploy to **Vercel** using **GitHub Actions**.  
Every push triggers the workflow, runs tests, and deploys the project.

---

### 📂 What We Learned

- **GitHub Actions can auto‑deploy** to Vercel using a workflow file.
- **Correct YAML indentation is required** for GitHub Actions to run.
- Vercel needs three secrets:
  - `VERCEL_TOKEN`
  - `VERCEL_ORG_ID`
  - `VERCEL_PROJECT_ID`
- Vercel does **not** run normal Node servers (`node index.js`).
- Backend logic must be placed inside the **/api** folder as a **serverless function**.
- The deployed API endpoint becomes available at `/api`.

---

### 🌐 Live API Endpoint

```
/api
```

This returns the message .
