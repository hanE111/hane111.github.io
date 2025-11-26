# Personal Website - GitHub Pages

A professional personal website showcasing your research, projects, and academic profile.

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

1. **Create a new GitHub repository:**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `your-username.github.io` (replace `your-username` with your GitHub username)
   - Make it public

2. **Upload these files:**
   - Upload `index.html`, `style.css`, and `script.js` to the repository
   - Add your profile photo as `profile-photo.jpg` (or update the filename in index.html)

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Under "Source", select the main branch
   - Save and wait a few minutes

4. **Visit your site:**
   - Your website will be live at `https://your-username.github.io`

### Option 2: Custom Domain

If you have a custom domain:
1. Follow the steps above
2. In Settings → Pages, add your custom domain
3. Configure DNS settings with your domain provider

## ✏️ Customization Guide

### 1. Update Personal Information

**In `index.html`, replace:**

- **Name:** Search for "Han" and replace with your name
- **Email:** Replace `your.email@example.com` with your actual email
- **LinkedIn:** Replace `https://linkedin.com/in/your-profile` with your LinkedIn URL
- **GitHub:** Replace `https://github.com/your-username` with your GitHub profile URL

### 2. Add Your Profile Photo

- Add your photo to the repository as `profile-photo.jpg`
- Or update line 38 in `index.html` to match your photo filename:
  ```html
  <img src="your-photo-name.jpg" alt="Your name">
  ```

### 3. Customize Content

**About Section (lines 51-69):**
- Update the paragraphs with your background and interests
- Modify the motto quote to reflect your personal philosophy

**Research Interests (lines 74-99):**
- Update the four research cards with your specific areas
- Change icons by using different Font Awesome classes

**Publications (lines 105-130):**
- Add your publications with proper citations
- Update authors, titles, and descriptions
- Add links to papers if available

**Projects (lines 136-179):**
- Update project descriptions
- Change technology tags to match your tech stack
- Add GitHub links if you want

### 4. Change Colors

In `style.css`, modify the `:root` section (lines 2-12):

```css
:root {
    --primary-color: #2563eb;     /* Main brand color */
    --secondary-color: #1e40af;   /* Hover states */
    --accent-color: #3b82f6;      /* Tags and highlights */
}
```

### 5. Modify Gradient

Change the hero gradient in `style.css` (line 82):

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

[Try gradient generator](https://cssgradient.io/)

## 📱 Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Fade-in animations on scroll
- ✅ Scroll-to-top button
- ✅ Professional styling
- ✅ Fast loading
- ✅ SEO-friendly structure
- ✅ Social media integration

## 🎨 Icons

This site uses [Font Awesome](https://fontawesome.com/icons) for icons. To change icons:

1. Visit [Font Awesome Icons](https://fontawesome.com/icons)
2. Search for an icon
3. Copy the HTML code (e.g., `<i class="fas fa-brain"></i>`)
4. Replace the icon in your HTML

Common icons:
- `fa-capsules` - Medicine/drugs
- `fa-dna` - Genetics
- `fa-brain` - Neuroscience
- `fa-project-diagram` - Networks/graphs
- `fa-microscope` - Research
- `fa-chart-line` - Data/analytics

## 📂 File Structure

```
your-username.github.io/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
├── profile-photo.jpg   # Your profile picture
└── README.md          # This file
```

## 🔧 Advanced Customization

### Add a Blog Section

Add this to your `index.html` before the contact section:

```html
<section id="blog" class="blog">
    <div class="container">
        <h2>Blog</h2>
        <div class="blog-grid">
            <!-- Add blog posts here -->
        </div>
    </div>
</section>
```

### Add Google Analytics

Add before the closing `</head>` tag in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

### Add PDF Resume Download

Add this button in the hero section:

```html
<a href="your-resume.pdf" download class="btn-download">
    <i class="fas fa-download"></i> Download CV
</a>
```

## 🐛 Troubleshooting

**Images not showing:**
- Make sure the image filename matches exactly (case-sensitive)
- Check that the image is in the same directory as index.html

**Site not updating:**
- GitHub Pages can take 5-10 minutes to update
- Try clearing your browser cache
- Check repository Settings → Pages for error messages

**Links not working:**
- Make sure to use the full URL with `https://`
- Test links before deploying

## 📞 Support

If you need help:
1. Check [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Review common issues on [Stack Overflow](https://stackoverflow.com/questions/tagged/github-pages)

## 📝 License

This template is free to use and modify for personal or commercial purposes.

## 🎉 Tips for Success

1. **Keep content updated:** Regular updates show you're active
2. **Use high-quality photos:** Professional headshot works best
3. **Link to your work:** Add GitHub repos, papers, etc.
4. **SEO matters:** Use descriptive text and proper headings
5. **Mobile-first:** Most visitors will view on mobile
6. **Fast loading:** Optimize images (use tools like TinyPNG)
7. **Get feedback:** Ask colleagues to review before going live

## 🚀 Next Steps

1. ✅ Deploy the website
2. ✅ Add your content and photo
3. ✅ Test on mobile devices
4. ✅ Share your link on LinkedIn
5. ✅ Add the link to your email signature
6. ✅ Include it in PhD applications
7. ✅ Update regularly with new projects/publications

---

**Good luck with your website and PhD applications!** 🎓