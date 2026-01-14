# Cloud, Unclouded

> A clean, developer-focused blog exploring **Cloud Computing**, **Data Engineering**, and the Google Cloud ecosystem.
> Built with Hugo and hosted on Firebase Hosting, with CI/CD via GitHub Actions.

---

## 🚀 Features

* **Static Site Generator:** Hugo for fast, lightweight builds
* **Theme:** Blowfish — clean, minimal, with sidebar navigation
* **Search:** Built-in search for easy content discovery
* **Sidebar Navigation:** Easy browsing across blog posts, projects, and about pages
* **CI/CD:** Automatic deployment via GitHub Actions to Firebase Hosting
* **Responsive & Dark Mode:** Modern, readable design for all devices

---

## 🌐 Live Site

[https://cloud-unclouded.web.app](https://cloud-unclouded.web.app)

---

## 💻 Local Development

1. **Clone the repository**

```bash
git clone https://github.com/Suelybuque/Cloud_Unclouded.git
cd Cloud_Unclouded
```

2. **Install Hugo**

```bash
npm install -g hugo
```

3. **Run locally**

```bash
hugo server -D
```

Open your browser at [http://localhost:1313](http://localhost:1313) to preview the site.

4. **Build for production**

```bash
hugo
```

This outputs the static site to the `public/` directory, ready to deploy.

---

## 📦 Deployment

This blog is deployed to Firebase Hosting using GitHub Actions:

* Every push to `main` automatically builds and deploys the site
* Pull Requests generate preview deployments for review

---

## 📝 Project Structure

```
├── archetypes/       # Hugo archetypes for posts
├── content/          # Markdown blog posts
├── layouts/          # Theme overrides
├── static/           # Static assets (images, css, js)
├── themes/           # Hugo theme (Blowfish)
├── config.toml       # Site configuration
└── public/           # Generated static files (ignored in Git)
```

---

## 💡 Contributing

1. Fork the repo
2. Create a new branch for your feature/fix
3. Submit a pull request
4. CI/CD will deploy previews automatically

---

## 📚 Future Plans

* Add **Mermaid.js** for architecture diagrams
* Implement **newsletter subscription**
* Write long-form articles about **Data Engineering in GCP**
* Add a **custom domain** (`suely.dev`)

---

## 🔗 Contact

* GitHub: [@Suelybuque](https://github.com/Suelybuque)
* LinkedIn: [Suely Buque](https://www.linkedin.com/in/suelybuque/)
* Email: [your-email@example.com](mailto:scbuque@gmail.com)

---

> Built with ❤️ by Suely Buque
