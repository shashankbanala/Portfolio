# Personal Portfolio Website

A modern, responsive portfolio website for Data Analysts and Engineers. Built with vanilla HTML, CSS, and JavaScript - no frameworks required!

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading with no dependencies
- 🎯 SEO-friendly structure
- 🌐 Easy to customize

## Sections

- **Hero**: Eye-catching introduction
- **About**: Personal information and statistics
- **Skills**: Technical skills organized by category
- **Projects**: Showcase your work with project cards
- **Experience**: Timeline of your professional journey
- **Contact**: Contact information and social links

## Customization

### 1. Update Personal Information

Edit `index.html` and replace:
- `Your Name` with your actual name
- `your.email@example.com` with your email
- Phone number and location
- Social media links

### 2. Update Skills

In the Skills section, modify the skill tags to match your expertise:
```html
<span class="skill-tag">Your Skill</span>
```

### 3. Add Your Projects

Replace the example projects with your own:
- Update project titles and descriptions
- Add your GitHub and demo links
- Modify project tags

### 4. Update Experience

Edit the timeline items in the Experience section with your work history.

### 5. Customize Colors

Edit `styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... */
}
```

## Free Hosting Options

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select the main branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`

**Steps:**
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git push -u origin main
```

### Option 2: Netlify

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up for free
3. Drag and drop your project folder
4. Your site is live instantly!

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign up for free
3. Import your GitHub repository or upload files
4. Deploy with one click

### Option 4: Cloudflare Pages

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repository
3. Deploy automatically

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Tips

- Add your own projects with real GitHub links
- Include screenshots or images in project cards
- Update the statistics in the About section
- Customize colors to match your brand
- Add a favicon for a professional touch

## License

Feel free to use this template for your personal portfolio!

---

**Need help?** Open an issue or customize the code to fit your needs!

