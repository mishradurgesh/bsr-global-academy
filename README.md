# BSR Global Education Academy — Website

Premium static website for BSR Global Education Academy, hosted on GitHub Pages.
Live site: [mishradurgesh.github.io/bsr-global-academy](https://mishradurgesh.github.io/bsr-global-academy/)

---

## File Structure

```
bsr-global-academy/
├── index.html                  ← Homepage
├── about.html                  ← About Us
├── subjects.html               ← Subjects (tabbed explorer)
├── curriculum.html             ← Curricula supported (region tabs)
├── teachers.html               ← Our Expert Teachers (6 profiles)
├── reviews.html                ← Parent & Student Reviews
├── demo.html                   ← Book Free Demo (enhanced form)
├── style.css                   ← Shared stylesheet (all pages)
├── logo.jpg                    ← BSR logo
├── sitemap.xml                 ← SEO sitemap
├── robots.txt                  ← SEO robots file
└── reviews-screenshots/        ← Real review screenshot images
    ├── review-gurcharanjit-google.jpeg
    ├── review-rajani-singh-google.jpeg
    ├── review-zayan-ahmed-google.jpeg
    ├── review-siya-mahajan-google.jpeg
    ├── review-shweta-mishra-google.jpeg
    ├── review-ansar-mohammed-google.jpeg
    ├── review-madhavi-chat-full.jpeg
    ├── review-steve-french-whatsapp.jpeg
    ├── review-birgit-whatsapp.jpeg
    └── review-rajani-aura-whatsapp2.jpeg
```

---

## GitHub Pages Deployment

1. Create/use the repository `mishradurgesh/bsr-global-academy`
2. Upload **all files and folders** (including `reviews-screenshots/`) to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch, `/ (root)`
5. Click **Save** — site goes live at:
   `https://mishradurgesh.github.io/bsr-global-academy/`

> The `reviews-screenshots/` folder must be uploaded for review images to display.

---

## Pages & Features

| Page | Key Sections |
|------|-------------|
| `index.html` | Hero, Ticker, Why Parents Choose BSR, Animated Impact Counters, Countries, Faculty Preview, Reviews Preview, Testimonials Carousel, Follow Us, FAQ (7 questions), CTA, Footer |
| `about.html` | Mission, Stats Strip, Our Values, Expert Tutors |
| `subjects.html` | 7-tab subject explorer (Maths, Sciences, English, CS, Languages, Communication, Exam Prep) |
| `curriculum.html` | Curriculum cards with region tabs (International, South Asia, UK, USA, Australia) |
| `teachers.html` | 6 full teacher profiles with credentials, tags, Faculty Promise section |
| `reviews.html` | 10 real reviews (Google + WhatsApp), filterable by subject, screenshot gallery with lightbox |
| `demo.html` | Enhanced booking form — Student Name, Parent Name, School, Phone, WhatsApp, Email, Grade, Curriculum, Subject, Date/Time preference, Country; submits via WhatsApp |

---

## Social Media Links

| Platform | URL |
|----------|-----|
| YouTube | https://www.youtube.com/@BSRGlobalEducation |
| Instagram | https://www.instagram.com/bsrglobalacademy?utm_source=qr&igsh=ejBpeWNtMnh1djho |
| Facebook | https://www.facebook.com/profile.php?id=61587389646397 |
| WhatsApp | +91 8318830632 |

WhatsApp CTA URL used sitewide:
```
https://wa.me/918318830632?text=Hello%20BSR%20Global%20Academy%2C%20I%20would%20like%20to%20know%20more%20about%20your%20tutoring%20programs%20and%20free%20demo%20classes.
```

---

## Contact Details

- WhatsApp: +91 8318830632
- Email: bsrglobalacademy@gmail.com

---

## Connecting the Booking Form

The demo form currently validates fields then opens a pre-filled WhatsApp message.
To also receive email notifications from form submissions, use one of:

**Option A — Formspree** (recommended, free):
1. Sign up at [formspree.io](https://formspree.io)
2. Create a form, get your endpoint URL (e.g. `https://formspree.io/f/xabcdefg`)
3. In `demo.html`, add `action="https://formspree.io/f/YOUR_ID" method="POST"` to the `<form>` tag
4. Give each input a `name` attribute

**Option B — EmailJS** (no backend):
1. Sign up at [emailjs.com](https://www.emailjs.com)
2. Connect your Gmail account
3. Replace the `submitForm()` JS function with their SDK call

---

## Customisation Notes

- **Logo**: Replace `logo.jpg` — keep the same filename (referenced across all pages)
- **Tutor profiles**: Edit the teacher cards in `teachers.html`
- **Reviews**: Add new review cards in `reviews.html` using the existing card structure; add screenshots to `reviews-screenshots/` and register them in the lightbox array at the bottom of `reviews.html`
- **FAQ**: Edit the `.faq-item` blocks in `index.html`
- **Impact counters**: Change `data-target` values on `.impact-number` elements in `index.html`
- **Colours**: CSS custom properties are at the top of `style.css` — edit `--navy`, `--royal`, `--gold` etc.
