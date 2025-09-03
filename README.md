<img width="798" height="474" alt="image" src="https://github.com/user-attachments/assets/a40fa0e6-8b09-4eaa-93f8-20a4ccb4597c" />


# Portfolio Template

A sophisticated, museum-inspired portfolio template crafted for the **GFG Patna Workshop**. Features Louvre-level sophistication, designed for developers who appreciate clean, professional design.

<img width="1220" height="687" alt="image" src="https://github.com/user-attachments/assets/585f9d5c-00e0-452c-9bce-938fad7fe387" />


## ✨ Features

- **Museum-Quality Design**: Inspired by Louvre aesthetics
- **Light/Dark Theme Toggle**: Smooth transitions with elegant animations  
- **Fully Responsive**: Perfect on all devices from mobile to desktop
- **Interactive Elements**: 3D profile frame, typing animations, scroll effects
- **Professional Typography**: Playfair Display + Inter + Crimson Pro
- **Smooth Animations**: CSS custom properties with elegant transitions
- **Contact Form**: Built-in validation with professional feedback
- **SEO Optimized**: Semantic HTML with proper meta tags

## 🚀 Quick Start

### Step 1: Give it a Star ⭐
If you find this template useful, please give it a star! It helps others discover this project.

### Step 2: Fork the Repository
1. Click the **Fork** button at the top right of this repository
2. This creates a copy in your GitHub account

### Step 3: Clone Your Fork
```bash
# Replace 'your-username' with your actual GitHub username
git clone https://github.com/your-username/museum-portfolio-template.git

# Navigate to the project folder
cd museum-portfolio-template
```

### Step 4: Customize Your Portfolio
Open the files in your favorite code editor and customize:

#### `index.html` - Update Your Information:
```html
<!-- Change Anjali Ray -->
<h1 class="name-main">Anjali Ray</h1>

<!-- Update your role -->
<span class="role-main" id="roleText">Your Title</span>

<!-- Add your description -->
<p class="hero-description">Your personalized description...</p>

<!-- Update contact information -->
<p>ashutoshgautamformal@gmail.com</p>
<p>+91 12345 67890</p>
<p>Your City, State, Country</p>

<!-- Add your social links -->
<a href="https://github.com/yourusername" class="social-link" data-platform="github">
<a href="https://linkedin.com/in/yourusername" class="social-link" data-platform="linkedin">
```

#### `styles.css` - Customize Colors:
```css
:root {
    /* Change accent colors to match your brand */
    --accent-primary: #your-color;
    --accent-secondary: #your-color;
    --accent-tertiary: #your-color;
}
```

#### Add Your Projects:
Replace the placeholder projects with your own work, update images, descriptions, and tech stacks.

#### Add Your Skills:
Update the skills section with your technologies and adjust the progress percentages.

### Step 5: Test Locally
```bash
# Use Live Server in VS Code, or any local server
# Don't open index.html directly in browser - use a server!

# Alternative: Python simple server
python -m http.server 8000

# Alternative: Node.js serve
npx serve .
```

### Step 6: Deploy to Netlify

#### Option A: Drag & Drop
1. Go to [Netlify](https://netlify.com)
2. Drag your project folder to the deploy area
3. Your site is live!

#### Option B: Git Integration
1. Push your changes to GitHub:
```bash
git add .
git commit -m "Customize portfolio with my information"
git push origin main
```
2. Connect your GitHub repo to Netlify
3. Enable auto-deploy

### Step 7: Custom Domain (Optional)
1. Buy a domain from any provider
2. In Netlify, go to Domain Settings
3. Add your custom domain
4. Update DNS records as instructed

## 📁 File Structure

```
museum-portfolio-template/
│
├── index.html          # Main HTML file
├── styles.css          # All styling (museum-quality CSS)
├── script.js           # Interactive functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### Colors
The template uses CSS custom properties. Change the accent colors in `:root`:
```css
--accent-primary: #8b6f47;    /* Warm Bronze */
--accent-secondary: #6b5b73;  /* Muted Aubergine */  
--accent-tertiary: #7c8471;   /* Sage Green */
```

### Typography  
Three font families are used:
- **Headings**: Playfair Display (elegant serif)
- **Body**: Inter (clean sans-serif)
- **Accents**: Crimson Pro (readable serif)

### Sections
- **Hero**: Your introduction and main CTA
- **About**: Your story in three cards + skills notebook
- **Projects**: Showcase your best work
- **Skills**: Technical skills with progress bars
- **Contact**: Contact form + your information

### Theme Toggle
The light/dark theme toggle is fully functional. Colors automatically adjust using CSS custom properties.

## 🛠️ Development Tips

### Adding New Sections
Follow the existing pattern:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <div class="section-number">05</div>
            <h2 class="section-title">
                <span class="title-word">New</span>
                <span class="title-word">Section</span>
            </h2>
        </div>
        <!-- Your content -->
    </div>
</section>
```

### Adding Animations
Use the `.fade-in` class on elements you want to animate on scroll:
```html
<div class="my-element fade-in">Content</div>
```

### Performance
- All animations use `transform` and `opacity` for smooth 60fps performance
- Images are optimized with proper `loading="lazy"` where appropriate
- CSS uses efficient selectors and minimal repaints

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

Found a bug or want to contribute? 

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created By

**Ashutosh Gautam** for **GFG Patna Workshop**

- GitHub: [@ashutoshgautams](https://github.com/ashutoshgautams)
- Workshop: GeeksforGeeks Patna Chapter

## 🙏 Acknowledgments

- Inspired by Harvey.ai's clean aesthetics
- Museum design principles from Louvre's digital presence
- Typography choices inspired by editorial design
- Color palette based on warm, professional tones

---

**⭐ If this template helped you create an amazing portfolio, don't forget to star this repository!**

Happy coding! 🚀
