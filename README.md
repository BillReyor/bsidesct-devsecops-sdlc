![Bsides Logo 2024 Logo](bsides_ct_logo.png "BSides Logo")

# DevSecOps and Securing your SDLC 

This repository contains training materials for workshops on DevSecOps and Securing your Software Development Lifecycle (SDLC).

The workshop will be held at `BSides CT` on `Saturday, 21st September`. The exact time will be announced soon.

## Workshop Outline

In this workshop, you'll learn the basics of DevSecOps and securing your SDLC using a range of tools. We'll explore both open-source options and those native to GitHub. Participants will learn how to set up IDE plugins, pre-commit hooks, and other techniques to secure their development environment. We will also cover building a CI/CD pipeline using DevSecOps concepts, including secrets scanning, dependency analysis, and Static Analysis Security Testing (SAST).

## Pre-Setup Phase

Before participating in this workshop, you’ll need to create a GitHub account.

- You can sign up at [GitHub](https://www.github.com).
- If you're a student, you can sign up with a `.edu` email to get free private repositories and other benefits.

Once your account is set up, you will need to `Fork` and `Clone` this repository.

A complete guide for setting up the necessary tools is available in the Part 1 README file. This workshop will focus on using GitHub Codespaces.

[Part 1 - Security within the development environment](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part1#part-1---security-within-the-development-environment)

## Part 1: Security within the Development Environment

Attendees will learn how to integrate security tools and pre-commit hooks into their development environment to enhance code security from the start.

1. **Third-Party Plugin Integration**: We’ll explore tools like SonarLint, which can be integrated into the IDE to aid in linting and SAST. We will also review GitHub Copilot.  
   [Part 1 - Module 1: IDE Integration](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part1#module-1-ide-integration)

2. **Pre-Commit Hooks**: This section covers setting up pre-commit hooks using Talisman.  
   [Part 1 - Module 2: Pre-Commit Hooks](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part1#module-2-pre-commit-hooks)

3. **Git Ignore**: You will learn how to use `.gitignore` files to prevent committing sensitive or unwanted files.  
   [Part 1 - Module 3: Preventing Accidental Commits](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part1#module-3-preventing-accidental-commits)

## Part 2: Repository Scanning and Advanced Analysis

We will cover repository scanning techniques, including secrets scanning and vulnerability detection, using tools like GitHub's Dependabot and Tartufo. Additionally, we will explore Endor Labs' advanced features for reachability analysis, SBOM generation with VEX reachability data, and running SCA tests locally.

1. **Secrets Scanning**: Learn how to scan for secrets in your source code using tools like Tartufo/TruffleHog, GitHub, and Horusec.  
   [Part 2 - Module 4: Secrets Scanning](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-4secrets-scanning)

2. **Handling Secrets in GitHub**: Learn how to store and handle secrets securely in GitHub.  
   [Part 2 - Module 5: Handling Secrets in GitHub](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-5handling-secrets-in-github)

3. **Detecting Security Vulnerabilities**: Understand how to detect security vulnerabilities in your repository.  
   [Part 2 - Module 6: Detecting Security Vulnerabilities](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-6detecting-security-vulnerabilities)

4. **Vulnerable Dependency Detection**: Learn how to detect vulnerable dependencies using GitHub's Dependabot.  
   [Part 2 - Module 7: Vulnerable Dependencies](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-7vulnerable-dependencies)

5. **Static Analysis**: This section covers GitHub's SAST tool built on CodeQL and other tools like Horusec.  
   [Part 2 - Module 8: Static Analysis](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-8static-analysis)

6. **Branch Protection and PR Gating**: Learn about using branch protection rules to enforce security checks on pull requests.  
   [Module 9: Branch Protection Rules](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-9branch-protection-rules)

7. **SBOMs (Software Bill of Materials)**: Explore how to extract and use SBOMs from your GitHub repositories.  
   [Part 2 - Module 10: SBOMs](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-10sboms-software-bill-of-materials)

8. **Endor Labs Reachability Analysis**: Learn how Endor Labs' reachability analysis helps prioritize security findings by identifying which vulnerabilities in your code are actually exploitable.  
   [Part 2 - Module 11: Endor Labs Reachability Analysis](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-11endor-reachability-analysis)

9. **Generating SBOM with VEX Reachability Data**: Understand how to generate Software Bill of Materials (SBOM) with VEX (Vulnerability Exploitability eXchange) reachability data to provide insights into whether vulnerabilities found in components are actually reachable.  
   [Part 2 - Module 12: Generating SBOM with VEX](https://github.com/tweag/bsidesct-devsecops-sdlc/tree/main/part2#module-12sbom-vex-reachability)


## Wrap-Up

We'll conclude with a discussion on future trends in DevSecOps and a recap of the topics covered in this workshop.

