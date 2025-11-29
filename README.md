# Vishal Shamanthula - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, projects, and professional experience as a Java Full Stack Developer.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Multiple Pages**:
  - Home page with hero section and skills visualization
  - Resume page with detailed experience and certifications
  - Projects page showcasing portfolio projects
  - Contact page with form and social links
- **Mobile Navigation**: Hamburger menu for mobile devices with smooth animations
- **Skill Progress Bars**: Animated skill bars with percentage indicators
- **Contact Form**: Functional contact form with email validation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript**: Interactive features and form validation
- **No Frameworks**: Pure vanilla HTML, CSS, and JavaScript for fast loading

## 📁 Project Structure

```
Vishal-Portfolio/
│
├── index.html          # Home page
├── resume.html         # Resume page
├── projects.html       # Projects showcase
├── contact.html        # Contact page
├── style.css           # Shared stylesheet
├── script.js           # Shared JavaScript
├── README.md           # Project documentation
└── assets/             # Assets folder
    ├── yourphoto.jpg   # Professional photo (add your photo here)
    └── Vishal_Shamanthula_Resume.pdf  # Resume PDF (add your PDF here)
```

## 📝 Setup Instructions

### 1. Add Your Assets

Before deploying, make sure to add your assets:

- **Professional Photo**: Place your circular professional photo in `assets/yourphoto.jpg` (recommended size: 400x400px)
- **Resume PDF**: Add your resume PDF file as `assets/Vishal_Shamanthula_Resume.pdf`

### 2. Update Contact Information

If needed, update the LinkedIn profile link in `contact.html` (currently set to placeholder).

### 3. Local Testing

To test the website locally:

1. Open `index.html` in a web browser, or
2. Use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
3. Navigate to `http://localhost:8000` in your browser

## 🌐 GitHub Pages Deployment

### Step-by-Step Guide

1. **Push Your Code to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub: `https://github.com/vishalshamanthula/Vishal-Portfolio`
   - Click on **Settings** (top navigation bar)
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select:
     - **Branch**: `main`
     - **Folder**: `/ (root)`
   - Click **Save**

3. **Access Your Website**
   - GitHub will provide a URL like: `https://vishalshamanthula.github.io/Vishal-Portfolio/`
   - It may take a few minutes for the site to be available
   - You'll receive an email notification when the site is live

4. **Custom Domain (Optional)**
   - In the same Pages settings, you can add a custom domain
   - Follow GitHub's instructions for DNS configuration

### Important Notes

- The site will remain active as long as your repository and GitHub account exist
- Any changes you push to the `main` branch will automatically update the website
- GitHub Pages uses HTTPS by default, ensuring secure connections
- The website is automatically served from the root directory

## 🎨 Customization

### Colors
The color scheme can be customized by modifying CSS variables in `style.css`:
```css
:root {
    --primary-blue: #2563eb;
    --primary-blue-dark: #1e40af;
    /* ... other colors ... */
}
```

### Content
- Update personal information in `index.html`
- Modify resume content in `resume.html`
- Add/edit projects in `projects.html`
- Update contact information in `contact.html`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available for personal use.

## 📧 Contact

**Vishal Shamanthula**
- 📍 Hyderabad, India
- 📞 +91 7981387292
- ✉️ shamanthulavishal123@gmail.com

---

**Note**: Remember to replace placeholder assets (photo and resume PDF) before deploying to GitHub Pages.
