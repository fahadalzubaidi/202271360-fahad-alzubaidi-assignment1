# Personal Portfolio Website - Assignment 1

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript, showcasing projects, skills, and professional information.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with persistent preference storage
- **Smooth Scrolling**: Elegant navigation with smooth scrolling animations
- **Time-Based Greeting**: Dynamic greeting message that adapts based on the time of day
- **Interactive Forms**: Contact form with client-side validation and user feedback
- **Modern Animations**: Scroll-reveal animations, hover effects, and smooth transitions
- **Accessible**: Semantic HTML and ARIA labels for better accessibility

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with profile image and call-to-action buttons
2. **About Me**: Personal introduction with achievement statistics
3. **Projects**: Showcase of 3 featured projects with descriptions and technology tags
4. **Skills**: Visual representation of technical skills with animated progress bars
5. **Contact**: Functional contact form with email, phone, and location information

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No server required - runs entirely on the client side

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Open `index.html` in your web browser

```bash
# Option 1: Open directly
start index.html  # Windows
open index.html   # macOS
xdg-open index.html  # Linux

# Option 2: Use a local server (recommended)
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using VS Code Live Server extension
# Right-click index.html and select "Open with Live Server"
```

Then navigate to `http://localhost:8000` in your browser.

## 📁 Project Structure

```
assignment-1/
├── README.md                      # Project documentation
├── index.html                     # Main HTML file
├── css/
│   └── styles.css                # Stylesheet with modern design system
├── js/
│   └── script.js                 # JavaScript for interactivity
├── assets/
│   └── images/                   # Project and profile images
├── docs/
│   ├── ai-usage-report.md       # AI tools usage documentation
│   └── technical-documentation.md # Technical details
└── .gitignore                    # Git ignore file
```

## 🎨 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, custom properties, and animations
- **JavaScript (ES6+)**: Interactive features and DOM manipulation
- **Google Fonts**: Inter and Outfit font families
- **Local Storage API**: Theme preference persistence

## ✨ JavaScript Features

1. **Smooth Scrolling**: Click navigation links for smooth page transitions
2. **Theme Toggle**: Switch between dark and light modes (preference saved)
3. **Dynamic Greeting**: Time-appropriate greeting message (morning/afternoon/evening/night)
4. **Form Validation**: Client-side validation for contact form
5. **Scroll Animations**: Elements reveal as you scroll
6. **Navbar Effects**: Navbar appearance changes on scroll
7. **Active Link Highlighting**: Current section highlighted in navigation

## 🤖 AI Integration

This project was developed with assistance from AI tools to enhance productivity and code quality. Detailed information about AI usage can be found in:

- [AI Usage Report](docs/ai-usage-report.md) - Comprehensive documentation of AI tool usage, benefits, challenges, and learning outcomes

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Customization Guide

### Personalizing the Portfolio

1. **Update Personal Information**:
   - Edit `index.html` and replace "Your Name" with your actual name
   - Update email, phone, and location in the contact section

2. **Add Your Projects**:
   - Replace project titles, descriptions, and tags in the projects section
   - Add your project images to `assets/images/`

3. **Modify Skills**:
   - Update skill categories and progress percentages in the skills section

4. **Change Color Scheme**:
   - Edit CSS custom properties in `css/styles.css` (lines 1-50)
   - Modify `--color-primary`, `--color-secondary`, and `--color-accent`

5. **Add Your Images**:
   - Replace `profile.jpg`, `project1.jpg`, `project2.jpg`, `project3.jpg` in `assets/images/`
   - Recommended dimensions: Profile (400x400px), Projects (1600x1000px)

## 🌐 Deployment

### GitHub Pages (Free)

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select main branch and root folder
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)

1. Create an account at [Netlify](https://netlify.com)
2. Drag and drop your project folder
3. Get instant deployment with custom domain support

### Vercel (Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts for deployment

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Assignment requirements from SWE363 course
- Design inspiration from modern portfolio websites
- AI assistance from Claude/ChatGPT for code optimization and documentation
- Google Fonts for typography
- Icons from inline SVG

---

**Note**: This is an educational project created for SWE363 - Assignment 1. Feel free to use it as a template for your own portfolio!
