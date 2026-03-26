# be/impact Brand Identity Plugin

This plugin teaches Claude the be/impact brand — colors, fonts, tone, layout patterns — so everything it creates for you looks and sounds like be/impact. You don't need to describe the brand every time. Just ask for what you need.

**Examples of things you can ask:**

- "Write an email inviting nonprofits to our next cohort"
- "Create a slide deck for the investor meeting"
- "Draft a one-pager about be/impact for partners"
- "Write a LinkedIn post announcing the program"
- "Make a proposal for [client name]"

Claude will automatically use the right colors, fonts, and voice.

---

## How to install (Claude Desktop app)

### Step 1 — Add the plugin source

1. Open **Claude Desktop**
2. Click on the **Code** tab (bottom of the sidebar)
3. Type `/plugins` in the message box and press Enter
4. A dialog opens. Click the **Marketplaces** tab
5. Click **Add marketplace**
6. Enter this:
   - **Name:** `beimpact-brand`
   - **Source:** GitHub
   - **Repo:** `fabien-beimpact/beimpact-brand`
7. Click **Save**

### Step 2 — Install the plugin

1. Still in the `/plugins` dialog, go back to the **Plugins** tab
2. You should see **beimpact-brand** in the list
3. Click **Install**
4. Choose **"Install for you"** (so it works everywhere, not just one project)
5. Done!

### Step 3 — There is no step 3

Just start asking Claude to create things. The brand knowledge is always there in the background.

---

## How to install (terminal — if you prefer)

If you use Claude Code in a terminal:

```bash
claude plugin add github:fabien-beimpact/beimpact-brand
```

---

## What's inside

One skill file that contains:
- **Voice & writing style** — how be/impact sounds (direct, warm, empowering)
- **Fonts** — Bitter for headings, Work Sans for body
- **Colors** — the full palette with clear roles for each color
- **Layout patterns** — the signature dark/light split panel
- **Practical templates** — how to structure slides, emails, PDFs, social posts
- **Design principles** — whitespace, hierarchy, contrast, accessibility