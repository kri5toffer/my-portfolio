# Christopher Siang - Personal Portfolio

A modern, responsive personal portfolio website showcasing my skills, experience, and projects as a Software Engineering student specializing in AI. Built with HTML, CSS, and JavaScript for optimal performance and cross-device compatibility.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive UI**: Smooth animations and modern interface
- **Project Showcase**: Display of personal projects with GitHub links
- **Professional Experience**: Timeline of education and work experience
- **Skills Section**: Technical skills and expertise overview
- **Contact Form**: Functional contact form with location map
- **Social Links**: Direct links to LinkedIn, GitHub, Instagram, and Strava profiles

## 📋 Sections

- **About**: Professional summary and background
- **Resume**: Education timeline and work experience
- **Portfolio**: Featured projects with live demos and source code
- **Blog**: Content section (currently disabled)
- **Contact**: Contact form and location details

## Demo

![vCard Desktop Demo](./website-demo-image/desktop.png "Desktop Demo")
![vCard Mobile Demo](./website-demo-image/mobile.png "Mobile Demo")

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with responsive design
- **Icons**: Ion Icons
- **Fonts**: Google Fonts (Poppins)
- **Deployment**: Static hosting compatible

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/kri5toffer/portfolio.git
   cd portfolio/vcard-personal-portfolio
   ```

2. **Open in browser**
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

### Docker Deployment

1. **Build the Docker image**
   ```bash
   docker build -t portfolio-website .
   ```

2. **Run the container**
   ```bash
   docker run -p 8080:80 portfolio-website
   ```

3. **Access the website**
   Open your browser and navigate to `http://localhost:8080`

## 📁 Project Structure

```
vcard-personal-portfolio/
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css   # Main stylesheet
│   ├── js/
│   │   └── script.js   # JavaScript functionality
│   └── images/         # Images and media files
├── Dockerfile          # Docker configuration
└── README.md           # Project documentation
```

## 🌐 Deployment Options

- **GitHub Pages**: Free static hosting
- **Netlify**: Drag-and-drop deployment
- **Vercel**: One-click deployment
- **Docker**: Containerized deployment

## 📱 Contact

- **Email**: chris.siang123@gmail.com
- **LinkedIn**: [Christopher Siang](https://www.linkedin.com/in/christopher-siang/)
- **GitHub**: [kri5toffer](https://github.com/kri5toffer)
- **Location**: Melbourne, Victoria, Australia

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
