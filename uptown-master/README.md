# Uptown Real Estate Website

A professional, responsive real estate website built with Bootstrap 4 and modern web technologies.

## 📋 Project Structure

```
uptown-master/
├── index.html                 # Homepage
├── about.html                 # About page
├── agent.html                 # Agents listing
├── services.html              # Services page
├── properties.html            # Properties listing
├── properties-single.html     # Single property detail
├── blog.html                  # Blog listing
├── blog-single.html          # Single blog post
├── contact.html               # Contact page
├── vercel.json               # Vercel deployment config
├── .gitignore                # Git ignore rules
├── css/                      # Stylesheets
│   ├── style.css            # Main stylesheet
│   ├── bootstrap.min.css    # Bootstrap framework
│   └── (other CSS files)
├── js/                       # JavaScript files
│   ├── main.js              # Main script
│   ├── bootstrap.min.js     # Bootstrap JS
│   └── (other JS libraries)
├── images/                   # Image assets
├── fonts/                    # Font files
└── scss/                     # SCSS source files
```

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Add Vercel configuration"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Your site will be live!

### Or Deploy via Vercel CLI

```bash
npm i -g vercel
vercel
```

## 📁 File Paths Guide

All file paths are **relative**, which is essential for Vercel deployment:

✅ **CORRECT:**
```html
<link href="css/style.css" rel="stylesheet">
<script src="js/main.js"></script>
<img src="images/property.jpg" alt="Property">
```

❌ **INCORRECT (will not work on Vercel):**
```html
<link href="/css/style.css" rel="stylesheet">
<script src="/js/main.js"></script>
<img src="/images/property.jpg" alt="Property">
```

## 🔍 Vercel Configuration

The `vercel.json` file includes:
- Static file serving for HTML, CSS, JS, fonts, and images
- Cache headers for better performance
- Proper routing for multi-page sites

## 💡 Tips

- All HTML pages are fully responsive
- Bootstrap 4 framework for consistent styling
- Real content and customer testimonials
- Professional agent information
- SEO-friendly structure

## 📧 Contact

For inquiries, contact: hello@uptownrealestate.com
Phone: (555) 123-4567

---

**Last Updated:** January 29, 2026
