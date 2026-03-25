# ChatGPT iFrame Preview (Client Side)

פרויקט סטטי (HTML/CSS/JS) עם:
- `index.html` — דף ראשי עם iframe לתצוגה מקדימה.
- `preview.html` — תוכן הדגמה פנימי של ה-iframe.

## העלאה ל-GitHub + פרסום לאוויר (GitHub Pages)

> הכנתי עבורך workflow מוכן: `.github/workflows/deploy-pages.yml`.

### 1) צור ריפו ב-GitHub וחבר remote
```bash
git remote add origin <YOUR_GITHUB_REPO_URL>
```

### 2) שנה את שם הענף ל-`main` (אם צריך)
```bash
git branch -M main
```

### 3) דחוף ל-GitHub
```bash
git push -u origin main
```

### 4) הפעל GitHub Pages
ב-GitHub:
- `Settings` → `Pages`
- תחת **Build and deployment** בחר **Source: GitHub Actions**

לאחר push ל-`main`, ה-workflow ירוץ אוטומטית ויעלה את האתר לאוויר.

## כתובת האתר
ברוב המקרים הכתובת תהיה:

`https://<YOUR_GITHUB_USERNAME>.github.io/<YOUR_REPO_NAME>/`

