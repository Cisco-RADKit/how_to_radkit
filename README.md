<p align="center">
  <img src="how_to_radkit__.gif" style="width:400" alt="Cisco RADKit" /></br>
</p>

# 💻 Cisco RADKit Developer Community

Cisco RADKit Developer is a public community space for sharing, exploring, and collaborating on RADKit projects. All repositories are open for reading, cloning, and forking, contributions are welcome via Pull Requests.

---

## Table of Contents

- [License](#-license)
- [Contributing a Project](#-contributing-a-project)
- [Project Requirements](#-project-requirements)
- [Repository Setup Checklist](#repository-setup-checklist)
- [Community Expectations](#-community-expectations)
- [Recommendations](#-recommendations)

---

## 📄 License

All material is released under the [Apache 2.0 License](/LICENSE), which ensures open collaboration, freedom to use the software, and protection for contributors.

**Important:**
- Contributors must understand and agree to the license terms.
- If work is done on behalf of an employer, the employer may hold copyright.
- All contributions must include a [Developer Certificate of Origin (DCO)](#️-developer-certificate-of-origin) sign-off.

---

## 🤝 Contributing a Project

### Submission Steps

1. Create a GitHub account if you don't already have one.
2. Prepare your project locally or in your own GitHub repository.
3. Verify your project meets the [Project Requirements](#-project-requirements).
4. Email **radkit-librarians@cisco.com** with:
   - Your repository link
   - A brief project description
   - Maintainer contact information
5. The RADKit librarians will review your submission.
6. If accepted, your project will be added to the Cisco RADKit Developer GitHub organization.

**After onboarding**, you retain maintainer privileges, can grant collaborators access, and community members can submit Pull Requests and Issues.

### Maintenance

If you can no longer maintain your project:

1. Add a note to your README indicating the maintenance status.
2. Email **radkit-librarians@cisco.com**.

The librarians may help find a new maintainer or archive the repository if it becomes inactive.

---

## ✅ Project Requirements

Submitted projects must:

- Be relevant to RADKit users or developers
- Include clear and concise documentation
- Build and run as described
- Follow licensing rules
- Be and remain **publicly accessible**
- Accept community collaboration

> Projects that do not meet these requirements may be declined or archived.

### ✍️ Developer Certificate of Origin

Every commit must be signed off using `git commit -s`, certifying that you have the right to submit the code.

First, make sure your git identity is configured:

```bash
git config user.name "John Smith"
git config user.email "johnsmith@example.com"
```

Then sign off your commits:

```bash
git commit -s -m "My commit message"
# Adds: Signed-off-by: John Smith <johnsmith@example.com>
```

By signing off, you confirm you have the right to submit the code and that it will be publicly accessible. See the [Developer Certificate of Origin](https://developercertificate.org) for full terms.

---

## Repository Setup Checklist

Use this checklist when preparing your repository:

| Item | Requirement |
|------|-------------|
| **Name** | Catchy or descriptive, avoid generic names like `generic-tool`. For tools/libraries, creative names are encouraged (e.g., `IxT`). For demos, use descriptive names (e.g., `jwt-login-demo`). |
| **Description** | Clearly explain what the project does, its type (tool, example, library), and who it helps. |
| **README.md** | Must include: what the project does, dependencies, build/run instructions, and attribution for any derived code. |
| **LICENSE** | Add a `LICENSE` file, [Apache 2.0](/LICENSE) is recommended. |

---

## 💡 Community Expectations

### As a user

- Code is provided **"as is"**, use it at your own risk.
- Bug fixes and extensions are welcome back as Pull Requests.

### As a contributor

- Your code will be available to everyone in source form.
- It may be used for teaching, building products, or as a starting point for other projects.
- Only contribute code you own the intellectual property rights (IPR) to.
- Avoid any references to customers: names, network configs, templates, etc.
- Supporting your code is encouraged but not mandatory, reviewing PRs and responding to issues is appreciated.

---

## 💎 Recommendations

- Add test cases and include instructions on how to run them.
- Specify which RADKit API/SDK version your project is tested against, not all features are backwards compatible.
- Tag releases in Git and maintain a `CHANGES` file or Release Notes if you publish versioned releases.

---

Thank you for your interest. Happy collaboration!
