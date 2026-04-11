# ICON Workshop Website

[![Jekyll Build](https://github.com/workshop-icon/workshop-icon.github.io/actions/workflows/jekyll.yml/badge.svg)](https://github.com/workshop-icon/workshop-icon.github.io/actions/workflows/jekyll.yml)
[![GitHub Pages](https://img.shields.io/badge/docs-GitHub%20Pages-blue.svg)](https://workshop-icon.github.io)

This repository contains the source code for the landing page of the **ICON Workshop** series: **IoT and Cyber-Physical Systems in the Edge–Cloud Continuum**.

The website is built using [Jekyll](https://jekyllrb.com/) and is hosted on [GitHub Pages](https://pages.github.com/).

## 🌐 Live Website

The website is accessible at: [https://workshop-icon.github.io](https://workshop-icon.github.io)

## 📅 Workshop Editions

- **[2026 Edition: 1st ICON Workshop](https://workshop-icon.github.io/2026)** — Stay tuned for more details!

---

## 🚀 Local Development

To run the website locally for development and testing, follow these steps:

### Prerequisites

- **Ruby** (v2.7 or higher recommended)
- **Bundler** (`gem install bundler`)

### Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/workshop-icon/workshop-icon.github.io.git
    cd workshop-icon.github.io
    ```

2.  **Install dependencies:**
    ```bash
    bundle install
    ```

3.  **Run the Jekyll server:**
    ```bash
    bundle exec jekyll serve
    ```

4.  **View the site:**
    Open [http://localhost:4000](http://localhost:4000) in your browser.

---

## 🏗️ Project Structure

- `index.md`: The main landing page.
- `_config.yml`: Jekyll configuration settings.
- `_layouts/`: Templates for different page types.
- `_includes/`: Reusable HTML components.
- `_sass/`: CSS/Sass styles.
- `assets/`: Images, scripts, and other static files.
- `history.md`: Historical information about the workshop.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to update content, fix a bug, or improve the design:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/improvement`).
3.  Commit your changes (`git commit -am 'Add some improvement'`).
4.  Push to the branch (`git push origin feature/improvement`).
5.  Create a new Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🛠️ Troubleshooting

### Jekyll Version Mismatch
If you encounter an error like `Could not find gem 'jekyll (~> 4.2.1)'` when running `bundle exec jekyll serve`, it's because your local environment has a newer version of Jekyll than specified in the `Gemfile`.

To fix this, you can:
1. Update your dependencies:
   ```bash
   bundle update jekyll
   ```
2. Or, run with whatever version is available (not recommended for production consistency):
   ```bash
   bundle exec jekyll serve
   ```
   (Note: `bundle install` should usually handle this if versions are compatible).
