# Guru Prasad Reddy Kothakapu - Cybersecurity Portfolio

A professional, cybersecurity-themed portfolio website showcasing skills, projects, and achievements in the field of cybersecurity and software development.

## 🚀 Features

- **Modern Cybersecurity Theme**: Dark theme with green accent colors and cyber-inspired animations
- **Responsive Design**: Fully responsive across all devices and screen sizes
- **Interactive Elements**:
  - Animated typing effect in hero section
  - Matrix rain background animation
  - Smooth scrolling navigation
  - Hover effects and transitions
  - Loading screen with cyber-themed loader
- **Comprehensive Sections**:
  - Hero section with professional introduction
  - About/Executive summary
  - Education timeline
  - Skills matrix with progress bars
  - Featured projects showcase
  - Experience and internships
  - Achievements and certifications
  - Contact form and information

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Animations**: CSS animations and AOS (Animate On Scroll) library
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Orbitron, Roboto)

## 📁 Project Structure

```
Portfolio/
├── .gitignore              # Git ignore rules
├── README.md               # Project documentation (this file)
├── index.html              # Main HTML file
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
└── assets/
    ├── favicon.svg         # Website favicon
```

**Note**: The project is Git-ready with proper ignore rules and documentation.

## 🎨 Design Features

### Color Palette

- **Primary**: #00ff41 (Cyber Green)
- **Secondary**: #0066cc (Tech Blue)
- **Accent**: #ff6b35 (Warning Orange)
- **Background**: #0a0a0a (Deep Black)
- **Cards**: #1a1a1a (Dark Gray)

### Typography

- **Headers**: Orbitron (Futuristic, tech-inspired)
- **Body**: Roboto (Clean, readable)

### Animations

- Matrix rain effect in hero background
- Typing animation for role titles
- Smooth scroll navigation
- Hover effects on cards and buttons
- Loading screen with spinning rings
- Glitch effect on main title

## 🔧 Git Setup & Version Control

### Quick Start (Repository Ready!)

This project is now Git-ready with a `.gitignore` file already included. To start version control:

1. **Initialize Git Repository**:

   ```bash
   cd c:\My_Projects\Portfolio
   git init
   git add .
   git commit -m "Initial commit: Portfolio website setup"
   ```
2. **Connect to Remote Repository**:

   ```bash
   # Create a new repository on GitHub, then:
   git remote add origin https://github.com/guruprasadreddyk/portfolio.git
   git branch -M main
   git push -u origin main
   ```

### Git Configuration

The project includes a comprehensive `.gitignore` file that excludes:

- OS-generated files (Thumbs.db, .DS_Store, etc.)
- Editor configuration files (.vscode/, .idea/, etc.)
- Temporary and log files
- Personal/sensitive configuration files
- Build outputs and dependencies

### Repository Structure for Git

```
Portfolio/
├── .gitignore              # Git ignore rules (included)
├── README.md               # Project documentation
├── index.html              # Main HTML file
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
└── assets/
    ├── favicon.svg         # Website favicon
```

### Git Workflow & Best Practices

1. **Daily Development Workflow**:

   ```bash
   # Check current status
   git status

   # Add specific files or all changes
   git add .
   # or git add specific-file.html

   # Commit with descriptive message
   git commit -m "Update: Add new project to portfolio"

   # Push to remote repository
   git push origin main
   ```
2. **Feature Development**:

   ```bash
   # Create and switch to feature branch
   git checkout -b feature/new-section

   # Make your changes, then:
   git add .
   git commit -m "Add new portfolio section with animations"
   git push origin feature/new-section

   # Merge back to main (after review)
   git checkout main
   git merge feature/new-section
   git push origin main
   ```
3. **Content Updates**:

   ```bash
   # For regular content updates
   git add .
   git commit -m "Update: Add latest project and certifications"
   git push origin main
   ```
4. **Git Best Practices for Portfolio**:

   - **Commit frequently**: After each significant change or addition
   - **Descriptive messages**: Use clear, specific commit messages
   - **Organize commits**: Group related changes together
   - **Branch for experiments**: Use branches for major redesigns
   - **Keep history clean**: Avoid committing temporary or test files
   - **Regular backups**: Push to remote repository regularly
5. **Common Git Commands for This Project**:

   ```bash
   # View commit history
   git log --oneline

   # See what files changed
   git diff

   # Undo last commit (keep changes)
   git reset --soft HEAD~1

   # Check remote repository status
   git remote -v

   # Pull latest changes (if collaborating)
   git pull origin main
   ```

## 📋 Setup Instructions

### For New Users (Cloning from Repository)

1. **Clone and Setup**:
   ```bash
   git clone https://github.com/guruprasadreddyk/portfolio.git
   cd portfolio
   ```

### For Local Development (First Time Setup)

1. **Initialize Git Repository**:

   ```bash
   cd c:\My_Projects\Portfolio
   git init
   git add .
   git commit -m "Initial commit: Portfolio website setup"
   ```
2. **Connect to GitHub** (create repository first on GitHub):

   ```bash
   git remote add origin https://github.com/guruprasadreddyk/portfolio.git
   git branch -M main
   git push -u origin main
   ```
3. **Add Your Profile Photo**:

   - Add your professional headshot as `assets/profile-photo.jpg`
   - Recommended size: 400x400px (square aspect ratio)
   - Should be a clear, professional photo
4. **Update Social Links**:

   - Replace placeholder `#` links with your actual social media profiles
   - Update LinkedIn and GitHub URLs in the contact section
5. **Customize Content**:

   - Review and update all personal information
   - Add or modify projects based on your work
   - Update skills and proficiency levels
   - Add your actual certifications and achievements
6. **Optional Enhancements**:

   - Add project screenshots to `assets/` folder
   - Include your resume as `assets/resume.pdf`
   - Add more interactive features as needed
7. **Commit Your Changes**:

   ```bash
   git add .
   git commit -m "Customize portfolio with personal information"
   git push origin main
   ```

## 🌐 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## ⚡ Performance Features

- Optimized CSS with efficient selectors
- Lazy loading for images
- Debounced scroll events
- Minimal external dependencies
- Compressed and optimized assets

## 🔧 Customization

### Changing Colors

Update the CSS custom properties in `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #00ff41;
    --secondary-color: #0066cc;
    --accent-color: #ff6b35;
    /* ... other colors */
}
```

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS styles in `css/style.css`
3. Update navigation menu if needed
4. Add any required JavaScript functionality

### Modifying Animations

- Animation durations and easing can be adjusted in CSS
- JavaScript animations can be modified in `js/script.js`
- AOS animations can be customized with data attributes

## 📞 Contact Information

- **Email**: kguruprasadreddy2004@gmail.com
- **Phone**: +91 8187830204
- **LinkedIn**: [Guru Prasad Reddy K](https://www.linkedin.com/in/guru-prasad-reddy-k-8577012b9)
- **GitHub**: [Guru Prasad Reddy K](https://github.com/guruprasadreddyk)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- AOS library for scroll animations
- Inspiration from modern cybersecurity and tech websites

---

**Note**: This portfolio is designed specifically for cybersecurity professionals and students. The design emphasizes security, technology, and professionalism while maintaining modern web standards and accessibility.
