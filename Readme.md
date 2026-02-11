# Electric & Acoustic Hearing Lab Website

Official website for the Electric & Acoustic Hearing Lab at the University of South Alabama, directed by Dr. Niyazi Ömer Arslan.

🔗 **Live site:** [https://eahlab.com](https://eahlab.com)

---

## 🧬 About the Lab

The Electric & Acoustic Hearing Lab investigates the neural basis of auditory perception to transform hearing restoration for cochlear implant users. Our research spans:

- **Neural Health Assessment** — Developing objective measures of auditory nerve survival
- **Focused Stimulation** — Testing current focusing strategies for enhanced spectral resolution
- **Cortical Plasticity** — Mapping auditory cortex reorganization patterns

---

## 🛠️ Tech Stack

- **Static Site Generator:** [Hugo](https://gohugo.io/) v0.139+
- **Theme:** [HugoBlox](https://hugoblox.com/) Research Group
- **Hosting:** [Netlify](https://www.netlify.com/)
- **CMS:** Decap CMS (optional)

---

## 📁 Project Structure

```
eah-lab-website/
├── assets/
│   └── scss/
│       └── custom.scss          # Custom styles (EAHL branding)
├── config/
│   └── _default/
│       ├── hugo.yaml            # Main Hugo config
│       ├── params.yaml          # Site parameters
│       ├── menus.yaml           # Navigation menus
│       ├── languages.yaml       # Language settings
│       └── module.yaml          # Hugo modules
├── content/
│   ├── authors/                 # Team member profiles
│   ├── publication/             # Research publications
│   ├── post/                    # News & blog posts
│   ├── research.md              # Research overview page
│   ├── contact.md               # Join Us / Contact page
│   └── privacy.md               # Privacy policy
├── layouts/
│   └── partials/
│       ├── custom_head.html     # Custom <head> elements
│       └── custom_footer.html   # Custom footer
├── static/
│   ├── robots.txt               # SEO robots file
│   └── media/                   # Images & assets
├── netlify.toml                 # Netlify deployment config
└── README.md
```

---

## 🚀 Local Development

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) v0.139.0+
- [Go](https://golang.org/dl/) 1.21+
- [Node.js](https://nodejs.org/) 20+ (optional, for Decap CMS)

### Setup

```bash
# Clone the repository
git clone https://github.com/thegodparticle/eah-lab.git
cd eah-lab

# Install Hugo modules
hugo mod get -u
hugo mod tidy

# Start development server
hugo server --disableFastRender
```

Visit `http://localhost:1313` to view the site.

### Build for Production

```bash
hugo --gc --minify
```

Output will be in the `public/` directory.

---

## 🎨 Design System

### Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Navy | `#0a1628` | Headings, dark backgrounds |
| Cream | `#faf8f5` | Page backgrounds |
| Teal (Accent) | `#4a90a4` | Links, buttons, highlights |
| Coral | `#e07a5f` | Accents, section dividers |
| Sage | `#6b8f71` | Secondary accents |

### Typography

- **Headings:** Playfair Display (serif)
- **Body:** Source Sans 3 (sans-serif)

---

## 📝 Content Management

### Adding a Publication

Create a new folder in `content/publication/`:

```bash
hugo new publication/my-new-paper/index.md
```

### Adding a Team Member

Create a new folder in `content/authors/`:

```bash
hugo new authors/firstname-lastname/_index.md
```

### Adding a News Post

```bash
hugo new post/my-news-post/index.md
```

---

## 🌐 Deployment

The site automatically deploys to Netlify when changes are pushed to the `main` branch.

### Manual Deploy

```bash
# Build
hugo --gc --minify

# Deploy to Netlify (if using CLI)
netlify deploy --prod
```

---

## 📄 License

© 2026 Electric & Acoustic Hearing Lab, University of South Alabama. All rights reserved.

---

## 📧 Contact

**Dr. Niyazi Ömer Arslan**  
Assistant Professor & Lab Director  
Department of Speech Pathology & Audiology  
University of South Alabama

📩 [narslan@southalabama.edu](mailto:narslan@southalabama.edu)  
🔬 [Google Scholar](https://scholar.google.com/citations?user=cTzzqvMAAAAJ)