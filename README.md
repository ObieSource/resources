## **Introduction**
Welcome to ObieSource! This guide is designed to help you navigate the world of open-source contributions, whether you're contributing to a club project, your own project, or a broader open-source initiative. Following these guidelines will ensure that your contributions are effective, well-documented, and aligned with open-source best practices.

## **Table of Contents**
1. [General Documentation Guidelines](#general-documentation-guidelines)
2. [Best Practices for Coding and Collaboration](#best-practices-for-coding-and-collaboration)
3. [How to Contribute to Open Source](#how-to-contribute-to-open-source)
4. [Resources and Learning Materials](#resources-and-learning-materials)
5. [Contact and Support](#contact-and-support)

## **General Documentation Guidelines**

### **1. README.md**
- **Purpose:** The README.md file is the first thing people see when they visit your project. It should provide a clear overview of the project.
- **Contents:**
  - **Project Title and Description:** A brief introduction to what the project does and its goals.
  - **Installation Instructions:** Step-by-step guide on how to install and set up the project locally.
  - **Usage:** Basic instructions on how to use the project.
  - **Contributing:** Guidelines on how others can contribute (I would put to-dos in the "Issues" tab on GitHub).

### **2. Code Documentation**
- **Inline Comments:** Write comments in your code where necessary to explain complex logic or important decisions. Don't overdo it, but generally speaking its better to have more than less.
- **Docstrings:** For functions, classes, and modules, include docstrings that describe their purpose, parameters, and return values. Follow a consistent style according to the language or framework you're working with.
- **Examples:** If applicable, provide example scripts or usage examples in the documentation to demonstrate how to use your code.

### **3. Additional Documentation**
- For more complex projects, you might want to include more robust documentation. This can include:
  - **Architecture Overview:** Diagrams or descriptions of the project's architecture.
  - **API Documentation:** Detailed documentation for APIs, including endpoints, request formats, and expected responses.
  - **Contribution Guidelines:** Extended guidelines on contributing, including coding standards, branching strategies, and testing protocols.

### **4. Consistency and Clarity**
- **Clarity:** Write documentation that is easy to understand for newcomers and experienced developers alike.
- **Consistency:** Use consistent terminology, formatting, and style throughout your documentation. Consider using a linter or style guide for markdown files.

## **Best Practices for Coding and Collaboration**

### **1. Version Control with Git**
- **Branching Strategy:** Experiment with branching strategies like Git Flow or feature branches. Main branches (e.g., `main`, `master`) should always be stable. If you're just starting out or you're working on a smaller project, just committing to the main branch is ay okay! 
- **Commit Messages:** Write clear, concise commit messages. You could try following a format like: `feat: add user authentication`, `fix: resolve login bug`. Or you could always to do the classic `the war is finally over and the bug is squashed. I can finally GRIEVE`, but that wouldn't be as clear (*I apologize to all my fellow collaborators*).
- **Pull Requests:** Make pull requests for merging changes into main branches. Ensure your PR includes a clear description of the changes and references any relevant issues. Link any documentation you referenced in making your PR.

### **2. Code Quality**
- **Code Reviews:** Always request code reviews for pull requests. This ensures code quality and knowledge sharing.
- **Testing:** Write unit tests and integration tests for your code. Ensure that tests pass before merging changes.
- **Linting:** Use linters to enforce coding standards and detect errors (e.g., ESLint for JavaScript, Pylint for Python).

### **3. Collaboration and Communication**
- **Discussion Channels:** Reach out through the ObieSource discord or through private messages to discuss ideas, problems, and updates.
- **Documentation of Decisions:** Document important decisions made during discussions to ensure that everyone is on the same page.
- **Respect and Inclusivity:** Always communicate respectfully and inclusively. Encourage a welcoming environment for contributors of all experience levels.

## **How to Contribute to Open Source**

### **1. Finding a Project**
- **Club Projects:** Start by contributing to ObieSource projects. These are beginner-friendly and have mentors to guide you. You can begin with the [club website, which has a step-by-step contribution guide!](https://github.com/ObieSource/obiesource.github.io?tab=readme-ov-file#contribution-guide)
- **External Projects:** Explore GitHub, GitLab, or other platforms to find open-source projects that match your interests and skills. Look for repositories with labels like `good first issue` or `help wanted`. Even if repositories don't have these labels, reaching out to the main contributors should get you started.

### **2. Understanding the Project**
- **Read the Documentation:** Before contributing, thoroughly read the project’s README, contribution guide, current issues, and any other documentation.
- **Set Up Locally:** Follow the installation instructions to set up the project locally. Familiarize yourself with the codebase and its functionality.
- **Engage with the Community:** Join the project’s communication channels, introduce yourself, and ask any clarifying questions. If there aren't any servers to join, the main contributors should have some form of contact listed on their profiles for you to reach out to.

### **3. Making Your First Contribution**
- **Create a Fork:** Fork the repository to your GitHub account and clone it to your local machine.
- **Start Small:** Begin with small tasks like fixing typos, updating documentation, or addressing minor issues.
- **Implement Changes:** Start noticing the bigger issues and implement their solutions. Consider the organization of your changes and whether you should make your changes in a new branch. For most smaller scale projects, working on the main branch is okay, but never hurts to get into this practice. Ensure your code is well-documented and tested.
- **Submit a Pull Request:** Push your commit to your fork, and submit a pull request (PR) to the original repository. Write a clear description of your changes and reference relevant issues.

### **4. Continuous Contribution**
- **Regular Contributions:** Continue contributing by picking up more complex issues, proposing new features, or helping with documentation and code reviews.
- **Engage with the Community:** Attend virtual meetings, participate in discussions, and collaborate with other contributors (this is an awesome and authentic way to network!)
- **Mentorship:** Once you’re comfortable, consider mentoring new contributors or taking on a leadership role in a project.

## **Resources and Learning Materials**

### **1. Learning Git and GitHub**
- **Git Documentation:** [Git Documentation](https://git-scm.com/doc)
- **Pro Git Book:** [Pro Git](https://git-scm.com/book/en/v2)
- **GitHub Learning Lab:** [GitHub Learning Lab](https://lab.github.com/)
- See `gitbasics.md` for more git learning materials!

### **2. Open Source Contribution**
- **First Contributions:** [First Contributions](https://github.com/firstcontributions/first-contributions) - A guide to making your first open-source contribution. You could also making [adding yourself as a member to your club website your first contribution!](https://github.com/ObieSource/obiesource.github.io?tab=readme-ov-file#contribution-guide)
- **Up For Grabs:** [Up For Grabs](https://up-for-grabs.net/) - A site that aggregates beginner-friendly issues from various open-source projects.
- **Open Source Guides:** [Open Source Guides](https://opensource.guide/) - Guides on how to contribute to open-source projects.
- For more open source materials, see `opensource.md`

### **3. Coding and Documentation Standards**
- **Google Style Guides:** [Google Style Guides](https://google.github.io/styleguide/)
- **Sphinx Documentation:** [Sphinx Documentation](https://www.sphinx-doc.org/en/master/)

For any additional resources, there are guides posted elsewhere in this repository. But this is a good start. 


## **Contact and Support**
If you have any questions, need help, or want to discuss a project, reach out via our Discord server or email [obsource@oberlin.edu](mailto:obsource@oberlin.edu).

We’re excited to see your contributions and help you grow as an open-source contributor!
