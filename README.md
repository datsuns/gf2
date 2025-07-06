# gf2

## winfilemanager

A simple file manager example for Windows using the [gocui](https://github.com/jroimartin/gocui) library.

### Keybindings

- `Ctrl+C` - Quit the application.

### Build

Run the following command from the repository root:

```sh
go build -o winfilemanager.exe ./cmd/winfilemanager
```

### Running on Windows

Ensure Go is installed. Build the application as above and execute `winfilemanager.exe` from a command prompt. The UI shows a single view with the message "Press Ctrl+C to quit". Use the keybinding to exit.

