# Hewitt Lab Website — Image Assets Guide
# Place all custom images in this `public/` folder.
# Reference images in HTML as: src="public/filename.jpg"

## Required Images (Replace Unsplash placeholders)

### Home Page (index.html)
- public/hero-lab.jpg
  Used: Hero section background
  Recommended: Wide lab environment, research equipment, or abstract science image
  Ideal size: 1600 x 900 px minimum | Aspect ratio: 16:9 | Quality: 80%+

- public/group-photo.jpg
  Used: "About the Lab" split section (left image)
  Recommended: Lab group photo or team working in the lab
  Ideal size: 900 x 500 px | Aspect ratio: ~16:9 or 3:2

- public/news-1.jpg
  Used: News card 1 (Publication highlight)
  Recommended: Microscopy image, genomics data visualization, or tissue section
  Ideal size: 600 x 340 px

- public/news-2.jpg
  Used: News card 2 (Software release)
  Recommended: Computational / data science imagery
  Ideal size: 600 x 340 px

- public/news-3.jpg
  Used: News card 3 (Award/grant)
  Recommended: Lab equipment, lung/cardiac imagery, or abstract science
  Ideal size: 600 x 340 px

---

### Research Page (research.html)
- public/research-cardiac.jpg
  Used: Cardiac Genomics research area image
  Recommended: Cardiac tissue histology, cardiomyocyte imaging, heart anatomy
  Ideal size: 800 x 400 px

- public/research-pulmonary.jpg
  Used: Pulmonary Disease research area image
  Recommended: Lung tissue, pulmonary vasculature, or alveolar imagery
  Ideal size: 800 x 400 px

- public/research-computational.jpg
  Used: Computational Methods research area image
  Recommended: Server/HPC cluster, data visualization, coding environment
  Ideal size: 800 x 400 px

- public/research-translational.jpg
  Used: Translational Research area image
  Recommended: Clinical setting, biospecimen processing, patient-care imagery
  Ideal size: 800 x 400 px

---

### Lab Members Page (team.html)
- public/pi-headshot.jpg
  Used: PI profile photo (large)
  Recommended: Professional headshot or portrait
  Ideal size: 300 x 300 px | Format: Square, face centered

- public/member-postdoc-1.jpg
  Used: First postdoc card photo
  Ideal size: 400 x 260 px | Will be cropped top-center

- public/member-postdoc-2.jpg
  Used: Second postdoc card photo
  Ideal size: 400 x 260 px

- public/member-postdoc-3.jpg (optional)
  Used: Third postdoc card photo (currently placeholder emoji)
  Ideal size: 400 x 260 px

- public/member-phd-1.jpg through member-phd-4.jpg (optional)
  Used: PhD student cards (currently placeholder emoji)
  Ideal size: 400 x 260 px

---

## How to Replace Placeholder Images

In each HTML file, look for comments like:
  <!-- PLACEHOLDER: Replace with public/hero-lab.jpg -->

Then change the line below from:
  src="https://images.unsplash.com/..."
To:
  src="public/hero-lab.jpg"

---

## Image Format Guidelines
- Use JPG for photos (smaller file size, good for photography)
- Use PNG for logos or graphics with transparency
- Use WebP if you want better compression and browser compatibility
- Keep hero images under 400 KB; card images under 150 KB
- Run images through https://squoosh.app/ for easy optimization

---

## Logo / Favicon
- public/logo.png        (optional custom logo, currently uses SVG heart icon)
- public/favicon.ico     (browser tab icon, 32x32 or 64x64)
- public/blood-logo.png  (original favicon from the previous site version)
