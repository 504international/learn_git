## Section 2: Getting Started with Git

### Installing Git
Before you can start using Git, you need to have it installed on your machine. Git can be installed on various operating systems including Windows, macOS, and Linux.

#### Windows Installation
1. Download the latest Git for Windows installer from the [Git website](https://git-scm.com/download/win).
2. Run the installer and follow the prompts to install Git. During installation, you can choose the default editor for Git, adjust your PATH environment, and select the SSH executable among other options.
3. Once installed, you can verify the installation by opening the Git Bash application and typing `git --version`.

#### macOS Installation
1. The easiest way to install Git on macOS is using the Homebrew package manager. If you don't have Homebrew installed, you can find instructions on the [Homebrew website](https://brew.sh/).
2. Once Homebrew is installed, open a terminal and type `brew install git` to install Git.
3. Verify the installation by typing `git --version` in the terminal.

#### Linux Installation
1. Git can be installed on Linux using the package manager that comes with your distribution. For Ubuntu/Debian-based systems, you can use `sudo apt-get install git`.
2. Verify the installation by typing `git --version` in the terminal.

### Basic Configuration of Git
After installing Git, you should configure it by setting up your user name and email address. This information is important because Git uses it to identify the author of the commits.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
