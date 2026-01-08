# GitHub Copilot Instructions for Jamie-BitFlight Repository

## Repository Overview

**Profile/portfolio repository** (special GitHub repo matching username) serving as Jamie Nelson's professional profile page at https://github.com/Jamie-BitFlight.

**Purpose:** Showcase DevOps/CI/CD/IaC expertise with links to external projects.

**Key Facts:**
- Single-file repository containing only README.md (108 lines, 9KB)
- Pure Markdown documentation, no code
- No build process, dependencies, or tests
- Size: ~196KB total

## Repository Structure

```
/
├── .git/                  # Git repository metadata
├── .github/              # GitHub configuration directory
│   └── copilot-instructions.md  # This file
└── README.md             # Profile page content (108 lines)
```

### Key Files

**README.md** - Profile page containing:
- Personal intro (New Haven, CT, USA)
- 10+ years experience in CI/CD, IaC, cloud automation
- Technical skills: CI/CD, Terraform, AWS, Linux, multiple languages
- Links to external projects (CI/CD tools, Terraform modules)
- LinkedIn contact info

## Making Changes

### Editing the Profile (README.md)

**Guidelines:**
1. **Preserve Formatting:** Maintain emoji bullets, markdown headers, and existing style
2. **Section Structure:** Header, About Me, Expertise (bulleted), Repositories (categorized links), Learning Goals, Contact
3. **Repository Links Format:**
   ```markdown
   - #### Project Title
     🔗[org/repo-name](https://github.com/org/repo-name)
       Brief description.
   ```
4. **Professional Tone:** This is a public professional portfolio

### Validation

**No build/test required.** Only validate:
- Markdown syntax correctness
- Links properly formatted
- Consistent formatting (-, #### for subsections)

**Preview markdown rendering if possible before committing.**

## GitHub Actions Workflows

**One active workflow:** "Copilot coding agent" (path: `dynamic/copilot-swe-agent/copilot`)
- Dynamically managed by GitHub Copilot
- No manual intervention required

## Git Operations

**Default Branch:** `main`

Standard git commands work normally:
```bash
git --no-pager status     # Check status
git --no-pager diff       # View changes
cat README.md             # View content
```

## What This Repository Does NOT Have

**To save exploration time, this repository has NO:**
- Source code files (.js, .py, .java, .ts, etc.)
- Build configs (package.json, Makefile, pom.xml)
- Dependencies (package-lock.json, requirements.txt, go.mod)
- Test files or frameworks
- CI/CD config files (.github/workflows/*.yml in repo)
- Linting config (.eslintrc, .pylintrc)
- Docker files
- IaC files (.tf, CloudFormation)
- Scripts directory

## Troubleshooting

**Q: How do I build/test?**  
A: Nothing to build/test. This is documentation-only.

**Q: Where are the project files?**  
A: This is a profile repo. Projects referenced are external (bitflight-devops, bitflight-public orgs).

**Q: Changes not on profile?**  
A: Ensure committed to `main` branch. GitHub displays README.md from main on profile page.

## Key Reminders

1. **Trust These Instructions:** Repository thoroughly analyzed. Search only if instructions incomplete/incorrect.
2. **Documentation-Only:** No build files, tests, or source code exists.
3. **No Validation Pipeline:** No build failures, tests, or linting. Only validate markdown formatting.
4. **Preserve Professional Tone:** Public-facing professional profile.
5. **External Projects:** Listed projects are references only. Don't modify external repos.
6. **Minimal Changes:** Make surgical edits. Preserve structure and style.
7. **No Dependencies:** No packages, runtimes, or environment setup needed.

## Content Summary

**Professional Background:** 10+ years CI/CD, IaC, cloud automation  
**Skills:** TypeScript, JavaScript, Python, Java, C/C++, Groovy, Perl, Bash  
**Expertise:** GitHub Actions, Jenkins, Jira, Terraform, Packer, AWS, Linux  
**Projects Listed:**
- 4 GitHub Actions (README generator, Jira tools)
- 1 Shell script library with cross-platform functions
- 5+ Terraform modules for AWS
**Contact:** LinkedIn profile included

## Files in Repository

**/ (root):**
- README.md (9,057 bytes, 108 lines)

**/.github/:**
- copilot-instructions.md (this file)

---

**Last Updated:** January 2026
**Repository URL:** https://github.com/Jamie-BitFlight/Jamie-BitFlight
