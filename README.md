# Templ Hello World Demo

This is a very simple demonstration project using the [templ](https://github.com/a-h/templ) Go library for generating HTML.

## Prerequisites

- [Go](https://go.dev/doc/install) installed on your system.

## Getting Started

1.  **Clone the project:**
    ```bash
    git clone <repository-url> # Replace <repository-url> with the actual URL
    cd templ-hello-world
    ```

2.  **Install dependencies:**
    Run the bootstrap script. This will install the necessary Go modules and the `air` tool for live reloading.
    ```bash
    script/bootstrap
    ```
    *(Alternatively, you can manually install `air` globally (`go install github.com/air-verse/air@latest`) and run `go mod tidy`)*

3.  **Run the development server:**
    Use `air` to start the server. It will watch for file changes and automatically rebuild and restart the server.
    ```bash
    air
    ```

4.  **View the application:**
    Open your web browser and navigate to [http://localhost:3000](http://localhost:3000).

Changes to `.templ` or `.go` files will trigger a reload automatically.
