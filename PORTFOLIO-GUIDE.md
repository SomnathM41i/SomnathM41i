# Portfolio Fix Checklist — Somnath Mali

Apply these to `https://somnathm41i-portfolio.vercel.app/`. Each item is quick; do them in any order.

## 1. Facts & dates (do first)

| Item | Current | Fix |
|---|---|---|
| Footer copyright | `© 2025` | `© 2026` |
| Experience years | `2+yrs experience` (stats bar) | `3+ yrs experience` |
| Current role start | `June 2023 – Present` | Keep (correct) |
| Location | Mixed: `Karagani, Sangli` (identity card) vs `Mumbai / Remote` (hero) | Pick **one** primary: `Mumbai / Remote (based in Maharashtra)` and use it in hero + contact + footer |
| Title | Multiple variants | Use **`Full-Stack Developer • PHP/Laravel • Python/FastAPI • React`** everywhere (matches README) |

## 2. Broken / dead links

- **Lotus Brand Bazaar → "Live" button** currently points to `#`. Options:
  - Link it to the real production URL if it's public, or
  - Relabel the button to `Case Study` and keep the GitHub link, or
  - Drop the "Live" badge so it doesn't look broken/overclaimed.
- Audit every `href` — the contact icons in the footer render as empty links (`[](github)…`). Add visible text and `aria-label` so they show icons correctly.

## 3. Proof / credibility

- Add one **hard number** with context. Examples using real data:
  - "Fully delivered a business management app in a **10-week MVP cycle**."
  - "Integrated **PhonePe + Razorpay** payments with webhook reconciliation in production."
  - "25 matrimonial platforms, each serving **10K–50K users**."
- Add a short **testimonial** from the Gold Loan client (even 2 lines) if they'll allow it — this is the single biggest trust booster.
- Replace generic GitHub-profile links on each project card with **direct repo links** where one exists:
  - myvivahai → `https://github.com/SomnathM41i/myvivahai`
  - Matrimony_Platform → `https://github.com/SomnathM41i/Matrimony_Platform`

## 4. Resume

- Export your resume as `somnath-mali-resume.pdf`.
- Host it (same Vercel project — drop it in `public/`) and add a **"Download Resume"** button in the hero and identity card.
- Add the same link to your GitHub README contact row (`https://somnathm41i-portfolio.vercel.app/somnath-mali-resume.pdf`).

## 5. SEO / share preview (LinkedIn & Google)

- Set `<title>`: `Somnath Mali — Full-Stack Developer | PHP, Laravel, FastAPI, React`
- Add meta description (1–2 lines, ~155 chars).
- Add an **Open Graph image** (1200×630 PNG) with your name + title so the link preview looks professional when shared on LinkedIn/WhatsApp.

## 6. Content polish

- Hero `/ls ./skills/` block: drop anything you wouldn't claim in an interview (e.g., only list tools you've used in production).
- Footer line *"Built with PHP, regret, and a dream…"* — it's charming; keep it, but consider "…and a lot of late-night debugging" instead of "regret" for recruiters.
- Blog link (`emperorofbattle.blogspot.com`) — the name reads casual/gaming. Either rename the blog to something like `somnathmali.dev/blog` or put it under "Extras" instead of the top nav.