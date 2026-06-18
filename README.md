# BSR Global Education Academy — Website

## 📁 File Structure
```
bsr-website/
├── index.html        ← Homepage (hero, testimonials, FAQ, CTA)
├── about.html        ← About Us page
├── subjects.html     ← Subjects with interactive tabs
├── curriculum.html   ← Curriculum guide with region tabs
├── demo.html         ← Demo booking form
├── style.css         ← Shared styles (import in all pages)
└── logo.jpg          ← BSR logo image
```

## 🚀 GitHub Pages Deployment

1. Create a new GitHub repository (e.g. `bsr-global-academy`)
2. Upload all files in this folder to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch, `/ (root)`
5. Click **Save** — your site will be live at:
   `https://yourusername.github.io/bsr-global-academy/`

## ✅ Features Included
- ✅ BSR logo in navigation bar
- ✅ Mobile-first responsive design
- ✅ WhatsApp floating button (all pages)
- ✅ Testimonials carousel (homepage)
- ✅ FAQ accordion (homepage)
- ✅ Demo booking form with validation
- ✅ Interactive subject tabs
- ✅ Curriculum region tabs
- ✅ SEO meta tags (all pages)
- ✅ Country ticker animation
- ✅ Footer with social media links

## 📞 Contact Details (in site)
- WhatsApp: +91 8318830632
- Email: bsrglobalacademy@gmail.com

## 🔧 Customisation Tips
- **Social links**: Search for `href="#"` in footers and replace with real URLs
- **Form submission**: In `demo.html`, replace the `submitForm()` function with Formspree (free) or EmailJS
- **Testimonials**: Edit the `.testimonial-card` blocks in `index.html`
- **Logo**: Replace `logo.jpg` with any updated logo file (keep same filename)

## 📧 Connecting the Booking Form (Free Options)
**Option A — Formspree** (recommended):
1. Sign up at formspree.io
2. Create a form, get your endpoint URL
3. Add `action="https://formspree.io/f/YOUR_ID"` to the form tag

**Option B — EmailJS**:
1. Sign up at emailjs.com
2. Connect your Gmail account
3. Replace the `submitForm()` JS function with their SDK

