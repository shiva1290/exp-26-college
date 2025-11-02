# GitHub Actions CI/CD Pipeline

This project demonstrates continuous integration and deployment using GitHub Actions. The workflow automatically triggers on every push to the main branch, setting up Node.js environment, installing dependencies, running tests, and building the project. The build artifacts are then deployed to GitHub Pages for hosting. The workflow configuration is defined in the .github/workflows/main.yml file, which orchestrates the entire pipeline. To enable GitHub Pages deployment, ensure the repository settings have GitHub Pages enabled with the gh-pages branch as the source. The pipeline ensures code quality through automated testing before deployment.

