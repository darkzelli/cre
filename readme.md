# 🌌 CRE: Command-line Repository Enhancements 🌍

A collection of command-line interfaces.

## OS Compatibility

- **macOS**: ✅
- **Windows**: ❌

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Open your shell configuration file:

   - For `zsh`, use:
     ```bash
     nano ~/.zshrc
     ```
     or
     ```bash
     cmd shift .
     ```
     in your home directory to show hidden files.

3. Add the following line to your shell configuration file to include the repository in your PATH:

   ```bash
   export PATH=$PATH:/path/to/cloned/repo
   ```

4. Apply the changes by executing:

   ```bash
   source ~/.zshrc
   ```

You should now be able to use `cre` as a command from anywhere in your terminal.

---

## Collection

### ✨ cre: Command-line Repository Enhancements ✨

A collection of useful and shortcut commands designed to enhance efficiency in command-line operations.

### Example Usage:

| Action                            | Command                                                     |
| --------------------------------- | ----------------------------------------------------------- |
| Clone the default repository      | `cre`                                                       |
| Clone a specific repository       | `cre --r https://github.com/example/repo --d new_directory` |
| Update the default repository URL | `cre --set-default https://github.com/new/default-repo`     |

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

