# 📁 mkcd

> Create a directory and immediately open it.

`mkcd` is a small cross-platform utility that combines the functionality of `mkdir` and changing into the newly created directory. It is available for both **Linux** and **Windows**:

- 🐧 `mkcd.sh` — Linux shell script
- 🪟 `mkcd.bat` — Windows batch script

---

## ✨ Features

- 📂 Creates directories automatically
- ⚡ Faster than typing separate commands
- 🐧 Works on Linux
- 🪟 Works on Windows
- 🛠️ Lightweight and dependency-free

---

## 📑 Table of Contents

- [Files](#-files)
- [Installation](#-installation)
- [Usage](#-usage)
- [Examples](#-examples)
- [How It Works](#-how-it-works)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📦 Files

| File | Platform | Description |
|--------|----------|-------------|
| `mkcd.sh` | 🐧 Linux | Creates a directory and enters it in supported shells |
| `mkcd.bat` | 🪟 Windows | Creates a directory and opens it in Command Prompt |

---

## 🔧 Installation

### 🐧 Linux

Run it:

```bash
mkcd my-project
```

---

### 🪟 Windows

Run the batch file from Command Prompt:

```cmd
mkcd my-project
```

---

## 🚀 Usage

### Linux

```bash
mkcd <directory-name>
```

### Windows

```cmd
mkcd <directory-name>
```

---

## 💡 Examples

### Create a project folder

```bash
mkcd awesome-app
```

or

```cmd
mkcd awesome-app
```

Creates:

```text
awesome-app/
```

---

### Create nested folders

```bash
./mkcd projects/web/portfolio
```

or

```cmd
mkcd projects\web\portfolio
```

Creates the full directory structure if it does not already exist.

---

## ⚙️ How It Works

The tool:

1. 📁 Creates the specified directory.
2. ✅ Verifies the operation succeeded.
3. 📂 Opens or changes into the newly created directory (depending on platform and shell behavior).

---

## 🛠️ Troubleshooting

### Directory already exists

The tool may report that the directory already exists depending on the platform and implementation.


### Command not found

Verify that:

- The script exists in the current directory.
- The script's location is included in your system `PATH`.

---

## 🤝 Contributing

Contributions are welcome!

1. 🍴 Fork the repository
2. 🌱 Create a branch
3. 💾 Commit your changes
4. 🚀 Submit a pull request

---

## 📄 License

Licensed under the **MIT License**.

Use it freely in personal and commercial projects.
