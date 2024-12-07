# CLI Arguments

<img src="./assets/script.png" width="50">

*Linutil supports various command-line arguments to customize its behavior. Here are some common arguments you can use:*

- `-c, --config <CONFIG>` : Path to the configuration file.
- `--override-validation` : Show all available options, disregarding compatibility checks (UNSAFE).
- `--size-bypass` : Bypass the terminal size limit.
- `-y, --skip-confirmation` : Skip confirmation prompt before executing commands.
- `-t, --theme <THEME>` : Set the theme to use in the application [default: `default`] [possible values: `default`, `compatible`].
- `-h, --help` : Print help.

For more detailed usage, run:

```bash
curl -fsSL https://christitus.com/linux | sh -s -- --help
```

```bash
linutil --help
```

