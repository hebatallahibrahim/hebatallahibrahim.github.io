# Hebatallah Ibrahim — Portfolio

Full-Stack Developer & Team Leader — PHP / Laravel · Node.js · React · Flutter.

**Live site:** https://hebatallahibrahim.github.io

## What's inside
- **Featured systems:** CRS for Baitulmaal (video), BlueField ERP (video), FleetSpeed dispatch platform (dashboard, rider portal, mobile app)
- **More systems:** Water-Well Drilling Management, Faculty Affairs System (Alexandria University)
- **Websites:** Impact Associates, Handeal Groups, BlueField, Salam Charity USA & Canada, Biz Center, Vitalé Nutrition, Sheno Furniture, FleetSpeed
- Experience, skills, education and a downloadable CV

## Structure
```
index.html                     single-page site (HTML + CSS, no build step)
assets/shots/*.webp            website screenshots (1200px wide)
assets/videos/*.mp4 / *.webp   demo videos and their poster frames
assets/Hebatallah-Ibrahim-CV.pdf
```

## Adding a project
1. Save a screenshot as `assets/shots/<name>.webp` (about 1200×750).
2. Copy one `<article class="card">` block in `index.html` and change the image, title, text and link.
3. Keep videos under 50 MB (GitHub rejects files over 100 MB). To compress:
   `ffmpeg -i input.mp4 -c:v libx264 -preset slow -crf 27 -c:a aac -b:a 96k -movflags +faststart output.mp4`
