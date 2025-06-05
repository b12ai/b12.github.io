# b12.github.io

Landing page for [b-12 AI lab automation](https://b-12.ai).

## Files

- `index.html`: Landing page with ASCII-art header and company overview sections (Who are we, problem, solution, benefits).
- `contact.html`: Contact info (team bios, call to action).
- `styles.css`: External stylesheet with theme variables and layout styles.
- `CNAME`: Custom domain configuration (b-12.ai).
- `README.md`: This file.

## Customization & Suggestions

- **Typography & colors**: tweak CSS variables in `styles.css` to match your brand palette and fonts.
- **Header & navigation**: a sticky header with 'About' anchor link and 'Contact' page link has been added; customize link styles or add more sections.
- **Logo & imagery**: replace the ASCII art `<pre>` block with an SVG or image (`<img>`) for a clean logo.
- **SEO & social meta tags**: enhance the `<head>` in `index.html` with Open Graph or Twitter Card meta tags.
- **Animations & interactivity**: introduce CSS transitions or simple JavaScript to reveal sections on scroll.
- **Performance**: optimize assets (minify CSS, compress images) and consider hosting fonts locally. If using a scroll‑scrubbed background video, re‑encode it with a shorter keyframe interval for smoother seeking (e.g. `ffmpeg -i b12.mp4 -c:v libx264 -preset veryfast -g 30 -crf 20 b12-scrub.mp4`).
