# Microsoft Certifications 2026 - Frontend

This project is a frontend web page that displays the latest Microsoft certifications for 2026, including Azure, GitHub, and Microsoft 365 certifications.

## Features

- ✨ **Modern and Responsive Design**: Adapted for mobile devices, tablets, and desktop
- 🌓 **Dark/Light Mode**: Theme toggle with localStorage persistence
- 📱 **Fully Responsive**: Designed with CSS Grid and Flexbox
- 🎨 **Smooth Animations**: Transitions and hover effects
- ♿ **Accessible**: ARIA labels and screen reader support
- 📊 **Updated Information**: Data obtained using microsoft_docs_search

## Included Certifications

### GitHub Certifications
- GitHub Foundations (Beginner)
- GitHub Actions (Intermediate)
- GitHub Copilot (Intermediate)
- GitHub Administration Beta (Intermediate)
- GitHub Advanced Security (Intermediate)

### Azure Certifications
- Azure Administrator Associate (Intermediate)
- Azure Solutions Architect Expert (Expert)
- Cloud and AI Security Engineer Associate SC-500 (NEW - Beta May 2026)
- Security, Compliance, and Identity Fundamentals (Beginner)

### Microsoft 365 Certifications
- Collaboration Communications Systems Engineer Associate (NEW)
- Copilot and Agent Administration Fundamentals (NEW)

## Usage

Simply open the `index.html` file in your preferred web browser.

```bash
# If you have Python installed, you can use a local server:
python -m http.server 8000

# Or with Node.js:
npx serve
```

Then open your browser at `http://localhost:8000`

## Project Structure

```
.
├── index.html      # Main page with content
├── styles.css      # CSS styles with theme support
├── script.js       # JavaScript for interactive functionality
└── README.md       # This file
```

## Technologies Used

- HTML5
- CSS3 (CSS Variables, Grid, Flexbox, Media Queries)
- JavaScript ES6+ (Vanilla JS)
- LocalStorage API
- Intersection Observer API

## Design Features

- **Color Palette**: Based on official Microsoft colors
- **Typography**: Segoe UI (Microsoft's official font)
- **Responsive Breakpoints**: 480px, 768px, 1200px
- **Animations**: Fade-in, hover effects, smooth scrolling
- **Accessibility**: ARIA labels, keyboard navigation, screen reader support

## Certifications Information

All certification data was obtained from official Microsoft Learn documentation using the `microsoft_docs_search` tool, ensuring accurate and up-to-date information for 2026.

## Sources

- [Microsoft Learn - Certifications](https://learn.microsoft.com/credentials/certifications/)
- [Microsoft Partner Center Announcements 2026](https://learn.microsoft.com/partner-center/announcements/)
- [GitHub Certifications](https://learn.microsoft.com/credentials/browse/?products=github)

## License

This project is a proof of concept (POC) created for educational purposes.
