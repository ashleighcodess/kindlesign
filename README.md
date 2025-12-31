# Kindle Sign Company Website

Custom website for Kindle Sign Company, a family-owned sign business in Langhorne, PA serving Bucks County, Philadelphia, and the greater Delaware Valley.

## 🚀 Quick Start

### Option 1: Netlify (Recommended)
1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) → Sign in with GitHub
3. Click "Add new site" → "Import an existing project"
4. Select this repository
5. Deploy settings: Leave defaults (no build command needed)
6. Click "Deploy site"

Your site will be live at `https://[random-name].netlify.app`

### Option 2: Manual Upload
Upload contents to any web host via FTP/cPanel.

## 📁 Project Structure

```
kindlesign/
├── index.html              # Homepage
├── l__3_.jpg               # Logo
├── services/
│   ├── channel-letters.html
│   ├── monument-signs.html
│   ├── pylon-signs.html    # Enhanced SEO version
│   ├── led-signs.html
│   ├── awnings-canopies.html
│   └── vehicle-wraps.html
├── README.md
├── LICENSE
└── .gitignore
```

## ✨ Features

- **Responsive Design** - Mobile-first, works on all devices
- **SEO Optimized** - Schema markup, meta tags, semantic HTML
- **Fast Loading** - No build process, pure HTML/CSS/JS
- **Accessible** - Proper heading hierarchy, alt text ready

## 🔧 Customization

### Update Contact Info
Search and replace across all files:
- Phone: `866-358-9892`
- Email: `sales@kindlesign.com`
- Address: `116 N Bellevue Ave Suite 306, Langhorne PA 19047`

### Update Logo
Replace `l__3_.jpg` with your logo file, or update all `<img>` src references.

### Add New Pages
1. Copy any service page as a template
2. Update content, meta tags, and canonical URL
3. Add link to navigation in all pages

## 🌐 Custom Domain Setup (Netlify)

1. Go to Site settings → Domain management
2. Click "Add custom domain"
3. Enter your domain (e.g., `kindlesign.com`)
4. Update DNS at your registrar:
   - **Option A**: Point nameservers to Netlify
   - **Option B**: Add CNAME record pointing to your Netlify URL

## 📈 SEO Checklist

- [x] Title tags optimized
- [x] Meta descriptions (155-160 chars)
- [x] Schema.org structured data
- [x] Canonical URLs
- [x] Internal linking
- [x] Mobile responsive
- [ ] Submit sitemap to Google Search Console
- [ ] Set up Google Analytics
- [ ] Add real images with alt text

## 🛠 Future Enhancements

- Add sitemap.xml
- Add robots.txt
- Create location pages (Bucks County, Philadelphia, etc.)
- Add portfolio/gallery with real project images
- Integrate contact form with Netlify Forms or Formspree

## 📞 Support

For website updates or questions, contact your developer.

---

Built with ❤️ for Kindle Sign Company
