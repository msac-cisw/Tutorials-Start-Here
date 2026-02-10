# CISW Tutorials — Start Here 🚀

A beginner-friendly starter template for HTML, CSS, and JavaScript tutorials.  
Everything runs in your browser — no local install needed!

---

## Start Here (No VS Code Needed)

### Step 1 — Open in Codespaces

Click the link below to launch your own coding environment in your browser:

👉 [**Open in Codespaces**](https://codespaces.new/msac-cisw/Tutorials-Start-Here)

That's it! GitHub will create a personal workspace for you automatically. Wait for it to finish loading (this may take a minute the first time).

### Step 2 — Run Your Tutorials

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

## Tutorials

Each tutorial has a matching demo at [cisw17-demos](https://msac-cisw.github.io/cisw17-demos/).

| Folder | Tutorial | Demo |
|--------|----------|------|
| `web00-basic-html` | A Basic HTML Page | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web00-basic-html.html) |
| `web03-happy-sad` | Happy or Sad | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web03-happy-sad.html) |
| `web04-links` | Links | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web04-links.html) |
| `web05-custom-homepage` | Custom Homepage | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web05-custom-homepage.html) |
| `web06-simple-animations` | Simple CSS Animations | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web06-simple-animations.html) |
| `git-intro` | Intro to Git | [demo](https://msac-cisw.github.io/cisw17-demos/demos/git-intro.html) |
| `web09-quote-generator` | Random Quote Generator | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web09-quote-generator.html) |
| `web10-silly-poem` | A Silly Poem | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web10-silly-poem.html) |
| `web11-rps` | Rock, Paper, Scissors | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web11-rps.html) |
| `web12-dark-mode` | Toggle Dark Mode | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web12-dark-mode.html) |
| `web17-simple-nodejs` | Simple Node.js App | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web17-simple-nodejs.html) |
| `web18-simple-typescript` | Simple TypeScript App | [demo](https://msac-cisw.github.io/cisw17-demos/demos/web18-simple-typescript.html) |
| `docker01-simple-web` | Simple Webserver & PHP | [demo](https://msac-cisw.github.io/cisw17-demos/demos/docker01-simple-web.html) |
| `py13-hello-flask` | Hello, Flask | [demo](https://msac-cisw.github.io/cisw17-demos/demos/py13-hello-flask.html) |

---

## Project Structure

```
.
├── index.html                          ← Root page linking to all tutorials
├── tutorials/
│   ├── web00-basic-html/
│   ├── web03-happy-sad/
│   ├── web04-links/
│   ├── web05-custom-homepage/
│   ├── web06-simple-animations/
│   ├── git-intro/
│   ├── web09-quote-generator/
│   ├── web10-silly-poem/
│   ├── web11-rps/
│   ├── web12-dark-mode/
│   ├── web17-simple-nodejs/
│   ├── web18-simple-typescript/
│   ├── docker01-simple-web/
│   └── py13-hello-flask/
├── .devcontainer/
│   └── devcontainer.json               ← Codespaces configuration
├── package.json                        ← Simple dev server & formatter
└── README.md                           ← You are here!
```

---

## Need Help?

Ask your instructor or open an issue in your copy of this repo.