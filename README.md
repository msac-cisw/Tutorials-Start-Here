# CISW Tutorials — Start Here 🚀

A beginner-friendly starter template for HTML, CSS, and JavaScript tutorials.  
Everything runs in your browser — no local install needed!

---

## Start Here (No VS Code Needed)

### Step 1 — Make Your Own Copy

Click the button below (or the green **"Use this template"** button at the top of this page) to create your own copy under your GitHub account:

👉 [**Use this template**](https://github.com/msac-cisw/Tutorials-Start-Here/generate)

### Step 2 — Open in Codespaces

In **your copy** of the repo:

1. Click the green **Code** button.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**.

Or use this shortcut to jump straight in:

👉 [**Open in Codespaces**](https://codespaces.new/msac-cisw/Tutorials-Start-Here)

### Step 3 — Run Your Tutorials

Once the codespace finishes loading you have two options:

#### Option A: Live Server (recommended)

1. Open any `.html` file in the editor.
2. Right-click the file and choose **"Open with Live Server"**.
3. A preview tab or browser window will open automatically.

#### Option B: npm start

1. Open the **Terminal** in Codespaces (`` Ctrl+` `` or **Terminal → New Terminal**).
2. If prompted, run:
   ```bash
   npm install
   ```
3. Then start the server:
   ```bash
   npm run start
   ```
4. Codespaces will show a notification with a link to the forwarded port (5500). Click **"Open in Browser"** to view your site.

> **Tip:** Look for the **Ports** tab at the bottom of the Codespaces window to find and open forwarded ports at any time.

---

## Project Structure

```
.
├── index.html                    ← Root page linking to all tutorials
├── tutorials/
│   ├── 01-html-basics/
│   │   └── index.html
│   ├── 02-css-basics/
│   │   └── index.html
│   └── 03-js-basics/
│       └── index.html
├── .devcontainer/
│   └── devcontainer.json         ← Codespaces configuration
├── package.json                  ← Simple dev server &amp; formatter
└── README.md                     ← You are here!
```

---

## Useful Links

| What | Link |
|------|------|
| Create your copy | [Use this template](https://github.com/msac-cisw/Tutorials-Start-Here/generate) |
| Open in Codespaces | [codespaces.new/msac-cisw/Tutorials-Start-Here](https://codespaces.new/msac-cisw/Tutorials-Start-Here) |

---

## Need Help?

Ask your instructor or open an issue in your copy of this repo.
