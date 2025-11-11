# Professional Portfolio Website

A modern, responsive portfolio website showcasing your skills, projects, and professional experience.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations and transitions
- **Interactive Navigation**: Fixed navigation bar with smooth scrolling and mobile hamburger menu
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Section**: Personal introduction and professional background
- **Skills Section**: Showcase your technical skills and expertise
- **Projects Section**: Display featured projects with descriptions and links
- **Contact Section**: Contact form and social media links
- **Smooth Animations**: Scroll-triggered animations for better user experience

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- No external dependencies or frameworks required

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor for customization (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ranjith1605/Portofolio1.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Portofolio1
   ```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server (e.g., Live Server extension in VS Code)

## Customization

### Personal Information

Edit the following in `index.html`:

1. **Hero Section**: Update your name, title, and description
2. **About Section**: Add your personal bio and background
3. **Skills Section**: Modify skill cards to reflect your expertise
4. **Projects Section**: Update project cards with your own projects
5. **Contact Section**: Add your contact information and social media links

### Styling

Customize colors and styling in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Accent color */
    --dark-bg: #0f172a;            /* Dark background */
    --light-bg: #f8fafc;           /* Light background */
}
```

### Adding Images

To add project images:

1. Create an `images` folder in the root directory
2. Add your images to the folder
3. Update the `project-image` div in `index.html`:
   ```html
   <div class="project-image">
       <img src="images/your-image.jpg" alt="Project name">
   </div>
   ```

## Project Structure

```
Portofolio1/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── LICENSE             # MIT License
```

## Features Breakdown

### Navigation
- Fixed header that stays visible while scrolling
- Smooth scroll to sections
- Mobile-responsive hamburger menu
- Active section highlighting

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Flexible grid layouts
- Touch-friendly navigation

### Animations
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Smooth transitions throughout
- Staggered animations for cards

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select the branch (main) and root folder
5. Save and wait for deployment

### Other Platforms

This portfolio can be deployed on:
- Netlify
- Vercel
- Heroku
- Any static hosting service

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out through the contact form on the website or open an issue in this repository.

## Acknowledgments

- Icons: Emoji characters (no external dependencies)
- Fonts: System fonts for fast loading
- Design inspiration: Modern portfolio best practices

---

**Made with ❤️ | © 2025**
