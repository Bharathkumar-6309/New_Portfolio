# New_Portfolio
A highly professional, visually stunning personal portfolio website for a Full Stack Developer specializing in MERN stack and AI/ML systems.


📸 Preview
┌─────────────────────────────────────────────────────┐
│  BK.                              ☀  [Hire Me →]   │
├─────────────────────────────────────────────────────┤
│                                                     │
│  ● Open to opportunities · Hyderabad, IN            │
│                                                     │
│  Bharath Kumar                                      │
│  Reguchinthala                  ◯ ─ ─ ─            │
│                                / geometric  \       │
│  Full Stack Developer         /   SVG float  \      │
│  crafting intelligent        ◯─────────────────◯   │
│  web experiences...                                 │
│                                                     │
│  [→ Hire Me]   [⬡ View Projects]                   │
│                                                     │
│  10+           6+          5+                       │
│  Internships   Domains     Projects                 │
│                                                     │
└─────────────────────────────────────────────────────┘

✨ Features
🎨 Design

Dark-first aesthetic with neon green (#00ffb3) accent palette
Glassmorphism cards with subtle backdrop blur
Animated particle network canvas background
Custom cursor with magnetic hover effects and blend mode
Dark / Light mode toggle with smooth transitions
Scroll reveal animations on every section
Premium typography: Syne + DM Mono + DM Sans

🗂 Sections
#SectionDescription01HeroName, title, tagline, animated badge, stats counter, CTA buttons02AboutPersonal story, skill chips categorized by domain03Skills4 category cards with animated progress bars04Projects6 project cards with hover lift, tags, and links05ExperienceFull timeline of 8+ internships with role tags06EducationB.Tech, Intermediate, SSC cards07CertificationsAWS, MERN, JavaScript, Full Stack certs08TerminalInteractive CLI — type real commands09ContactSplit layout with info card + contact form
⚡ Interactive Terminal
Type these commands in the terminal section:
bashwhoami      # About Bharath Kumar
skills      # List all technical skills
projects    # Show all 6 featured projects
experience  # Full work history
stack       # Current tech stack (JSON)
contact     # Contact information
status      # Availability status
help        # List all commands
clear       # Clear terminal output

🛠 Tech Stack
HTML5     — Semantic structure
CSS3      — Custom properties, animations, glassmorphism
JavaScript — Vanilla JS (no frameworks required)
Canvas API — Particle network background
Google Fonts — Syne, DM Mono, DM Sans

Zero dependencies. No npm, no build step, no frameworks. Just open the file.


📁 File Structure
portfolio/
│
├── portfolio.html      ← Single file — entire portfolio lives here
└── README.md           ← You are here
This is an intentionally single-file architecture for maximum portability. The entire portfolio — HTML structure, CSS styles, and JavaScript logic — lives in one file that can be opened in any browser instantly.

🚀 Getting Started
Option 1 — Open Locally
bash# Just double-click portfolio.html
# Or open with your browser directly
open portfolio.html          # macOS
start portfolio.html         # Windows
xdg-open portfolio.html      # Linux
Option 2 — Local Dev Server
bash# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using VS Code
# Install "Live Server" extension → Right click → Open with Live Server
Then visit http://localhost:8000

☁️ Deployment
GitHub Pages (Free — Recommended)
bash# 1. Create a new repo named: bharathkumar-6309.github.io
# 2. Upload portfolio.html → rename it to index.html
# 3. Go to Settings → Pages → Source: main branch → Save
# 4. Live at: https://bharathkumar-6309.github.io
Netlify (Drag & Drop)

Go to netlify.com/drop
Drag your portfolio.html file onto the page
Get an instant live URL — done in seconds


✏️ Customization Guide
Update Personal Info
Open portfolio.html and search for these values:
What to changeSearch forName & taglineBharath Kumar ReguchinthalaEmail addressreguchinthalabharathkumar@gmail.comLinkedIn URLlinkedin.com/in/bharathkumar-reguchinthalaGitHub URLgithub.com/Bharathkumar-6309LocationHyderabad, Telangana, India
Change Accent Color
Find :root in the CSS and update:
css:root {
  --accent: #00ffb3;   /* ← change this to any color */
}
Add a Real Project
Find the .projects-grid section and copy a .project-card block. Update:

project-thumb background gradient
project-tags tech stack chips
project-title and project-desc
project-link href to your GitHub / live URL

Add Resume Download
Inside the Hero section, add:
html<a href="your-resume.pdf" download class="btn-secondary">⬇ Download CV</a>

📊 Performance

✅ No external JS libraries — instant load
✅ Google Fonts — only 3 font families, preconnect enabled
✅ CSS animations — GPU-accelerated transforms only
✅ Canvas particles — lightweight, requestAnimationFrame-based
✅ IntersectionObserver — scroll reveals without scroll event overhead
✅ Mobile-first responsive — works on all screen sizes


🗺 Roadmap / Improvement Ideas

 Add downloadable resume PDF button in hero
 Connect contact form to Formspree or EmailJS
 Add real project screenshots / thumbnails
 Add meta OG tags for LinkedIn / Twitter card previews
 Add sitemap.xml and robots.txt for SEO
 Add Google Analytics or Plausible for visitor tracking
 Expand terminal with echo, ls, cat projects.json commands
 Add a blog section powered by a headless CMS


📬 Contact
Bharath Kumar Reguchinthala

📧 Email: reguchinthalabharathkumar@gmail.com
💼 LinkedIn: (https://www.linkedin.com/in/bharath-kumar-reguchinthala-0817b2293?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
🐙 GitHub: github.com/Bharathkumar-6309
📍 Location: Hyderabad, Telangana, India


📄 License
This project is open source and available under the MIT License.
Feel free to fork, customize, and use it as your own portfolio base — just give a ⭐ if it helped!
