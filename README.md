# Magdalena Motor Inn Website

Simple, fast static website for magdalenamotorinn.com

## File Structure
```
/
├── index.html          # Main page
├── styles.css          # All styling
├── images/             # Create this folder for photos
└── README.md          # This file
```

## Adding Photos

1. Create an `images` folder in this directory
2. Add your photos with these names (or update the HTML to match your filenames):
   - `hero.jpg` - Main header image (landscape, 1920x1080 recommended)
   - `room1.jpg`, `room2.jpg` - Room photos
   - `exterior.jpg` - Building exterior
   - `area.jpg` - Local scenery

3. In `index.html`, replace placeholder divs with:
   ```html
   <img src="images/hero.jpg" alt="Description">
   ```

## Adding Max Reservations Booking Widget

1. Get your embed code from Max Reservations
2. Open `index.html`
3. Find the section marked `<!-- Max Reservations embed code goes here -->`
4. Replace the entire `<div class="booking-placeholder">` section with your embed code

## Deploying to Cloudflare Pages

1. Go to pages.cloudflare.com
2. Sign up/login
3. Click "Create a project" → "Upload assets"
4. Drag and drop ALL files (index.html, styles.css, images folder if created)
5. Click "Deploy site"
6. Once deployed, go to "Custom domains" and add magdalenamotorinn.com

## Pointing Your GoDaddy Domain

1. In Cloudflare Pages, get your site's nameservers
2. Go to GoDaddy → Domains → magdalenamotorinn.com → Manage DNS
3. Update nameservers to Cloudflare's (they'll provide these)
4. Wait 10-60 minutes for DNS propagation

## Updating the Site Later

Just re-upload files to Cloudflare Pages. Dead simple.

## Contact Info in Site
- Phone: (575) 517-7847
- Email: info@magdalenamotorinn.com
