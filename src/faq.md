# FAQ

<img src="./assets/faq.png" width="50">

[What is Linutil?](#what-is-linutil)

[How to Use Linutil?](#how-to-use-linutil)

[Can Using Linutil Break My System?](#can-using-linutil-break-my-system)

[How do i uninstall Linutil?](#how-do-i-uninstall-linutil)

## What is Linutil?

*Linutil is a versatile tool designed to help with various application setups, including gaming and system utilities. It provides a text-based user interface (TUI) that simplifies the setup process.*

## How to Use Linutil?

1. **Installation**  
   - You can install Linutil from a package manager or directly from GitHub.  
   - If you're using the CLI, you can run it directly from GitHub by choosing either the stable or dev branch.

2. **Running Linutil**  
   After installation, simply run the command `linutil` in your terminal to launch the TUI. You will be presented with different setup options for various packages. Instructions are provided within the interface to guide you through each option.

3. **Using Linutil**  
   Once the TUI is open, you can select different setups, and Linutil will handle the configuration automatically. It's designed to make the process as simple as possible for users.

## Can Using Linutil Break My System?

In general, using Linutil will not break your system. There are no scripts in Linutil that can cause system failure. The TUI is user-friendly, and you can easily see available options. If you are unsure about a script or option, you can always search for more information online.

However, it’s important to understand what each option does before selecting it. If you choose an option without knowing its function, it could potentially lead to issues on your system. Ultimately, using Linutil is safe as long as you're aware of what you're doing.

## How do I uninstall LinUtil?

- **If you are running Linutil directly from GitHub using the CLI command**, it will run in the `/tmp` directory, and Linutil will be removed automatically as soon as you exit the program.

- **If you installed Linutil via a package manager**, you can uninstall it using one of the following commands:
  - For **paru**:  
    `paru -R linutil<git/bin>`
  - For **yay**:  
    `yay -R linutil<git/bin>`

  - OpenSUSE
 `sudo zypper remove linutil`

  - Cargo
  `cargo uninstall linutil_tui`
