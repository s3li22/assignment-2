# Portfolio Website

A modern, responsive portfolio website for a Computer Science student showcasing projects, skills, and contact information.

## Project Description

This is a personal portfolio website built with HTML, CSS, and JavaScript. It features a dark/light theme toggle, responsive design, and interactive project showcases. The portfolio displays academic background, technical skills, project details, and contact information in an elegant, user-friendly interface.

## Setup Instructions

### Running Locally

1. Clone or download the project files
   - Save the HTML file as `index.html`

2. Open the website
   - Option 1: Double-click the `index.html` file to open it in your default browser
   - Option 2: Use a local server for better functionality:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
   - Then visit `http://localhost:8000` in your browser

3. Customization
   - Edit the HTML file directly to update personal information, projects, or skills
   - Modify the CSS variables in the `<style>` section to change colors and styling
   - Update the JavaScript project data array to add new projects

## AI Usage Summary

This project utilized AI assistance for implementing the project details modal functionality. The AI helped create a dynamic modal system that displays comprehensive information about each project when users click "View Details." Key AI contributions included modal design, JavaScript functionality for dynamic content loading, and responsive layout adjustments.

Detailed AI usage information is available in `ai-usage-report.md`.

## Live Deployment

The portfolio can be deployed using:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service