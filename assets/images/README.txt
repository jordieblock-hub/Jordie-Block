IMAGE ASSETS — PLACEMENT GUIDE
================================

1. HEADSHOT (About section)
   File name: jordie-headshot.jpg  (or .webp)
   Recommended size: 800 × 1000 px  |  Format: JPG or WebP
   Location: assets/images/jordie-headshot.jpg

   In index.html, find the About section and replace:
     <div class="about-img-placeholder"> ... </div>
   With:
     <img src="assets/images/jordie-headshot.jpg" alt="Jordie Block" />

2. PROJECT IMAGES (Work section)
   Replace the .card-bg <div> in each project card with an <img> tag.
   Recommended size: 800 × 1000 px  |  Format: JPG or WebP

   Example — replace:
     <div class="card-bg" style="background:..."></div>
   With:
     <img src="assets/images/projects/cboe-cover.jpg" alt="Cboe Global Markets project" class="card-bg-img" />

   And add to style.css:
     .card-bg-img { position:absolute; inset:0; width:100%; height:100%; object-fit:cover; }

3. RESUME PDF
   File: assets/resume/Jordie-Block-Resume.pdf
   (The nav "Resume ↗" button links to this path.)
