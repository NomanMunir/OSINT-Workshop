# OSINT Workshop

> Open Source Intelligence Training for Engineers and Security Professionals

A comprehensive, beginner-friendly workshop designed to teach OSINT (Open Source Intelligence) techniques through hands-on activities. This workshop covers advanced search operators, reverse image search, and device reconnaissance.

## 🎯 Overview

This workshop provides practical, interactive training in OSINT fundamentals. Each activity includes:
- Clear explanations for beginners
- Real-world examples
- Hands-on challenges
- Step-by-step guidance

**Target Audience:** Engineers, security professionals, and anyone interested in learning OSINT techniques
**Difficulty Level:** Beginner to Intermediate
**Duration:** 2-3 hours (self-paced)

## 📚 Workshop Activities

### Activity 1: Google Dorking
Learn advanced Google search operators to find hidden information across the web.

**Topics Covered:**
- Search operators (`site:`, `filetype:`, `inurl:`, `intitle:`, `intext:`)
- Finding exposed directories and files
- Configuration file discovery
- Admin panel identification
- Document hunting

**Challenge:** Find publicly indexed PDF documents on a university domain

### Activity 2: Reverse Image Search (RIS)
Master visual intelligence through reverse image search techniques.

**Topics Covered:**
- Google Images (general searches)
- Yandex (facial recognition, landmarks)
- TinEye (image history and verification)
- Geolocation techniques
- Image verification

**Challenge:** Identify a famous landmark using RIS tools

### Activity 3: Shodan Recon
Explore the Internet of Things (IoT) search engine for connected devices.

**Topics Covered:**
- Shodan search filters
- Finding exposed devices (webcams, servers, industrial systems)
- Geographic filtering
- Security reconnaissance
- Understanding device exposure

**Challenge:** Count internet-connected printers in the UAE

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge)
- Internet connection
- (Optional) Free Shodan account for Activity 3

### Quick Start

1. **Open the workshop:**
   ```bash
   # Navigate to the workshop directory
   cd OSINT-Workshop
   
   # Open index.html in your browser
   # On Windows:
   start index.html
   
   # On macOS:
   open index.html
   
   # On Linux:
   xdg-open index.html
   ```

2. **Follow the activities in order:**
   - Start with Activity 1 (Google Dorking)
   - Progress to Activity 2 (Reverse Image Search)
   - Complete Activity 3 (Shodan Recon)

3. **Complete the challenges** in each activity to practice your skills

## 📁 Project Structure

```
OSINT-Workshop/
├── index.html                        # Main landing page
├── activities/                       # Workshop activity files
│   ├── activity-01-google-dorking.html
│   ├── activity-02-reverse-image-search.html
│   └── activity-03-shodan-recon.html
├── assets/                          # Static assets
│   └── images/                      # Image files
│       └── 20250115072739.png       # Activity 2 challenge image
├── docs/                            # Documentation
│   └── CONTRIBUTING.md              # Contribution guidelines
├── .github/                         # GitHub configuration
│   └── copilot-instructions.md      # AI coding guidelines
├── README.md                        # This file
├── LICENSE                          # MIT License
└── .gitignore                       # Git ignore rules
```

## 🎨 Design Features

- **Cyber Intelligence Theme:** Dark mode with matrix-green accents
- **Glassmorphism UI:** Modern semi-transparent card designs
- **Responsive Layout:** Works on desktop, tablet, and mobile
- **Interactive Elements:** Copy-to-clipboard functionality, hover effects
- **Beginner-Friendly:** Clear explanations and step-by-step guides

## 🛡️ Legal & Ethical Guidelines

### ⚠️ Important Notice

This workshop is for **educational purposes only**. All activities must be conducted ethically and legally.

**Key Principles:**

1. **Respect Privacy:** Only access publicly available information
2. **Legal Compliance:** Viewing indexed data is research; unauthorized access is illegal
3. **Ethical Use:** Use these skills for security improvement and legitimate research
4. **No Harm:** Never attempt to access, modify, or damage systems without authorization
5. **Responsible Disclosure:** If you discover vulnerabilities, report them responsibly

**Legal Boundaries:**
- ✅ Searching public data on Google, Yandex, Shodan
- ✅ Viewing publicly indexed information
- ✅ Educational research and learning
- ❌ Accessing systems without permission
- ❌ Attempting to bypass security measures
- ❌ Unauthorized data collection or scraping

## 🔧 Technical Details

### Technologies Used
- **HTML5:** Structure and content
- **Tailwind CSS:** Styling via CDN
- **FontAwesome:** Icons via CDN
- **JavaScript:** Copy-to-clipboard functionality
- **JetBrains Mono:** Monospaced font for code

### Browser Compatibility
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## 📖 Learning Outcomes

After completing this workshop, participants will be able to:

1. **Use Advanced Search Operators**
   - Construct complex Google dork queries
   - Find exposed files and directories
   - Identify security misconfigurations

2. **Perform Visual Intelligence**
   - Use multiple RIS tools effectively
   - Verify image authenticity
   - Geolocate images and landmarks

3. **Conduct Device Reconnaissance**
   - Search for exposed IoT devices
   - Understand Shodan filters and queries
   - Assess organizational security posture

4. **Apply OSINT Ethically**
   - Understand legal boundaries
   - Practice responsible disclosure
   - Respect privacy and security

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-activity`)
3. Commit your changes (`git commit -m 'Add new activity'`)
4. Push to the branch (`git push origin feature/new-activity`)
5. Open a Pull Request

### Contribution Ideas
- Additional OSINT activities
- Improved challenges and examples
- UI/UX enhancements
- Documentation improvements
- Bug fixes and optimizations

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Credits

**Created by:** NomanMunir
**Repository:** [OSINT-Workshop](https://github.com/NomanMunir/OSINT-Workshop)

## 📞 Support

For questions, issues, or suggestions:
- Open an issue on GitHub
- Contact via repository discussions
- Submit a pull request

## 🔗 Additional Resources

### Recommended Reading
- [OSINT Framework](https://osintframework.com/)
- [Google Dorking Cheat Sheet](https://www.sans.org/security-resources/GoogleCheatSheet.pdf)
- [Shodan Documentation](https://help.shodan.io/)
- [Bellingcat's Online Investigation Toolkit](https://docs.google.com/spreadsheets/d/18rtqh8EG2q1xBo2cLNyhIDuK9jrPGwYr9DI2UncoqJQ/)

### OSINT Tools
- [Google Images](https://images.google.com)
- [Yandex Images](https://yandex.com/images)
- [TinEye](https://tineye.com)
- [Shodan](https://shodan.io)
- [Censys](https://censys.io)

### Security & Privacy
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Electronic Frontier Foundation](https://www.eff.org/)
- [Responsible Disclosure Guidelines](https://www.bugcrowd.com/blog/getting-started-with-responsible-disclosure/)

---

<div align="center">

**⚠️ Remember: Use these skills ethically and legally ⚠️**

Made with 💻 for the security community

[🏠 Home](index.html) | [📚 Activity 1](activities/activity-01-google-dorking.html) | [🖼️ Activity 2](activities/activity-02-reverse-image-search.html) | [🔍 Activity 3](activities/activity-03-shodan-recon.html)

</div>
