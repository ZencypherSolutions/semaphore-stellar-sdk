# **📚 Contributing Guide**

Thank you for being interested in contributing to the Semaphore Stellar SDK project!

Feel welcome and read the following sections in order to know how to ask questions and how to work on something.

Please make sure you are welcoming and friendly in all of our spaces.

We're really glad you're reading this, because we need volunteer developers to help this project come to fruition.

## Issues

The best way to contribute to our projects is tackling one of the issues <a href="https://github.com/ZencypherSolutions/semaphore-stellar-sdk/issues" target="_blank">listed here</a> .

# **📌 Applying for the Issue**

When assigned, please fork the repo and create a new branch to develop your issue. Once finished, open a PR and it will be reviewed by a mantainer ASAP.

1. When picking up an issue give a brief presentation about yourself.

```
Template:
Hi, I'm [Your Name] and I'll be working on issue #[Issue Number].

I estimate this will take [Time Estimate] to complete.

This is how I would tackle this issue:
[Steps to solve issue]

```

2. **Estimated Time to Completion**: Approximate number of hours or days required to complete the task.

3. **Approach and Methodology**: Briefly outline your strategy for tackling the issue, including any relevant tools, technologies, or resources you plan to utilize.

# **🎯 Pull Request**

1. **Clone and Fork Repo**: Click the **Fork** button in the top-right corner to create a copy of the repository under your account.

    - <a href="https://github.com/ZencypherSolutions/semaphore-stellar-sdk" target="_blank"> HERE</a>

#

2. **Clone the Fork:** 
    - Clone the forked repository to your local machine by running the following command:

    ```bash
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   ```

    - Replace `YOUR_USERNAME` and `REPOSITORY_NAME` with your GitHub username and the repository name.

#

3. **Create a new branch or use the main branch:** When modifying contracts kindly make sure the formatting is correct and all tests pass successfully.

    - Create a branch name based on the type of change (e.g., `feat/name-related-issue`, `docs/name-related-issue`).

    ```
    git checkout -b branch-name
    ```
    - One of ideas on how to implement it for the branch name:

        > `docs/update-readme` or `fix/bottom-bug`.

#

4. **Commit:** Commit your changes.

    1. **git add (file-name)**
    2. **git commit -m "[type] description"**

    - Example: 
    ```
    `git add Create_Documentation`

    `git commit -m "[docs]: update documentation"`
    ```

#

5. **Push fork:** Push to your fork and submit a pull request on our `dev` branch. Please provide us with some explanation of why you made the changes you made. For new features make sure to explain a standard use case to us.

- Push your changes to your forked repository:
    ```bash
   git push origin your-branch-name
   ```
   > Replace `your-branch-name` with the name of your branch.

- Example: 

    ```bash
    `git push origin fix/bug-fix`
    ```

#

6. **Submit a Pull Request:** Submit a pull request to the `dev` branch of the Semaphore Stellar SDK repository.

    - <a href="https://github.com/ZencypherSolutions/semaphore-stellar-sdk/pulls" target="_blank"> Summit pull request</a>



# **📝 CI (Github Actions)**

We use GitHub Actions to verify if the code of your PR passes all our checks.

When you submit your PR (or later change that code), a CI build will automatically be kicked off. A note will be added to the PR, and will indicate the current status of the build.

# **📁 Commits**

You can do a regular commit by following the next:

``` [type] significant message ```

- <a href="https://www.conventionalcommits.org/en/v1.0.0/" target="_blank">Learn more about conventional commits</a>

### Type

**The type must be one of the following:**

- feat: A new feature.
- fix: A bug fix.
- docs: Documentation only changes.
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
- refactor: A code change that neither fixes a bug nor adds a feature (improvements of the code structure).
- perf: A code change that improves the performance.
- test: Adding missing or correcting existing tests.
- build: Changes that affect the build system or external dependencies (example scopes: gulp, npm).
- ci: Changes to CI configuration files and scripts (example scopes: travis, circle).
- chore: Other changes that don't modify src or test files.
- revert: Reverts a previous commit.

# **🔗 Branches**

1. There must be a `main` branch, used only for the releases.
2. There must be a `dev` branch, used to merge all the branches under it.
3. Avoid long descriptive names for long-lived branches.
4. Use kebab-case (no CamelCase).
5. Use grouping tokens (words) at the beginning of your branch names (in a similar way to the `type` of commit).
6. Define and use short lead tokens to differentiate branches in a way that is meaningful to your workflow.
7. Use slashes to separate parts of your branch names.
8. Remove your branch after merging it if it is not important.

**Examples:**

```
git branch -b docs/readme
git branch -b test/a-feature
git branch -b feat/sidebar
git branch -b fix/b-feature
```

# **🚨 Code of Conduct**

### **Contributor Covenant Code of Conduct.**

- ### **Our Pledge**

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

- ### **Our Standards**

Examples of behavior that contributes to a positive environment for our
community include:

1. Demonstrating empathy and kindness toward other people.
2. Being respectful of differing opinions, viewpoints, and experiences.
3. Giving and gracefully accepting constructive feedback.
4. Accepting responsibility and apologizing to those affected by our mistakes, and learning from the experience.


- ### **Our Responsibilities**

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

- ### **Enforcement**

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported to the community leaders responsible for enforcement at
[INSERT CONTACT METHOD]. All complaints will be reviewed and investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the reporter of any incident.

- ### **Enforcement Guidelines**

Community leaders will follow these Community Impact Guidelines in determining the consequences for any action they deem in violation of this Code of Conduct.

# **🔒 License**

MIT License

Copyright (c) 2024 ZencypherSolutions

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.