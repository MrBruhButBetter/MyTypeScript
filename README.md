# MyTypeScript

A modern Node.js backend API built with TypeScript, Express, Drizzle ORM, and Better Auth.

## 🚀 Quick Start

To clone the repository and open it in Visual Studio Code, run the following commands:

```bash
git clone https://github.com/MrBruhButBetter/MyTypeScript
cd MyTypeScript
code .
```

### 📦 Installation

If you already have Node.js and NPM installed, simply install the project dependencies by running:

```bash
npm install
```

*Note: This automatically provisions all core dependencies (`express`, `zod`, `better-auth`, `drizzle-orm`, `pg`) and dev tools (`typescript`, `tsx`, `drizzle-kit`).*

---

## 🛠️ Prerequisites (If you don't have Node.js/NPM)

Follow these steps to set up your environment on Linux/Ubuntu systems:

### 1. Update Packages and Install cURL
Ensure your local package index is up-to-date and that cURL is installed:

```bash
sudo apt update && sudo apt install -y curl
```

### 2. Install Node Version Manager (NVM)
Run the official NVM installation script:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

### 3. Reload Your Terminal Environment
To start using NVM immediately without closing your terminal window, source your configuration file:

* If using **Bash**: 
  ```bash
  source ~/.bashrc
  ```
* If using **Zsh**: 
  ```bash
  source ~/.zshrc
  ```

Verify that NVM is successfully running by typing:
```bash
command -v nvm
```

### 4. Install Node.js and NPM
Install the stable Long-Term Support (LTS) release of Node.js (which includes NPM):

```bash
nvm install --lts
```

### 5. Verify the Installation
Confirm that both components are active and check their versions:

```bash
node -v
npm -v
```
