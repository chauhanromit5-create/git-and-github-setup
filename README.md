# 🚀 Git & GitHub Quick Start Guide

A step-by-step walkthrough to install Git, configure your identity, link your project folder to GitHub, and manage your code updates.

---

## 🛠️ Step 1: Install & Configure Git

1. **Download Git:** Download and install Git for Windows from the [Official Git Website](https://git-scm.com/install/windows).
2. **Open Git Bash:** Open the **Git Bash** application on your computer.
3. **Set Your Credentials:** Copy and paste the following commands to reset and configure your global identity:

```bash
# Clear any previous configurations
git config --global --unset user.name
git config --global --unset user.email

# Set your active GitHub credentials
git config --global user.name "chauhanromit5-create"
git config --global user.email "chauhanromit5@gmail.com"
