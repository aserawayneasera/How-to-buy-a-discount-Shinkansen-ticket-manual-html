# 🚄 Kumamoto ↔ Osaka Shinkansen Guide

An interactive, step-by-step guide to buying discounted Shinkansen tickets between **Kumamoto and Osaka**, built for Kumamoto University (KU) students.

---

## ✨ What It Does

This guide walks you through the ticket-buying process with branching questions and clear instructions, so you always end up on the right path for your situation. It covers two main routes:

1. **App-based booking** — using the JR Kyushu App or Smart EX (fast, card-required)
2. **Student Discount Certificate (学割証)** — applying for a KU student certificate and buying at the ticket office (cheapest option)

### Scenes covered

| # | Scene |
|---|-------|
| 1 | Title screen |
| 2 | Do you have a credit/debit card? |
| 3 | About the two apps (JR Kyushu / Smart EX) |
| 4 | Japanese ability check |
| 5 | No Japanese — your two options |
| 6 | JR Kyushu App — book early! |
| 7–9 | JR Kyushu App — collect your ticket (steps 1–3) |
| 10 | Smart EX — how to book |
| 11 | Smart EX — boarding |
| 12 | Get help at the JR Kyushu counter |
| 13 | KU Portal login |
| 14 | Student Certificate Issuance System |
| 15 | Paper or PDF? |
| 16 | Apply for your certificate (学割証) |
| 17 | Collect your certificate |
| 18 | Ticket Office (みどりの窓口) |
| 19 | Ticket gate — you're good to go! |
| 20 | Let's go! 🎉 |

---

## 🛠️ Tech Stack

- **React (JSX)** — compiled in-browser via Babel Standalone (no build step needed)
- **Single HTML file** — fully self-contained, no external dependencies beyond CDN-loaded React/Babel
- **localStorage** — saves scene state in the browser
- **Netlify** — deployed via drag-and-drop

---

## 🚀 Using the Guide

Just open the deployed URL. No login or setup required.

**Special URL parameters:**

| Parameter | Effect |
|-----------|--------|
| `?edit=1` | Unlocks **Edit Mode** — lets you modify scene content and download an updated file |
| `?reset=1` | Clears localStorage — use this once after deploying a new version |

---

## 📝 Editing Content

1. Open the guide with `?edit=1` appended to the URL
2. Click the **Edit** button on any scene to modify it
3. When finished, click **📥 Download updated HTML** — this bakes your changes into a new standalone file

---

## 🌐 Deployment (Netlify)

1. Edit content using `?edit=1`
2. Download the updated HTML file
3. Drag and drop the file onto your Netlify **Deploys** page
4. Visit `?reset=1` once to clear any cached localStorage for visitors
5. Share the clean URL with your classmates

---

## 📁 Repository Structure

```
shinkansen_guide.html   ← The entire app (single file)
README.md
```

---

## 📌 Notes

- Maximum **20 student discount certificates** can be issued per academic year
- Certificates must be collected within **7 days** of applying
- The guide targets the **Kumamoto ↔ Osaka** route but the general process applies to other routes too

---

*Built as a class project at Kumamoto University (KU) — Graduate School of Science and Technology.*
