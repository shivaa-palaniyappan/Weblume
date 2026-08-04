# Weblume — Portfolio Landing Page

A single-page website used to pitch web design services to small businesses that don't yet have a website. Send prospects the live link so they can see your work before agreeing to anything.

**Live demo:** _add your Vercel URL here once deployed_

---

## What's in this repo

```
weblume/
├── index.html      # the entire site (HTML, CSS, JS in one file)
└── README.md        # this file
```

No build tools, no dependencies, no framework. It's a static HTML file — easy to host for free and easy to edit even if you're not deep into code yet.

---

## 1. Before you deploy: personalize it

Open `index.html` and update these placeholders:

| Find | Replace with |
|---|---|
| `[Phone]` | Your phone number |
| `[Email]` | Your email address |
| `wa.me/91XXXXXXXXXX` | Your WhatsApp number, in international format with no `+` or spaces (e.g. `wa.me/919876543210`) |

Optional: update the pricing numbers under `#pricing` to match what you actually want to charge.

---

## 2. Put it on GitHub

If you don't have git installed or aren't comfortable with the command line, you can also just drag-and-drop the file on github.com — see the **"No command line" option** below.

### With git

```bash
# from the folder containing index.html
git init
git add .
git commit -m "Initial commit: Weblume landing page"

# create a new repo on github.com first, then:
git remote add origin https://github.com/<your-username>/weblume.git
git branch -M main
git push -u origin main
```

### No command line

1. Go to [github.com/new](https://github.com/new), create a repo named `weblume` (public is fine).
2. On the new repo page, click **"uploading an existing file"**.
3. Drag `index.html` into the upload box.
4. Scroll down, click **Commit changes**.

---

## 3. Deploy to Vercel (free)

1. Go to [vercel.com](https://vercel.com) and sign up/log in with your GitHub account.
2. Click **Add New → Project**.
3. Select the `weblume` repo you just created and click **Import**.
4. Leave all settings as default (no framework, no build command needed — it's a static file) and click **Deploy**.
5. In under a minute you'll get a live URL like `weblume.vercel.app`.

**Optional — custom domain:** In your Vercel project, go to **Settings → Domains** and add a domain you own (e.g. `weblume.com`) if you buy one later. Not required to get started.

**Updating the site later:** Any time you edit `index.html` and push to GitHub (or re-upload via the web UI), Vercel automatically redeploys the live site within a minute or two. No extra steps needed.

---

## 4. Sending it to customers

Once deployed, share the Vercel link directly:

> Hi, I'm [Your Name] from Weblume — I build websites for small businesses. Here's a sample of the kind of site I build: [your-vercel-url]. I'd love to build something similar for [Business Name]. Would you be open to a quick chat?

Tips:
- Send the **link itself**, not a screenshot — it looks far more credible when they can click around it themselves, especially on their phone.
- Test the WhatsApp button on your own phone before sending it out, to make sure it opens a chat correctly.
- Keep this page updated as you complete real client projects — swap the pricing/copy and eventually add a proper portfolio section with screenshots of sites you've actually shipped.

---

## License

This is your own project — use, edit, and reuse it however you like.
