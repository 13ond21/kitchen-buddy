# Kitchen Buddy â€” GitHub Pages (Privacy & Terms)

Calm static site matching the app theme for Google Play **Privacy policy URL** and **Terms**.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of use |
| `styles.css` | Oatmeal / accent theme |

## Publish on GitHub Pages (recommended)

### Option A â€” New public repo (simplest)

1. On GitHub.com â†’ **New repository**  
   - Name e.g. `kitchen-buddy` or `luckytools-legal`  
   - **Public**  
   - Do **not** add a README if you will push this folder as the root.

2. On your PC (GitHub CLI or Git):

```powershell
cd C:\Users\corey\sync_cook_flutter\github-pages
git init
git add .
git commit -m "Kitchen Buddy privacy and terms site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/kitchen-buddy.git
git push -u origin main
```

3. GitHub repo â†’ **Settings â†’ Pages**  
   - Source: **Deploy from a branch**  
   - Branch: **main** / folder **/** (root)  
   - Save  

4. After a minute, open:

```
https://YOUR_USERNAME.github.io/kitchen-buddy/
https://YOUR_USERNAME.github.io/kitchen-buddy/privacy.html
https://YOUR_USERNAME.github.io/kitchen-buddy/terms.html
```

### Option B â€” Repo already named `username.github.io`

Push these files to the root (or `/docs`) of that repo so the URL has no project path:

```
https://YOUR_USERNAME.github.io/privacy.html
```

## Play Console fields

| Field | URL |
|--------|-----|
| **Privacy policy** | `https://YOUR_USERNAME.github.io/kitchen-buddy/privacy.html` |
| **Terms** (if asked) | `https://YOUR_USERNAME.github.io/kitchen-buddy/terms.html` |

Replace `YOUR_USERNAME` and repo name with yours.

## Email

Policies use **autoaccentsni@gmail.com**. Change in all HTML files if your support address differs.

## Local preview

Open `index.html` in a browser, or:

```powershell
cd C:\Users\corey\sync_cook_flutter\github-pages
python -m http.server 8080
```

Then visit `http://localhost:8080`
