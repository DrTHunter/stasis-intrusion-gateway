🔮 ZTNA Cyberpunk Access Denied Page

A cyberpunk-themed access denied page that simulates a Zero Trust Network Access (ZTNA) gateway rejecting unauthorized access attempts. This page serves as an aesthetic deterrent with a slow-drip loading screen that never completes, creating an intimidating but legally safe experience.

---

🎯 Purpose

Create a visually striking "access denied" page that:

· Intimidates unauthorized users with cyberpunk aesthetics
· Simulates security analysis without making false claims
· Never fully loads (stalls at 92%)
· Collects only browser-exposed information (no actual surveillance)
· Conserves bandwidth and resources
· Provides "cold infrastructure" rejection vibes

---

🚀 Features

Feature Description
Cyberpunk Terminal Interface Neon green/blue/pink color scheme with glitch effects
Slow Drip Loading Progress bar advances slowly but stalls at 92%, never completing
Technical Simulation Uses real infrastructure terminology (ZTNA, JWT, edge routing)
Browser Data Collection Collects only publicly available browser information
Auto-termination Stops animations after 25 seconds to conserve resources
Mobile Responsive Adapts to different screen sizes
No External Dependencies Pure HTML/CSS/JS - no frameworks or libraries

---

🛡️ Legal & Ethical Design

This page is intentionally designed to be legally safe:

✅ Safe Practices ❌ Avoided Practices
✅ Clear simulation markers - "[SIMULATION]" prefix ❌ No fake IP collection
✅ Infrastructure-focused - real security terminology ❌ No false authority claims
✅ Browser-exposed data only ❌ No real surveillance
✅ Transparent about capabilities ❌ No law enforcement implications

---

📁 File Structure

```bash
cyberpunk-access-denied/
├── index.html          # Main HTML file
├── README.md           # This documentation
└── screenshot.png      # Optional: Page screenshot
```

---

🔧 Implementation Details

Terminal Simulation Flow

1. Access policy evaluation initiated
2. JWT validation: FAILED
3. Edge route token generated
4. Browser fingerprint analysis
5. Zero Trust policy check
6. ZTNA gate: DENIED
7. Return code: 403 - Forbidden
8. Session terminated

Data Collected (Browser-Exposed Only)

· 📱 User Agent (truncated to 35 characters)
· 🖥️ Screen resolution
· 🌍 Time zone
· 🗣️ Browser language
· 🍪 Cookie enabled status
· 💻 Platform information

Technical Features

· 🏗️ Pure client-side execution
· 🎭 CSS glitch animations
· 📊 JavaScript-controlled progress bar
· 🔢 Random session ID generation
· ⚡ Periodic glitch effects for authenticity
· ⏱️ Auto-cleanup after 25 seconds

---

🎨 Customization

Color Scheme

Color Hex Usage
Primary #00ff9d Neon green - main text
Secondary #00a2ff Neon blue - paths, codes
Error #ff0055 Neon pink - errors, warnings
Background #0a0a12 Dark blue-black - background

Timing Adjustments

```javascript
// Adjust progress bar speed:
progress += Math.random() * 0.5;  // Current speed

// Modify terminal line delays:
{text: '...', delay: 2000},  // Change delay values

// Change total runtime:
setTimeout(() => {...}, 25000);  // Current: 25 seconds
```

Text Content

· ✏️ Edit terminalLines array for different messages
· 📝 Modify footer text in the HTML
· 🏷️ Adjust status header as needed

---

📱 Responsive Design

The page adapts to various screen sizes:

Device Layout Adjustments
Desktop Default cyberpunk terminal layout
Tablets Adjusted terminal height
Mobile Stacked header, optimized spacing

---

⚠️ Important Notes

1. This is a simulation - The page does not perform actual security analysis
2. No server-side processing - Everything runs in the browser
3. Educational/Decorative use - Designed as a deterrent, not a security tool
4. Transparent about capabilities - Clearly marks simulated elements

---

🚀 Deployment

Simply upload index.html to any web server. No build process or special configuration required.

Cloudflare Pages (Recommended)

```bash
1. Fork this repository
2. Go to Cloudflare Pages dashboard
3. Connect your GitHub repository
4. Set build command to empty
5. Set build output directory to /
6. Deploy
```

Netlify/Vercel

· Same as above - static HTML deployment
· No special configuration needed

---

🔒 Security Considerations

· 🔐 No sensitive data collection
· 🌐 No external API calls
· 🍪 No cookies set
· 💾 No persistent storage
· 👁️ All code visible and auditable

---

📄 License

MIT License - feel free to use, modify, and distribute with attribution.

---

🙏 Credits

Created as a legal alternative to "hellpot" pages. Designed to intimidate without making false claims or engaging in unethical practices.

---

🖼️ Screenshot

screenshot.png

Replace with actual screenshot if available

🔗 Live Demo

View Live Demo

---

⚖️ Disclaimer

This tool is for educational and decorative purposes only. It simulates security infrastructure but does not provide actual security. Use responsibly and in compliance with all applicable laws and regulations.

---

<div align="center">

Made with ❤️ for the cyberpunk aesthetic community

STATUS: ACCESS_REJECTED • VERSION: 4.2.1 • RETURN_CODE: 403

</div>
