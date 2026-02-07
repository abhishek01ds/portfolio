# Abhishek Kumar - Portfolio Website

A clean, professional, and responsive portfolio website for showcasing AI & Data Science projects and skills.

## 🌟 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Easy to Update** - Modular code structure for easy content updates
- **Recruiter-Friendly** - Clear sections for education, skills, projects, and contact
- **Fast Loading** - Optimized performance with minimal dependencies
- **Cross-Browser Compatible** - Works on all modern browsers

## 📁 File Structure

```
portfolio/
│
├── index.html          # Main HTML file with website structure
├── style.css           # All styling and responsive design
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── resume.pdf          # Your resume (add this file)
```

## 🚀 Quick Start

### Option 1: Local Setup

1. **Download the files**
   - Save `index.html`, `style.css`, and `script.js` in a folder

2. **Add your resume**
   - Save your resume as `resume.pdf` in the same folder
   - Update line 369 in `index.html`:
     ```html
     <a href="resume.pdf" class="btn btn-primary" id="download-resume">
     ```

3. **Open in browser**
   - Double-click `index.html` to open in your default browser
   - Or right-click → Open With → Choose your browser

### Option 2: Deploy on GitHub Pages (Recommended)

1. **Create a GitHub repository**
   ```bash
   # Create a new repository on GitHub named: your-username.github.io
   # Or any name like: portfolio
   ```

2. **Upload files**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save

4. **Access your site**
   - Your site will be live at: `https://your-username.github.io/your-repo-name/`

### Option 3: Deploy on Netlify

1. **Drag and Drop**
   - Go to [Netlify](https://www.netlify.com/)
   - Drag your folder to the deploy area
   - Done! Your site is live

### Option 4: Deploy on Vercel

1. **Deploy with Vercel CLI**
   ```bash
   npm i -g vercel
   vercel
   ```

2. **Or use Vercel Website**
   - Go to [Vercel](https://vercel.com/)
   - Import your GitHub repository
   - Deploy automatically

## 📝 How to Update Your Portfolio

### Adding New Projects

The project section is designed to be modular and easy to update. Here's how:

1. **Open `index.html`**

2. **Find the Projects Section** (around line 230)

3. **Copy this template:**

```html
<!-- Project X -->
<div class="project-card">
    <div class="project-number">04</div>
    <h3>Your Project Title Here</h3>
    <p>
        Describe your project in 2-3 sentences. Explain what problem it solves,
        what technologies you used, and what you learned from it.
    </p>
    <div class="tech-stack">
        <span>Technology 1</span>
        <span>Technology 2</span>
        <span>Technology 3</span>
    </div>
    <div class="project-results">
        <p><strong>Key Results:</strong> Describe the outcomes, metrics, or 
        achievements of your project here.</p>
    </div>
</div>
```

4. **Customize the fields:**
   - Update the project number (01, 02, 03, etc.)
   - Change the title to your project name
   - Write your project description
   - Add/remove technology tags as needed
   - Update the results section

5. **Paste the new project card** inside the `<div class="projects-grid">` section

6. **Save and refresh** your browser to see the changes

### Example: Adding a New Project

```html
<!-- Project 4 - NEW PROJECT -->
<div class="project-card">
    <div class="project-number">04</div>
    <h3>Stock Price Prediction using LSTM</h3>
    <p>
        Developed a time-series forecasting model using Long Short-Term Memory (LSTM) 
        neural networks to predict stock prices. Implemented data preprocessing, feature 
        scaling, and sequential modeling to capture temporal patterns in financial data.
    </p>
    <div class="tech-stack">
        <span>Python</span>
        <span>TensorFlow</span>
        <span>LSTM</span>
        <span>Pandas</span>
        <span>NumPy</span>
    </div>
    <div class="project-results">
        <p><strong>Key Results:</strong> Achieved 85% accuracy in price movement 
        prediction with RMSE of 2.3, demonstrating effective use of deep learning 
        for financial forecasting.</p>
    </div>
</div>
```

### Updating Personal Information

#### Contact Details
Edit lines 365-420 in `index.html`:

```html
<!-- Email -->
<a href="mailto:your-new-email@example.com">your-new-email@example.com</a>

<!-- Phone -->
<a href="tel:+919876543210">+91 9876543210</a>

<!-- Social Links -->
<a href="https://linkedin.com/in/your-profile">LinkedIn</a>
<a href="https://github.com/your-username">GitHub</a>
```

#### Skills
Edit lines 186-245 in `index.html`:

```html
<div class="skill-category">
    <h3>Your New Category</h3>
    <div class="skill-tags">
        <span>Skill 1</span>
        <span>Skill 2</span>
        <span>Skill 3</span>
    </div>
</div>
```

#### Education
Edit lines 145-170 in `index.html` to add new degrees or certifications.

### Customizing Colors

Want to change the color scheme? Edit the CSS variables in `style.css` (lines 1-30):

```css
:root {
    --color-accent: #2c5f4f;          /* Main accent color */
    --color-accent-light: #3a7a64;     /* Lighter accent */
    --color-accent-dark: #1e4437;      /* Darker accent */
    /* Change these to your preferred colors */
}
```

**Color Scheme Suggestions:**
- **Blue Professional:** `#1e3a8a`, `#3b82f6`, `#1e40af`
- **Purple Modern:** `#6b21a8`, `#a855f7`, `#581c87`
- **Red Bold:** `#991b1b`, `#dc2626`, `#7f1d1d`
- **Teal Fresh:** `#115e59`, `#14b8a6`, `#0f766e`

## 📱 Responsive Breakpoints

The website is fully responsive with these breakpoints:
- **Desktop:** 1200px and above
- **Tablet:** 768px to 1199px
- **Mobile:** Below 768px

## 🎨 Design Features

- **Typography:** Crimson Pro (display) + DM Sans (body)
- **Animations:** Smooth fade-in effects on scroll
- **Color Palette:** Professional earth tones with green accents
- **Layout:** CSS Grid and Flexbox for responsive design
- **Accessibility:** Semantic HTML and proper contrast ratios

## 🔧 Customization Tips

### Adding a Blog Section

Add this HTML after the Projects section:

```html
<section id="blog" class="section blog">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <div class="blog-grid">
            <!-- Add blog post cards here -->
        </div>
    </div>
</section>
```

### Adding Certifications

Add this after Education section:

```html
<section id="certifications" class="section certifications">
    <div class="container">
        <h2 class="section-title">Certifications</h2>
        <div class="cert-grid">
            <!-- Add certification cards -->
        </div>
    </div>
</section>
```

### Adding a Contact Form

Replace the contact section with a form:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message</button>
</form>
```

Get a free form endpoint from [Formspree](https://formspree.io/)

## 🐛 Troubleshooting

### Resume download not working
1. Make sure `resume.pdf` is in the same folder as `index.html`
2. Update the file path in line 369 of `index.html`
3. Check browser console for errors (F12)

### Navigation not scrolling smoothly
- Make sure `script.js` is properly linked
- Check browser console for JavaScript errors

### Mobile menu not working
- Verify the hamburger menu JavaScript is loaded
- Check if viewport meta tag is present in HTML

### Styles not loading
- Verify `style.css` is in the same directory
- Check the link tag in HTML header
- Clear browser cache (Ctrl+F5)

## 📊 SEO Optimization (Optional)

Add these meta tags to `<head>` in `index.html`:

```html
<meta name="description" content="Abhishek Kumar - AI & Data Science Portfolio showcasing machine learning projects, deep learning models, and data analytics work">
<meta name="keywords" content="AI, Machine Learning, Data Science, Deep Learning, Python, Portfolio">
<meta name="author" content="Abhishek Kumar">
<meta property="og:title" content="Abhishek Kumar | AI & Data Science Portfolio">
<meta property="og:description" content="Portfolio showcasing AI and Data Science projects">
<meta property="og:image" content="your-preview-image.jpg">
<meta property="og:url" content="https://your-website-url.com">
```

## 📞 Support

If you need help or have questions:
- Email: akchapra8581@gmail.com
- LinkedIn: [abhishek-kumar-ai-ds](https://linkedin.com/in/abhishek-kumar-ai-ds)
- GitHub: [abhishek-ai-ds](https://github.com/abhishek-ai-ds)

## 📄 License

This portfolio template is free to use for personal purposes. Feel free to customize it for your own portfolio!

## 🙏 Credits

Designed and developed by Abhishek Kumar
- Fonts: Google Fonts (Crimson Pro, DM Sans)
- Icons: Lucide Icons (inline SVG)

---

**Last Updated:** February 2025

**Version:** 1.0.0

Good luck with your campus placements! 🚀
