# Vanessa Faustine Ishimwe - Portfolio Website

A modern, professional portfolio website showcasing skills, experience, and projects.

## ✨ New Features Added

### 🌓 Dark/Light Mode Toggle
- **Location**: Top-right corner of navigation bar (moon/sun icon)
- **Functionality**: Click to switch between dark and light themes
- **Persistence**: Your theme preference is saved in browser localStorage
- **Smooth Transition**: All colors transition smoothly when switching themes

### 📝 Contact Form
- **Location**: Contact section (left side)
- **Fields**:
  - Your Name (required)
  - Your Email (required)
  - Subject (required)
  - Message (required, expandable textarea)
- **Functionality**: 
  - Form validation
  - Success message on submission
  - Auto-reset after submission
  - Button changes to "✓ Message Sent!" with green gradient
- **Note**: Currently logs to console. To connect to a backend, add your API endpoint in the JavaScript

### 🔗 Social Media Links
- **Location**: Footer section
- **Platforms**: LinkedIn, GitHub, Twitter, Instagram
- **Update**: Replace placeholder URLs with your actual social media profiles
- **Interactive**: Hover effects with rotation and shadow animations

### 🎨 Enhanced Projects Section
- **6 Detailed Project Cards**:
  1. E-Commerce Platform
  2. Student Management System
  3. Brand Identity Package
  4. Mobile App Prototype
  5. Portfolio Website Template
  6. Secure Login System
- Each card includes specific technologies and detailed descriptions

## 🎯 How to Use

### Opening the Website
Simply double-click `index.html` or open it in any modern web browser:
- Chrome
- Firefox
- Safari
- Edge

### Customizing Social Media Links
Edit the footer section in `index.html` (around line 1294):
```html
<a href="YOUR_LINKEDIN_URL" target="_blank">💼</a>
<a href="YOUR_GITHUB_URL" target="_blank">💻</a>
<a href="YOUR_TWITTER_URL" target="_blank">🐦</a>
<a href="YOUR_INSTAGRAM_URL" target="_blank">📸</a>
```

### Connecting the Contact Form
To connect the form to a backend service:

1. **Using EmailJS** (Free):
   - Sign up at emailjs.com
   - Add their SDK before the closing `</body>` tag
   - Update the form submission handler

2. **Using Formspree** (Free):
   - Sign up at formspree.io
   - Change the form action attribute
   - Add method="POST"

3. **Using Your Own Backend**:
   - Update the form submission handler around line 1375
   - Replace the console.log with a fetch/axios call to your API

### Updating Projects
Replace the placeholder projects with your actual work:
- Update project titles
- Change descriptions
- Modify technology tags
- Add project links if available

## 🎨 Color Scheme

- **Coral**: #FF6B6B (Accent color)
- **Teal**: #06D6A0 (Primary action color)
- **Navy**: #0A1128 (Dark background)
- **Cream**: #FFF8F0 (Text color)
- **Gold**: #FFD23F (Highlights)
- **Slate**: #1E2749 (Card backgrounds)

## 📱 Responsive Design

The website is fully responsive and optimized for:
- 📱 Mobile phones (320px and up)
- 📱 Tablets (768px and up)
- 💻 Laptops (1024px and up)
- 🖥️ Desktops (1440px and up)

## 🚀 Features

✅ Single HTML file (easy to deploy)
✅ Embedded CSS and JavaScript
✅ No external dependencies (except Google Fonts)
✅ Fast loading
✅ Smooth scroll navigation
✅ Active navigation state tracking
✅ Fade-in animations on scroll
✅ Interactive hover effects
✅ Mobile-friendly hamburger menu
✅ Theme toggle with localStorage
✅ Working contact form
✅ Social media integration
✅ SEO-friendly semantic HTML

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload `index.html`
3. Go to Settings → Pages
4. Select main branch
5. Your site will be live at `username.github.io/repository-name`

### Netlify (Free)
1. Drag and drop the `index.html` file to netlify.com/drop
2. Get instant deployment with custom domain support

### Vercel (Free)
1. Sign up at vercel.com
2. Import your repository or upload the file
3. Deploy with one click

### Traditional Web Hosting
Upload `index.html` to any web hosting service via FTP

## 🛠️ Customization Tips

1. **Change Colors**: Update CSS variables in the `:root` section (line 17)
2. **Update Fonts**: Replace Google Fonts links with your preferred fonts
3. **Add More Sections**: Copy existing section structure and modify
4. **Modify Animations**: Adjust transition durations and effects in CSS
5. **Add Images**: Replace emoji icons with actual images or SVGs

## 📧 Contact Information

- **Email**: ishimwevanessa64@gmail.com
- **Phone**: +250 791 115 017
- **Location**: Kamonyi, Southern Province, Rwanda

## 📄 License

This portfolio is created for Vanessa Faustine Ishimwe. Feel free to use the code structure for your own portfolio!

---

**Built with ❤️ using HTML5, CSS3, and JavaScript**
