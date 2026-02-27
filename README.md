# Vrit Technologies — SMS API Documentation

Live developer reference for the Vrit SMS Gateway API. Built as a static single-page site — zero dependencies, zero build step.

🔗 **Live Docs:** `https://<your-username>.github.io/<repo-name>/`

---

## What's Covered

| API | Type | Endpoint |
|-----|------|----------|
| Text SMS | GET + POST | `/smsapi/index.php` |
| Flash SMS | GET + POST | `/smsapi/index.php` |
| WAP-Push | GET + POST | `/smsapi/index.php` |
| vCard | GET + POST | `/smsapi/index.php` |
| Unicode SMS | GET + POST | `/smsapi/index.php` |
| Credit Balance | GET | `/miscapi/{key}/getBalance/true/` |
| DLR Fetch | GET | `/miscapi/{key}/getDLR/{shoot_id}` |
| Fetch API Key | GET | `/getkey/{username}/{password}` |
| Last Transaction | GET | `/lasttran/index.php` |

## Features

- **Dynamic API key** — enter your key once, all code examples update instantly
- Tabbed PHP examples for every endpoint (GET/POST × API Key/Password)
- Full parameter tables with required/optional badges and defaults
- Sticky sidebar with active-section tracking
- Copy button on every code block
- Fully responsive

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save** — your docs will be live in ~60 seconds

## Local Preview

No build step needed — just open the file:

```bash
open index.html
# or
python3 -m http.server 8080
```

## Customization

To change the default API key shown in docs, edit line ~8 in `index.html`:

```html
<input ... value="YOUR_API_KEY_HERE" ...>
```

---

Built by [Vrit Technologies](https://vrittechnologies.com)
