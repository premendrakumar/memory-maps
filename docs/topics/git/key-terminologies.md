# Git Key Terminologies
- [**Basic Introductory Terminologies**](#basic-terminology)
- [**Targetted Terminologies: From Beginer to Expert in `Github Actions`**](#targetted-terminologies--from-beginer-to-expert-in-github-actions)
    - [**stepwise learning plan to master GitHub and GitHub Actions**](#stepwise-learning-plan-to-master-github-and-github-actions)
    - [**set of milestones tailored to your mixed-experience team for learning GitHub Actions**](#set-of-milestones-tailored-to-your-mixed-experience-team-for-learning-github-actions)
- [**Thanksgiving: Helping sites**](#thanks-to)

# Basic Terminology
- What is a Version Control System?
    - Version control, also known as source control, is tracking and managing software code changes.
    - Famous VCS:
        - Git (Most Famous)
        - Apache SubVersion
        - Piper (Used by Google)


- Introduction to Git VCS
    - What is Git?
    - Installation of Git CLI
    - Basic Git Commands
        - Setting up Git Global Configuration


- Version Controlling with Git
    - Initializing Git Project
    - Adding Files to VCS
        - git add <FILE_PATH>
        - git add .
    - Removing Files from VCS
        - git rm <FILE_PATH>
    - Introduction to Commits
        - Committing Files
            - git commit -m "MESSAGE"
        - Staging Area
        - Logging Commit History
            - git log
            - git log --oneline
        - Reverting Back


- Git VS GitHub
    - What are Git and GitServer
    - Popular Git Servers
        - GitHub
        - GitLab
        - BitBucket
    - Git Remotes
    - Pushing and Pulling in Git
    - Self-Hosted Git Server


- Branching in Git
    - Introduction to Branching Concept.
    - Creating Branches
        - git brach <BRANCH NAME>
        - git checkout <BR_NAME>
        - git checkout -b "BR_NAME"
    - Branch Tags
        - feat/feat-name
    - Merging Branches
        - Merge
        - Rebase
    - Stashing


---

# Targetted Terminologies:  From Beginer to Expert in `Github Actions`

## stepwise learning plan to master GitHub and GitHub Actions

Here’s a **stepwise learning plan to master GitHub and GitHub Actions**, structured for developers aiming to use GitHub Actions effectively.

---

### **Step 1: Master Git and GitHub Basics**
1. **Learn Version Control with Git**
   - Install and configure Git.
   - Understand repositories, commits, branches, and merges.
   - Common commands: `git init`, `git clone`, `git add`, `git commit`, `git push`, `git pull`.

2. **Collaborating on GitHub**
   - Create and manage repositories.
   - Work with forks, pull requests, and code reviews.
   - Understand repository permissions and branch protection rules.

3. **Explore GitHub Features**
   - Learn about Issues, Discussions, and Projects for collaboration.
   - Use README.md and CONTRIBUTING.md for documentation.

---

### **Step 2: Understanding Continuous Integration (CI) and Continuous Deployment (CD)**
1. **What is CI/CD?**
   - Understand the importance of automation in software delivery.
   - Learn how CI/CD workflows improve development efficiency.

2. **CI/CD with GitHub Actions**
   - Introduction to GitHub Actions: workflows, jobs, and steps.
   - Understand triggers like `push`, `pull_request`, and `schedule`.

---

### **Step 3: Start with GitHub Actions Basics**
1. **Setting Up GitHub Actions**
   - Navigate to the `Actions` tab in a repository.
   - Use the GitHub Actions starter templates.

2. **Write Your First Workflow**
   - Create `.github/workflows/main.yml`.
   - Add a simple job, such as running `echo "Hello, GitHub Actions!"`.
   - Test and observe the workflow execution.

3. **Use Prebuilt Actions**
   - Search and integrate actions from the GitHub Marketplace.
   - Example: Use `actions/checkout` to clone the repository.

---

### **Step 4: Develop Practical Workflows**
1. **Build and Test Automation**
   - Automate builds for Java projects using Maven or Gradle.
   - Run automated tests using JUnit or other testing frameworks.

2. **Working with Secrets**
   - Add sensitive data like API keys to GitHub Secrets.
   - Use secrets in workflows securely.

3. **Matrix Builds**
   - Run jobs with multiple configurations (e.g., test on Java 8, 11, and 17).

---

### **Step 5: Create Reusable and Advanced Workflows**
1. **Reusable Workflows**
   - Build reusable workflows with `workflow_call`.
   - Use reusable workflows across multiple repositories.

2. **Advanced Features**
   - Set up caching for dependencies to speed up workflows.
   - Use artifacts to save and share build outputs.

---

### **Step 6: Write Custom GitHub Actions**
1. **Custom JavaScript Actions**
   - Learn to write GitHub Actions using JavaScript.
   - Understand `action.yml` metadata.

2. **Custom Docker Actions**
   - Create custom actions with Docker to run specialized tools.

---

### **Step 7: Integrate CI/CD Pipelines**
1. **Deploy Applications**
   - Automate deployment for Java applications (e.g., deploy to AWS or Heroku).
   - Deploy Flex applications using workflows.

2. **Integrate Monitoring and Quality Tools**
   - Use tools like SonarQube, ESLint, and unit test reporters.
   - Automate notifications with Slack or email.

---

### **Step 8: Secure and Optimize Workflows**
1. **Security Best Practices**
   - Manage access to repositories and secrets.
   - Use branch protection rules and review workflows.

2. **Optimize Workflows**
   - Reduce redundant runs with `concurrency`.
   - Use workflows insights to analyze performance.

---

### **Step 9: Explore Advanced Topics**
1. **Custom Workflows for Team Collaboration**
   - Write workflows for code reviews, release versioning, and documentation updates.

2. **GitHub Actions for Open-Source Projects**
   - Automate contributions with bots (e.g., dependabot).
   - Create reusable templates for community use.

---

This stepwise learning path ensures a strong foundation in GitHub and progresses toward advanced GitHub Actions capabilities. Let me know if you’d like more detailed examples or real-world scenarios!

## set of milestones tailored to your mixed-experience team for learning GitHub Actions

Here’s a set of milestones tailored to your mixed-experience team for learning GitHub Actions:

---

### **Beginner Milestones (For Novices)**  
1. **Introduction to GitHub Actions**
   - What is GitHub Actions?
   - Overview of CI/CD pipelines.
   - Key concepts: Workflows, Jobs, Steps, and Actions.

2. **Creating a Simple Workflow**
   - YAML basics for GitHub Actions.
   - Writing a minimal `.github/workflows/main.yml`.
   - Triggering a workflow with `push` or `pull_request` events.

3. **Using Prebuilt Actions**
   - Searching for and using community actions from the GitHub Marketplace.
   - Example: Setting up a workflow to build a simple Java project using Maven.

4. **Understanding Logs and Debugging**
   - Viewing workflow runs and interpreting logs.
   - Debugging failed workflows.

---

### **Intermediate Milestones (For Experienced Developers)**  
5. **Customizing Workflows**
   - Using environment variables and secrets.
   - Conditional workflows and matrix builds.
   - Optimizing workflow triggers (`on: [push, schedule]`).

6. **Creating Reusable Workflows**
   - Setting up reusable workflows using `workflow_call`.
   - Sharing workflows across multiple repositories.

7. **Advanced Configuration**
   - Setting up caches for Maven dependencies or node_modules.
   - Using concurrency to avoid duplicate runs.

---

### **Advanced Milestones (For Senior Developers)**  
8. **Creating Custom Actions**
   - Writing custom actions in JavaScript or Docker.
   - Publishing actions to the GitHub Marketplace.

9. **Deploying with GitHub Actions**
   - Setting up workflows for deploying Java apps to AWS/GCP/Azure.
   - Deploying Flex applications to a CI/CD environment.

10. **Securing Workflows**
    - Managing sensitive data with GitHub Secrets.
    - Implementing security best practices for workflows.

11. **Integrating Third-Party Tools**
    - Configuring tools like SonarQube for code quality analysis.
    - Automating notifications using Slack or Teams.

12. **Monitoring and Metrics**
    - Tracking workflow success and failure rates.
    - Using GitHub Actions Insights for optimization.

---

### **Final Deliverable**
Create a hands-on guide with real-world examples:
- **Basic Example:** Java project build and test using Maven.
- **Intermediate Example:** Multi-job workflow for build, test, and deploy.
- **Advanced Example:** Reusable workflows and custom action development.

--- 


----

# Thanks to
- **Git & GitHub Crash Course** [https://app.eraser.io/workspace/P96VaUsW5o0FXVOTDzHY](https://app.eraser.io/workspace/P96VaUsW5o0FXVOTDzHY)
- [**Complete Git and GitHub Tutorial for Beginners**: **Hindi**](https://www.youtube.com/watch?v=RDxQEzXN8AU)
    - <span style="color:red">Abusive Language: Not Recommended</span>
- [**Master Git & GitHub in One Video: Learn the fundamentals with a Desi twist!**: **Hindi**](https://www.youtube.com/watch?v=YbX_5FTOgL8)
- [**Complete git and Github course in Hindi**](https://www.youtube.com/watch?v=q8EevlEpQ2A)
- [**Complete Git and GitHub Tutorial for Beginners**](https://www.youtube.com/watch?v=Ez8F0nW6S-w)
