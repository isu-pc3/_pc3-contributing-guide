# PC3 Contributing Guide
**ISU Physics Coding & Computation Collective**

Welcome to the contributing guide for **PC3 (Physics Coding & Computation Collective)**!
This document explains how members may contribute code, collaborate on projects, and follow the organizational standards for version control and computational work.

## 1. Purpose of This Guide
This repository serves as our source for:

- Git and Github workflow instruction
- Branching and merging conventions
- Code style standards
- How to submit pull requests
- How to request to join the organization
- Expectations for contributors
- Project structure guidelines

## 2. Getting Started

### 2.1 Prerequisites
Before contributing, you should have:
- A Github account
- Git installed on your computer
- Python (3.10+) installed

**If missing any of these, refer to 2.1.x, according to what you are missing**

#### 2.1.1 Install Git

##### Windows
1. Download Git for Windows at:
   https://git-scm.com/download/win
2. Run the installer.
3. Accept default options (recommended)
4. When prompted for command line integration, choose:
   "Git from the command line and also from 3rd-party software."

##### macOS

**Step 1 - Install Homebrew (recommended for macOS users)**
Homebrew is the standard package manager for macOS and makes installing Git much easier.

Open terminal and run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After installation completes, follow Homebrew's on-screen instructions to add it in your PATH
Then confirm Homebrew works:

```bash
brew --version
```

**Step 2 - Install Git using Homebrew:**

```bash
brew install git
```

Alternatively, download Git directly for macOS at:
https://git-scm.com/download/mac

##### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install git
```

##### Verify Git Installation

```bash
git --version
```

Expected output (As of 11/24/25):

```
git version 2.43.0
```

---

#### 2.1.2 Create a Github Account

1. Visit: https://github.com.join
2. Sign up using your email.
3. Choose a professional username.
4. Verify your email and log in.

---

#### 2.1.3 Install Python (3.10+)

##### Windows & macOS

Download Pythong from:
https://www.python.org/downloads/

On Windows, check:
**"Add python to PATH."**

##### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install python3 python3-pip
```

##### Verify Python installation

```bash
python3 --version
```

OR for Windows:

```bash
python --version
```

Expected output:

```
Python 3.10.x
```

---

#### 2.1.4 Install VS Code (Recommended Editor)

Download VS Code at:
https://code.visualstudio.com/

#### 2.2 Joining a Project

1. Select a repository
2. Read the project README
   Every project should include:
   - its purpose
   - expected coding style
   - required dependencies
   - contribution guidelines
3. Create a new branch
   All feature work must be done in a branch.
4. Make your changes locally
5. Commit changes with a commit description
6. Push your branch to GitHub
7. Open a pull request
   Go to the repository on GitHub and submit a PR from your branch into 'main'.
8. After review and approval it will be merged into "main" and you can delete your branch

## 4. Licensing

All PC3 repositories use the **MIT License**, located in the `.github` repo.
Student contributors retain authorship of their work while allowing open collaboration

## 5. Contact

For any issues that may arise, email:

lwise@iastate.edu
or open an issue in the `.github` repo.
