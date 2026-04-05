# Javid Mougamadou – Resume Website

This is my personal resume website, built with [Hugo](https://gohugo.io/) using the [PaperMod theme](https://github.com/adityatelange/hugo-PaperMod).

## 🚀 Features

- 📄 Clean resume-style homepage
- 🌙 Light/dark mode toggle
- 🔍 SEO-friendly metadata
- ⚡ Fast and static with Hugo
- 🔗 Social links (GitHub, Stack Overflow, etc.)

## 📁 Project Structure

```
.
├── config.yml (or config.toml)   # Hugo site configuration
├── content/                      # Resume pages and content
├── static/                       # Static assets (images, icons)
├── themes/                       # PaperMod theme
└── ...                           # Other Hugo project files
```

## 🛠️ Requirements

- [Go](https://golang.org/) (for installing Hugo, optional)
- [Hugo](https://gohugo.io/getting-started/installing/) v0.87.0 or higher

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Initialize the PaperMod theme as a submodule (if not already)
git submodule update --init --recursive
```

## 🔧 Local Development

```bash
# Run a local development server
hugo server -D
```

- The site will be live at: `http://localhost:1313`

## 🏗️ Build for Production

```bash
# Generate the public/ directory with the built site
hugo --minify
```

- The static site will be output to the `public/` folder.
- You can deploy it to any static hosting service (e.g., Netlify, GitHub Pages, Vercel, etc.).

## 📷 Customize OpenGraph & Social Image

Replace the placeholder image path in `config.yml`:

```yaml
images: ["/images/og-image.png"]
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to fork or adapt this resume template for your own portfolio.

---

## Contact

**Contact :** **Javid Mougamadou** — [Site web](https://javid-mougamadou.pro/) · [GitHub](https://github.com/javid-mougamadou) · [LinkedIn](https://www.linkedin.com/in/mougamadoujavid/) · [Discord](https://discord.gg/8rK6CKGb) · [Email](mailto:javid.mougamadou2@gmail.com)
