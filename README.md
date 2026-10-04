# Portfolio (Figma "Desktop - 1" recreation)

## Export these from Figma into /assets (PNG, 2x)
| File | Figma node | Notes |
|---|---|---|
| logo.png | image 4 (1049:10073) | 82x82 (done) |
| avatar.png | "Ellipse 1" inside the greeting group (select the circle photo next to "Hi, Swashika here") | 78x78, export as PNG |
| card1.png | Mask group (989:17) | 468x495, includes rounded corners |
| card2.png | Rectangle 3 (949:44) | 468x495, includes rounded corners |
| card3-mockup.png | ios-app-icon-mockup... (989:12) | 482x442 |

Optional: put `Aileron-Regular.woff2` in /fonts (Aileron is not on Google Fonts).
Optional: add `resume.pdf` at the root for the Resume link.

## Deploy on Vercel
1. Push this folder to a GitHub repo.
2. vercel.com > Add New > Project > import the repo.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Deploy.

Or from a terminal in this folder: `npx vercel --prod`
