# 🛡️ Linux Permissions Lab

## 🔍 Project Overview

This lab demonstrates practical Linux file permission management in the context of securing research data.

As a cybersecurity specialist supporting a research team, my task was to review and adjust the permissions of files and directories within the `projects/` directory to align with organizational access policies. The focus was on applying the principle of least privilege and reducing potential security risks related to misconfigured permissions.

This lab is part of my cybersecurity portfolio and includes real-world examples with screenshots and explanation.

---

## 📁 Files & Structure

| File                     | Description |
|--------------------------|-------------|
| `permissions-report.pdf` | Full case documentation, including screenshots and detailed commentary |
| `README.md`              | Project summary and overview (you’re reading it) |

---

## 🔧 Commands Demonstrated

```bash
# View permissions
ls -la

# Revoke write access for others
chmod o-w project_k.txt

# Modify access to a hidden file
chmod u-w,g-w,g+r .project_x.txt

# Restrict directory execution
chmod g-x drafts
