# Paste into Lovable (after repo is public on GitHub)

Replace `helloAbhishekJha` if your GitHub username differs.

```
Use these public image URLs only (constants file pattern). Do not use Unsplash.

const BASE = "https://raw.githubusercontent.com/helloAbhishekJha/halfpastimages/main/assets";

Create src/lib/halfPastImages.ts exporting:
- marco: BASE + "/half-past-photo-05-marco-host.jpg"
- interior: BASE + "/half-past-photo-02-interior-wide.jpg"
- exterior: BASE + "/half-past-photo-01-exterior.jpg"
- bookBg: BASE + "/section-book-mobile.jpg"
- confirmBg: BASE + "/section-confirm-mobile.jpg"
- deskBg: BASE + "/section-desk-desktop.jpg"
- around1: BASE + "/around-01-depasquale-fountain.jpg"
- around2: BASE + "/around-02-atwells-evening.jpg"
- around3: BASE + "/around-03-river-walk.jpg"
- plating: BASE + "/half-past-photo-03-chef-plating.jpg"

Import everywhere. /more mosaic uses marco, interior, around1-3.
```

Full list: see README.md or `lovable-images.ts`.
