# 🚀 QUICK START GUIDE

## Get Your Portfolio Live in 5 Minutes!

### Step 1: Download Files ✅
You already have these files:
- ✓ index.html
- ✓ style.css
- ✓ script.js
- ✓ README.md (detailed documentation)

### Step 2: Test Locally (RIGHT NOW!)
1. Put all files in one folder
2. Double-click `index.html`
3. Your portfolio opens in your browser! 🎉

### Step 3: Add Your Resume
1. Save your resume as `resume.pdf`
2. Put it in the same folder as the other files
3. Open `index.html` in a text editor
4. Find line 369 and change:
   ```html
   <a href="#" class="btn btn-primary" id="download-resume">
   ```
   To:
   ```html
   <a href="resume.pdf" class="btn btn-primary" download="Abhishek_Kumar_Resume.pdf">
   ```

### Step 4: Deploy Online (Choose ONE)

#### Option A: GitHub Pages (BEST for developers)
```bash
# 1. Create a new repo on GitHub
# 2. Upload your files
# 3. Go to Settings → Pages
# 4. Enable Pages from main branch
# 5. Done! Your site is at: username.github.io/repo-name
```

#### Option B: Netlify (EASIEST)
1. Go to netlify.com
2. Drag and drop your folder
3. Done! You get a free URL instantly

#### Option C: Vercel
1. Go to vercel.com
2. Import from GitHub or upload files
3. Deploy with one click

---

## 🔥 How to Add New Projects (Copy-Paste Method)

### Step 1: Open index.html in a text editor

### Step 2: Find this section (around line 320):
```html
<div class="projects-grid">
```

### Step 3: Copy this template:
```html
<div class="project-card">
    <div class="project-number">04</div>
    <h3>YOUR PROJECT NAME</h3>
    <p>
        Your project description here. What did you build? 
        What problem does it solve?
    </p>
    <div class="tech-stack">
        <span>Python</span>
        <span>TensorFlow</span>
        <span>Pandas</span>
    </div>
    <div class="project-results">
        <p><strong>Key Results:</strong> Your achievements here.</p>
    </div>
</div>
```

### Step 4: Paste it inside the projects-grid div

### Step 5: Update:
- Project number (01, 02, 03, 04...)
- Project name
- Description
- Technologies (add/remove spans)
- Results

### Step 6: Save and refresh browser!

---

## 💡 Quick Customization

### Change Colors:
Open `style.css`, find line 9:
```css
--color-accent: #2c5f4f;  /* Change this to your favorite color! */
```

Try these:
- Blue: `#1e40af`
- Purple: `#7c3aed`
- Red: `#dc2626`
- Orange: `#ea580c`

### Change Your Info:
Just search in `index.html` for your current info and replace it!

---

## 📞 Need Help?

**Common Issues:**

1. **Resume not downloading?**
   - Make sure resume.pdf is in the same folder
   - Update the link in index.html

2. **Mobile menu not working?**
   - Make sure script.js is in the same folder
   - Check if all three files are together

3. **Styles look weird?**
   - Press Ctrl+F5 to hard refresh
   - Make sure style.css is in the same folder

---

## ✨ You're All Set!

Your portfolio is:
- ✅ Mobile-friendly
- ✅ Professional design
- ✅ Easy to update
- ✅ Ready for recruiters
- ✅ Fast and modern

**Next Steps:**
1. Test locally
2. Add your resume
3. Deploy online
4. Share with recruiters!

Good luck with placements! 🎓💼

---

**Pro Tip:** Update your projects section every time you complete a new project. 
Keep your portfolio fresh and relevant!
