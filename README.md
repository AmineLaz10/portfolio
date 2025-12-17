# Data Scientist Portfolio Website

A clean, minimalist portfolio website inspired by Yan Holtz's design. Perfect for showcasing your data science projects, services, and expertise.

## Features

- ✨ Clean, minimalist design with network pattern background
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎯 Smooth scrolling navigation
- 🎨 Portfolio filtering system
- 💬 Testimonials slider
- ⚡ Fast and lightweight
- 🎭 Modern animations and transitions

## Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
   - Or use a local server: `python -m http.server 8000` (Python 3)
   - Or use: `npx serve` (Node.js)

2. **Customize your content**: Edit `index.html` to add your information

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace `YOUR` and `NAME` in the home section
- **Social Links**: Update Twitter, GitHub, and LinkedIn URLs
- **Email**: Replace `your.email@example.com` in the contact section
- **Intro Text**: Customize the introduction paragraph
- **Profile Image**: Replace the placeholder with your photo

### 2. Timeline & Experience

Update the timeline section in the Intro area with your work history:

```html
<div class="timeline-item">
    <span class="year">2024</span>
    <span class="role">Your Role - Company Name</span>
</div>
```

### 3. Services

Modify the services section to match what you offer:

```html
<div class="service-card">
    <div class="service-icon">🔧</div>
    <h3>Your Service</h3>
    <p>Description of your service.</p>
</div>
```

### 4. Portfolio Projects

Add your projects to the portfolio section:

```html
<div class="portfolio-item" data-category="ml">
    <div class="portfolio-image">
        <img src="path/to/your/image.jpg" alt="Project Name">
    </div>
    <h3>Project Name</h3>
    <p>Project description.</p>
</div>
```

**Categories available**: `ml`, `viz`, `analysis`, `dashboard`

### 5. Testimonials

Replace the testimonials with real ones from your clients:

```html
<div class="testimonial">
    <p class="testimonial-text">"[Your testimonial text]"</p>
    <p class="testimonial-author">— Client Name - <em>Position at Company</em></p>
</div>
```

### 6. Colors

Customize colors in `styles.css`:

```css
:root {
    --primary-color: #4ecdc4;  /* Teal/mint green accent */
    --text-color: #1a1a1a;     /* Main text color */
    --bg-color: #ffffff;        /* Background color */
}
```

### 7. Logo

Replace the SVG logo in the name container with your own logo or design.

## File Structure

```
Portfolio/
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

1. **Images**: Add your project images to a folder (e.g., `images/`) and reference them in the portfolio items
2. **Profile Photo**: Use a square image (200x200px or larger) for best results
3. **Portfolio Images**: Recommended size: 600x400px for portfolio project images
4. **Performance**: Optimize images before uploading for faster load times

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly!

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## License

Feel free to use this template for your own portfolio!

## Credits

Design inspired by [Yan Holtz's portfolio](https://www.yan-holtz.com/)

