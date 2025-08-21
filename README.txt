# SmartFlow Bottle — One-page Site
Built 2025-08-21

## Files
- index.html
- styles.css
- script.js
- /assets (SVG images & favicon)

## Free Hosting (pick one)
1) **Netlify**
   - Drag-and-drop the folder into Netlify.
   - Forms will work via Netlify (`data-netlify="true"` on the form).
2) **GitHub Pages**
   - Push these files to a repo and enable Pages on `main` branch root.
3) **InfinityFree / cPanel**
   - Upload files into `htdocs` for `smartflowbottle.in`.

## WordPress Migration (free)
- Install WordPress on your hosting (InfinityFree -> Softaculous).
- Install the free theme **Blocksy** or **Astra**.
- Install **Elementor (free)**.
- Create a new page "Home".
- Rebuild sections using Elementor:
  - Hero (Heading + Text + 2 Buttons + Image)
  - Logos (4 columns)
  - Features (6 cards)
  - Tech (2 columns + bullet list + badges)
  - Reviews (3 quotes)
  - FAQ (3 toggles/accordions)
  - Contact/Pre-order (2 columns + form)
- Copy wording from index.html as needed.
- Set your new page as the Homepage (Settings -> Reading).

## Custom Domain
- Point `smartflowbottle.in` A record to hosting IP, or set Netlify nameservers.
- Add `hello@smartflowbottle.in` email via your provider.

## Edit
- Colors & content: edit `styles.css` and `index.html`.
- JS only handles smooth scroll and footer year.
