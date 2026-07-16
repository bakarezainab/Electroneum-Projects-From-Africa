# Quick Submission Guide

## 🚀 Submit Your Project in 5 Minutes

### Step 1: Fork the Repository
Click here: https://github.com/electroneumafrica/Electroneum-Projects-From-Africa/fork

### Step 2: Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/Electroneum-Projects-From-Africa.git
cd Electroneum-Projects-From-Africa
```

### Step 3: Create Branch from `submissions`
```bash
git fetch origin submissions
git checkout -b add/your-project-name origin/submissions
```

### Step 4: Add Your Project

Edit `PROJECTS_REGISTRY.md` and add:

```markdown
#### Your Project Name
- **Developer:** Your Name
- **Country:** Your Country
- **Repository:** https://github.com/your-username/your-repo
- **Live Demo:** https://your-live-url.com
- **Description:** Brief description of your dApp
- **Tech Stack:** React, Solidity, etc.
```

### Step 5: Commit & Push
```bash
git add PROJECTS_REGISTRY.md
git commit -m "Add Your Project Name to registry"
git push origin add/your-project-name
```

### Step 6: Create Pull Request
1. Go to: https://github.com/electroneumafrica/Electroneum-Projects-From-Africa
2. Click "Compare & pull request"
3. **Make sure the target branch is `submissions`** (not main)
4. Click "Create Pull Request"

### Done! 🎉
Wait for approval and your project will be added to the registry!

---

## ✅ Before You Submit

- [ ] Your project repository is public
- [ ] README.md explains what it does
- [ ] Setup instructions are included
- [ ] Code is working (even if incomplete)

That's it! Questions? Open an issue.
