IMAGES TO ADD
==============

Drop image files into this folder, then update index.html to reference them.

1. PORTRAIT OF ERIM (used in #about section)
   - Filename suggestion: erim-portrait.jpg
   - Recommended size: ~800 x 1000 px (4:5 ratio), under 200 KB
   - In index.html, find:    <!-- Replace with: <img src="images/erim-portrait.jpg" ... -->
   - Replace the placeholder div content with: <img src="images/erim-portrait.jpg" alt="Erim Kaur, Public Speaking Coach">

2. BRAND LOGOS (used in "As Featured In" strip)
   Save each as a transparent-background PNG or SVG, ~120 px wide:
     - goldman-sachs.png
     - ted-talks.png
     - natwest.png
     - telegraph.png
     - sky.png
     - boots.png
     - breakout-beauty.png
   Then in index.html, replace each <span class="brand-logo">...</span> with:
     <span class="brand-logo"><img src="images/goldman-sachs.png" alt="Goldman Sachs"></span>

3. OPEN GRAPH IMAGE (used when the site is shared on social)
   - Filename: og-image.jpg
   - Size: 1200 x 630 px
   - Sat's portrait + a short tagline works best
   - This is referenced in the <meta property="og:image"> tag in index.html

4. EBOOK COVER (optional - currently uses a styled text card)
   - If you have a real cover, save as ebook-cover.jpg (3:4 ratio)
   - Replace the .ebook-cover div content in index.html with: <img src="images/ebook-cover.jpg" alt="The Confident Voice Playbook">

5. BLOG POST HERO IMAGES (optional)
   - The blog cards currently use coloured gradients with category text.
   - To swap in real images, save as 1600 x 900 px JPGs and replace the .card-thumb div in index.html / blog/index.html.

When ready, commit and push to GitHub. GitHub Pages will rebuild within a minute or two.
