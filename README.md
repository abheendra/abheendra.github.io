# Abheendra Sibu - Data Scientist Portfolio

A modern, responsive portfolio website showcasing my experience, projects, and skills in data science and analytics.

## 🚀 Live Demo

Visit the live site at: `https://[your-github-username].github.io/portfolio`

## 📋 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Sections Include**:
  - Hero/Landing page with social links
  - About section with key statistics
  - Professional experience timeline
  - Featured projects showcase
  - Skills and technologies
  - Education background
  - Contact information

## 🛠️ Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, and CSS Variables)
- JavaScript (Vanilla JS)
- Font Awesome Icons
- GitHub Pages for hosting

## 📦 Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository on GitHub**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `portfolio` or `[your-username].github.io` for automatic GitHub Pages URL
   - Make it public

2. **Upload the files**
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/[your-username]/portfolio.git
     cd portfolio
     ```
   - Copy all the files (`index.html`, `styles.css`, `script.js`) into the repository folder

3. **Commit and push**
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings" > "Pages"
   - Under "Source", select "main" branch and "/" (root) folder
   - Click "Save"
   - Your site will be published at `https://[your-username].github.io/portfolio`

### Option 2: Using GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Create a new repository through GitHub Desktop
3. Add all the portfolio files to the repository folder
4. Commit and push the changes
5. Enable GitHub Pages following step 4 above

## 🎨 Customization

### Update Your Information

1. **Personal Details**: Replace the following in `index.html`:
   - Name: "Abheendra Sibu"
   - Email: "abheendra@gmail.com"
   - Phone: "+49 176 32796110"
   - Location: "Berlin, Germany"
   - LinkedIn: "linkedin.com/in/abheendra"
   - GitHub: Update to your actual GitHub username

2. **Projects**: Update the project cards in the Projects section with:
   - Your actual GitHub repository links
   - Demo links if available
   - Update project descriptions as needed

3. **Colors**: Modify the color scheme in `styles.css` by changing the CSS variables:
   ```css
   :root {
       --primary-color: #2563eb;
       --secondary-color: #1e40af;
       --accent-color: #3b82f6;
   }
   ```

4. **Add a Profile Picture** (Optional):
   - Add your photo to the repository
   - Update the About section in `index.html` to include an image

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Maintenance

### Updating Content

To update your portfolio:
1. Edit the HTML file with your new content
2. Commit and push the changes
3. GitHub Pages will automatically update your site within a few minutes

### Adding New Projects

Add a new project card in the Projects section:
```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-header">
        <h3>Project Name</h3>
        <span class="project-date">Date</span>
    </div>
    <p class="project-description">Description here</p>
    <div class="project-tags">
        <span class="tag">Tech1</span>
        <span class="tag">Tech2</span>
    </div>
    <div class="project-links">
        <a href="github-link" target="_blank">
            <i class="fab fa-github"></i> View Code
        </a>
    </div>
</div>
```

## 📊 Performance

- Lightweight and fast loading
- Optimized for SEO
- Accessible design following best practices

## 📝 License

This project is open source and available for personal use.

## 🤝 Connect

- LinkedIn: [linkedin.com/in/abheendra](https://linkedin.com/in/abheendra)
- GitHub: [github.com/abheendra](https://github.com/abheendra)
- Email: abheendra@gmail.com

---

Built with ❤️ by Abheendra Sibu