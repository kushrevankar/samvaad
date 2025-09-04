*I will change the readme to a formal description as we approach the final submission. For now, please follow the files with your names you need to commit your work on. I'll give you the necessary permissions by today EoD.*

```
samvaad/
  ├── gui/          # ReactJS (Ansh)
  ├── cv_module/    # ISL recognition (Shreyas)
  ├── voice_module/ # STT + translation + TTS (Araham)
  ├── integration/  # Integration (Kush)
  ├── assets/       # Icons, UI assets, etc.
  ├── main.py       # Final app entry point
```
---

## Git Workflow for Team

### 1. Clone the Repository

```bash
git clone <repo-url>
cd <repo-name>
```

---

### 2. Switch to `dev` Branch (Always work here)

```bash
git checkout dev
git pull origin dev
```

---

### 3. Add & Commit Your Changes

```bash
git add .
git commit -m "Your meaningful commit message"
```

---

### 4. Push Changes to `dev`

```bash
git push origin dev
```

---

### 5. Sync Your Local `dev` Regularly

```bash
git pull origin dev
```

---

## Master Branch Rules

* **Do NOT commit or push to `master`.**
* `master` = production-ready code only.
* Only the lead (Kush) merges `dev → master`.

---

### 6. For Lead (Merging to Master)

```bash
git checkout master
git pull origin maste
git merge dev
git push origin master
```

---

**Tip:** If you get a merge conflict, solve it locally before committing.

---
