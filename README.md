# JSON editor
A terminal-based JSON editor built with Rust and `ratatui`. It provides an interactive interface for editing JSON directly in the terminal. The buffer content can be redirected to a file using:

```sh
cargo run >> test.json
```

## Features

- **Interactive TUI Interface**  
  Edit JSON structures with a clean and intuitive terminal UI.
- **Live Editing**  
  Create JSON in real-time with editing commands.
- **Export to File**  
  Redirect the buffer content to a file using standard output redirection.

## Usage

1. Clone the repository and navigate to the project directory.
2. Build and run the application with `cargo run`.
3. Interact with the JSON editor via the terminal.
4. Export the buffer to a file with output redirection:

