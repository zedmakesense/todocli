# todocli

A simple command-line todo list application built with Go and Cobra.

## Features

- Add new todos
- List all todos in a table format
- Delete todos by ID
- Mark todos as complete

## Installation

```bash
go mod download
go install
```

## Usage

### Add a todo
```bash
todocli add "Buy groceries"
```

### List all todos
```bash
todocli list
```

### Mark a todo as complete
```bash
todocli complete <id>
```

### Delete a todo
```bash
todocli delete <id>
```

## Data Storage

Todos are stored in a CSV file at `$HOME/.config/todocli/data.csv`.
