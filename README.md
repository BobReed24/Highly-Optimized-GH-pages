# Highly Optimized GitHub Pages

A minimal, highly optimized template for deploying static content to GitHub Pages with automated CI/CD workflows.

## Overview

This repository provides a streamlined setup for hosting static websites on GitHub Pages. It uses GitHub Actions to automatically deploy your content whenever changes are pushed to the main branch.

## Features

- **Zero Configuration**: Works out of the box with GitHub Pages
- **Automated Deployment**: Automatic deployment via GitHub Actions workflow
- **Minimal Overhead**: No build tools or dependencies required
- **Fast Deployment**: Optimized workflow for quick deployments
- **Flexible**: Deploy any static content (HTML, CSS, JavaScript, images, etc.)

## Getting Started

### Prerequisites

- A GitHub account
- GitHub Pages enabled for your repository

### Setup

1. **Fork or clone this repository**
   ```bash
   git clone https://github.com/BobReed24/Highly-Optimized-GH-pages.git
   cd Highly-Optimized-GH-pages
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Set Source to "GitHub Actions"

3. **Add your static content**
   - Add your HTML, CSS, JavaScript, and other static files to the repository
   - Commit and push to the `main` branch

4. **Automatic Deployment**
   - The GitHub Actions workflow will automatically deploy your content
   - Your site will be available at `https://<username>.github.io/<repository-name>/`

## Workflow

The repository includes a GitHub Actions workflow (`static.yml`) that:
- Triggers on every push to the `main` branch
- Can be manually triggered from the Actions tab
- Uploads the entire repository as a static artifact
- Deploys to GitHub Pages automatically

## Usage

Simply add your static files to the repository and push to the `main` branch. The workflow will handle the rest!

### Example Structure

```
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── images/
│   └── logo.png
├── LICENSE
├── README.md
└── static.yml
```

## Manual Deployment

You can also trigger a deployment manually:
1. Go to the "Actions" tab in your repository
2. Select "Deploy static content to Pages"
3. Click "Run workflow"

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Acknowledgments

- Built with GitHub Actions
- Powered by GitHub Pages
