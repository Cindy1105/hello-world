# Descripstion of how to run your GitHub Actions locally
```markdown
1. Reasons to do that: For fast feedbacks and local task runner.
2. How does it work: It uses the Docker API to either pull or build the necessary images, as defined in your workflow files and finally determines the execution path based on the dependencies that were defined. 
3. Installation: To install with Homebrew, run: brew install nektos/tap/act
4. Runners: GitHub Actions offers managed virtual environments for running workflows. In order for act to run your workflows locally, it must run a container for the runner defined in your workflow file.
