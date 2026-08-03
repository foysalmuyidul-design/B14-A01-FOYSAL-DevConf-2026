## 🎨 PLACEHOLDER SECTION — AI CHALLENGE 

-Venue
**submiting the prompts**-
1.Generate a relevant section - must stay relevant to the DevConf 2026 theme (e.g. Sponsors, Venue, FAQ, Newsletter Signup, Hackathon Details, Past Highlights, Job Board, etc.).
2.not code, scartch
3.Venue Section penpot file
4.Generate an SVG mockup that I can import into Penpot with all elements editable
5.generate a large venue photo

## 🔸 Other Requirements (Must Follow)
- Minimum **5 GitHub commits**


## 📂 Submission Format

- **GitHub Repository Link**
- **Live Website Link (GitHub Pages)**
- **AI Prompt(s)** used for the Placeholder Section (paste as text, or include in a `PROMPTS.md` file in your repo)
- **(Optional) Concept Explanation Video Link**

---

## ❓ Common Questions & Answers

**Can I use different images?**

- Yes, you may use any relevant images (speaker photos, hero background, etc.).

**Can I change the alignment and design freely?**

- No. You must follow the alignment and layout shown in the Figma design.

**Can I change colors?**

- Yes, as long as the colors are relevant and visually consistent with a tech-conference theme.

**Do I need to make the page pixel-perfect?**

- No. You can use your own margin and padding while following the overall structure from Figma.

**Can I use AI to build my sections?**

- Only for the **Placeholder Section** (see below). For every other section, you are expected to write the HTML & CSS yourself. Using AI to generate the Navbar, Banner, Speakers, Pricing, or Footer sections is **not recommended** and may cost marks during evaluation.

**Is the explanation video mandatory?**
- No, not for this assignment. It's optional and won't be graded, but it's a good habit to build early since it will be mandatory starting next assignment.

---
---

## ❓ Common Issues You May Face and Quick Solutions

**GitHub Pages showing 404 / site not loading?**
- Your main HTML file **must be named `index.html`** (lowercase). GitHub Pages looks for this file by default. Rename it if it's called anything else (e.g. `home.html`, `Index.html`).

**Images or CSS not loading on GitHub Pages?**
- Add `./` before your file paths: `./style.css`, `./images/photo.jpg` instead of `style.css` or `/images/photo.jpg`.
- File names are **case-sensitive** on GitHub Pages (Linux). `Photo.jpg` ≠ `photo.jpg` — make sure casing matches exactly.

**CSS background image not showing?**
- Paths in CSS `background-image: url(...)` are relative to the **CSS file location**, not the HTML file. Use `./images/bg.jpg` or `../images/bg.jpg` depending on your folder structure.

**Site not updating after pushing to GitHub?**
- Wait 1–2 minutes, then hard refresh: `Ctrl + Shift + R` (Windows) / `Cmd + Shift + R` (Mac) to bypass browser cache.

**CSS changes not reflecting locally?**
- Hard refresh: `Ctrl + Shift + R`. Your browser is likely showing a cached version.

**Commit count is less than 5?**
- Commit after completing each section (Navbar → Banner → Speakers → Pricing → Footer). Don't push everything in one final commit.

**Fonts or icons not loading?**
- If using Google Fonts or icon libraries via `<link>`, they require an internet connection. They will work fine on GitHub Pages.

**Page looks fine locally but broken on GitHub Pages?**
- Check all file/folder names for typos and casing mismatches. Windows ignores case, but GitHub Pages (Linux) does not.
