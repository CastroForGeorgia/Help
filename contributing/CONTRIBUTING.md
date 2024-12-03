# Contributing Guidelines

Thank you for considering contributing to our project! We welcome contributions from the community to help make this resource as comprehensive and useful as possible.

## How to Contribute

- **Fork the Repository**: Click on the "Fork" button at the top right of the repository page to create a copy in your GitHub account.
- **Clone the Repository**: Clone the forked repository to your local machine.
  ```bash
  git clone https://github.com/your-username/Help.git
  ```
- **Create a New Branch**: Create a branch for your changes.
  ```bash
  git checkout -b my-new-feature
  ```
- **Add Your Contributions**:
  - Use the provided scripts or templates to add new resources, links, or data.
  - Follow the directory structure and naming conventions.
- **Commit Your Changes**:
  ```bash
  git add .
  git commit -m "Add new resource on [topic]"
  ```
- **Push to GitHub**:
  ```bash
  git push origin my-new-feature
  ```
- **Submit a Pull Request**: Go to your forked repository on GitHub and click on "Compare & pull request".

## Guidelines

- **Use Templates**: Please use the templates provided in `contributing/templates` for consistency.
- **Run Linters**: Run the Markdown linter before submitting your pull request.
  ```bash
  markdownlint resources/**/*.md
  ```
- **Write Clear Commit Messages**: Describe your changes in detail.
- **Check for Duplicates**: Ensure the content you're adding doesn't already exist.

---

Thank you for your contributions!
