# ***DevOps Project***
A DevOps demo project using Git best practices. This project demonstrates a clean branching strategy and collaboration workflow using GitHub.

### ***Project Description***
This project showcases how to work efficiently with Git branches (`main`, `dev`, `feature/*`) and automate deployments using GitHub Actions and SSH to AWS instances.

### ***Setup Instructions***
  1. Clone the repository: git clone https://github.com/asmat72/devops-project.git  /cd devops-project
  2. Create and switch to feature branches for new development.
  3. Push changes and create pull requests to merge `feature` branches into "dev".
  4. After testing in `dev`, merge `dev` into `main` to deploy production-ready code.

### ***Branching Strategy***
  - "main" : Production-ready stable code.
  - "dev" : Integration branch where features are tested before going to main. 
  - "feature/*" :  Branches for new features and experiments.

### ***How to Contribute***
  1. Fork the repo and clone it locally.
  2. Create a new branch from "dev": git checkout -b feature/your-feature-name dev
  3. Make your changes, commit, and push:
     git add .
     git commit -m "Add a clear description of your change"
     git push origin feature/your-feature-name
  4. Open a pull request from your feature branch into `dev` on GitHub.
  5. Collaborate, review, and once approved, merge your changes.
  6. Keep your feature branches up to date with `dev` by pulling regularly.
  7. After all features are tested, create a pull request to merge "dev" into "main"
