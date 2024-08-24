# TodoJsonCli
This code is a simple command-line interface (CLI) tool for managing a to-do list using JSON files.
## Features
- **Add** a new to-do item with a deadline.
- **Remove** an existing to-do item by specifying the title and date.
## Installation
1. ```Clone the repository```
2. ```npm install```
## Usage
- Add a To-Do
- To add a new to-do item, use the add command followed by the deadline and the to-do title:
```bash
node Todo.js add <Time> <Todo>
```
- Remove a To-Do
- To remove an existing to-do item, use the remove command followed by the title and the date of the JSON file:
```bash
node Todo.js remove <Todo> <Date>
```
- For help
```bash
node Todo.js -h
```
