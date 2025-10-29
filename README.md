# EduSphere - Modern Education Platform

A comprehensive education website built with Node.js and Express, featuring a modern design system and responsive layouts for online learning and academic excellence.

## 🌟 Features

- **Modern Design System**: Professional UI with custom CSS variables, gradients, and modern typography
- **Responsive Layout**: Mobile-first design that works seamlessly across all devices
- **Multi-page Architecture**: Home, About, and Contact pages with consistent navigation
- **Interactive Elements**: Hover effects, smooth transitions, and engaging visual components
- **Contact Form Integration**: Working contact form with Formspree integration
- **Performance Optimized**: Clean HTML5 structure with semantic markup and accessibility features

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

####Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/education-website.git
   cd education-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or
   node app.js
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the website

## 📁 Project Structure

```
education-website/
├── app.js                 # Express server configuration
├── package.json          # Project dependencies and scripts
├── public/               # Static assets and HTML files
│   ├── index.html        # Homepage with hero, programs, testimonials
│   ├── about.html        # About page with mission, values, team
│   ├── contact.html      # Contact page with form and FAQs
│   └── css/
│       └── styles.css    # Comprehensive design system
└── README.md            # This file
```

## 🎨 Design System

The website features a cohesive design system with:

- **Color Palette**: Brand blues (#2563eb, #0ea5e9) with accent yellow (#facc15)
- **Typography**: Inter font family with carefully crafted type scales
- **Components**: Reusable cards, buttons, grids, and navigation elements
- **Layouts**: Flexible grid systems and responsive containers
- **Animations**: Subtle hover effects and smooth transitions

## 📄 Page Overview

### Home Page (`/`)
- Hero section with value proposition and key statistics
- Program showcase highlighting different learning tracks
- Testimonials from students, educators, and institutions
- Call-to-action sections for engagement

### About Page (`/about`)
- Mission statement and organizational values
- Company timeline and key milestones
- Leadership team profiles
- Partnership information

### Contact Page (`/contact`)
- Multiple contact methods (email, phone, form)
- Interactive contact form with validation
- Frequently asked questions
- Response time expectations

## 🛠 Customization

### Updating Content
- Edit HTML files in the `public/` directory
- Modify text, images, and links directly in the markup
- Update contact information in `contact.html`

### Styling Changes
- All styles are contained in `public/css/styles.css`
- CSS variables at the top of the file control colors and spacing
- Component classes are well-documented and modular

### Adding New Pages
1. Create new HTML file in `public/` directory
2. Add route in `app.js`
3. Update navigation links in all existing pages

## 🌐 Deployment

### Netlify (Recommended)
1. Connect your GitHub repository to Netlify
2. Set build command: `npm install`
3. Set publish directory: `public`
4. Deploy automatically on git push

### Heroku
1. Create `Procfile` with: `web: node app.js`
2. Push to Heroku git remote
3. Set environment variables if needed

### Traditional Hosting
1. Upload `public/` folder contents to web server
2. Configure server to serve static files
3. Update any absolute paths if necessary

## 📧 Contact Form Setup

The contact form uses Formspree for handling submissions:

1. Sign up 
2. Create a new form endpoint
3. Replace the form action URL in `contact.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="post">
   ```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🎯 Roadmap

- [ ] User authentication system
- [ ] Course enrollment functionality
- [ ] Payment integration
- [ ] Student dashboard
- [ ] Instructor portal
- [ ] Mobile app development

---

**Built with ❤️ for modern education** | 

<img width="833" height="416" alt="image" src="https://github.com/user-attachments/assets/7c8dfbba-c279-4de1-878d-7b40de83081c" />
<img width="826" height="411" alt="image" src="https://github.com/user-attachments/assets/d68aced1-a606-4283-ad62-f1a66d504b2d" />
<img width="826" height="426" alt="image" src="https://github.com/user-attachments/assets/602fe265-9850-40ec-a2c6-42a02a45425a" />




