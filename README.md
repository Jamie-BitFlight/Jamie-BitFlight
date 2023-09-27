# Jamie Nelson
🌐 New Haven, Connecticut, USA  

---

### 👋 About Me

Passionate about shaping the nexus of development and operations, I bring over 10 years of hands-on experience in CI/CD pipelines, Infrastructure as Code (IaC), and cloud automation. My trajectory through leading enterprise environments has nurtured my expertise in software development, infrastructure management, and team leadership.

---

### 🔍 Expertise

- **CI/CD & Application Development Lifecycle:** Deep understanding of end-to-end CI/CD practices, right from code commits to deployment, leveraging tools like GitHub Actions, Jenkins, and Jira.
  
- **Infrastructure as Code (IaC):** Proficient in Terraform and Packer, ensuring seamless, consistent, and scalable infrastructure deployments, especially on AWS Cloud.

- **Languages:** Well-versed in multiple languages such as Typescript, Javascript, Python, Java, C/C++, Groovy, Perl, and Bash, allowing me to understand and bridge the needs of developers and operations.

- **Linux Administration:** Comprehensive expertise in Linux administration, ensuring optimized, secure, and stable environments for application deployments.

- **Cloud & Automation:** Skilled in AWS infrastructure automation and containerization practices, driving scalability, efficiency, and robustness in application rollouts.

- **Distributed Logging Systems:** Experienced in implementing and managing distributed logging systems, facilitating effective monitoring, and debugging capabilities.

- **Agile Framework:** Firm believer in Agile methodologies, fostering a dynamic, responsive, and collaborative environment.

---

## 📂 Repositories

### 🔧 CI/CD Pipeline / DevOps Utilities Repos

A comprehensive set of pipelines, integrating GitHub Actions, Jenkins, and Jira for a seamless application development lifecycle.

- #### A GitHub Action's README.md generator CLI tool
  🔗[bitflight-devops/github-action-readme-generator](https://github.com/bitflight-devops/github-action-readme-generator)
  
    Maintain a current README.md with content from the action.yml file
    This is a CLI tool and GitHub Action that reads in the details from a GitHub Action's `action.yml` file and updates the `README.md` file with the `name`, `description`, `usage`, `inputs`, `outputs`, and examples of the action. Configuration can be provided via a `.ghadocs.json` file stored in the root directory of the Action's repository, via the command line when using the cli, or via the `with:` section of this Action.
    This tool uses markdown comments as delimiting tokens within the `README.md` file to determine where to place the generated content.
- #### A GitHub Action for transitioning Jira issue state
  🔗[bitflight-devops/github-action-jira-transition-manager](https://github.com/bitflight-devops/github-action-jira-transition-manager)
  
    This GitHub Action will transition the list of Jira issues provided between states, or it will display the available transitions and the current issue state. i.e. move an issue state from *In Progress* -> *Ready For Review*
- #### A GitHub Action for finding and presenting Jira issues in Pull Requests
  🔗[bitflight-devops/github-action-jira-find-issue-keys](https://github.com/bitflight-devops/github-action-jira-find-issue-keys)
  
    This GitHub Action will find the issue keys in the GitHub event, from a commit, between two branches or tags, or from the commits within the current pull request and return them as a comma separated list. 
    It also optionally allows you to:
    - Update the current Pull Request title to include the Jira issue keys that it finds
    - Update the Pull Request body to include a list of Jira Issues that include the Issue name with a link to the Jira issue itself, its state and summary.
- #### a CLI, GitHub Action, and Shell plugin that provides library of shell functions
  🔗[bitflight-devops/shell-scripts](https://github.com/bitflight-devops/shell-scripts)
  
    A growing library of shell functions that strives to be cross platform (mac, linux) and cross shell (bash, zsh, sh)
    ##### Libraries included cover:
    - **GitHub Core Functions** - creates single commands for interacting with GitHub and GitHub actions
    - **AWS Elastic Beanstalk Functions** - creates functions for controlling, deploying, logging, swapping, and building AWS Elastic Beanstalk environments
    - **General Shell Utility Functions** - creates functions for simplifying and clarifying complex shell commands
    - **Color and Emoji Variables** - creates shell environment variables for controlling the color of text, and displaying or escaping unicode emojis
    - **Java Functions** - creates functions for managing versioning and tagging in a pom file
    - **Log Functions** - creates a standard set of logging functions for streaming logs to console, or files, or annotated for GitHub Actions, includes timestamping, file and function tracebacks, and colorizing.
    - **OSX Utiility Functions** - creates functions that assist with downloading, fixing security issues, and installing scripts
    - **Remote Utility Functions** - creates functions that simplify downloading or streaming files across multiple operating systems, as well as ssh utilities for creating or connecting to bastion hosts and streaming files via those hosts, connecting to mysql servers, and streaming data back to those servers
    - **String Functions** - creates string handling functions for modifying text such as changing it to upper or lower case, trimming whitespace, or performing regex matching or extracting
    - **System Functions** - creates functions that help manage OS configuration, such as gracefully updating the PATH variable, modifying dot files and rc files in a non destructive way, checking for sudo access, running commands that can automatically use sudo as required, installing and caching packages via the package managers pip, yum, apt, brew, and mpm in the most performant way possible
    - **Tracing Functions** - creates functions that allow for toggling tracing on and off for shell debugging
    - **Yaml Functions** - creates functions for parsing and extracting data from yaml files
- #### A GitHub Action for updating a Jira Issue Fixversion, or for updating the GitHub Milestone to match the FixVersion of the issue
  🔗[bitflight-devops/shell-scripts](https://github.com/bitflight-devops/github-action-jira-issues-fixversion-manager)

  This action will add the supplied list of FixVersions to the list of Jira Issue Keys, or retrieve the current FixVersions from Jira.
  This action is useful when a PR is merged to the main branch, and the main branch version is incrimented, and other open
  
- 🌐 **Terraform IaC Repo**: Templates and modules for scalable and maintainable AWS infrastructure deployments.
  
- 🐳 **Containerization Repo**: Dockerfiles and Kubernetes configurations for various application setups.

---

### 🌱 Current Learning Goals

- Dive deeper into next-gen container orchestration platforms.
- Advance my understanding of multi-cloud strategies.

---

### 🤝 Connect with Me

- **LinkedIn:** [linkedin.com/in/jamie-nelson-director-cloud-platform-integration](https://www.linkedin.com/in/jamie-nelson-director-cloud-platform-integration/)

---

_Feel free to fork, star, or open issues in my repositories. Always open to collaboration and new ideas!_
