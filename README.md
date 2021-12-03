# gh-repo-fzf

A `gh` cli to fuzzy search your repositories and do an action with them
![gh-repo-fzf](https://user-images.githubusercontent.com/41034356/144628703-caaf0921-8d1a-4913-b5a0-24b5f7269549.gif)

## Requirements

1. `gh cli` - minimum version (2.0.0)

2. `fzf`

## Installation

```sh
gh extension install kavinvalli/gh-repo-fzf
```

### Installing Manually

> To install this extension **manually**, follow these steps:

1. Clone repo

   ```bash
   # git
   git clone https://github.com/kavinvalli/gh-repo-fzf

   # github cli
   gh repo clone kavinvalli/gh-fzf
   ```

2. cd into it

   ```bash
   cd gh-repo-fzf
   ```

3. Install it locally
   ```bash
   gh extension install .
   ```
   
## Available actions
- Clone
- View
- Fork
- Archive

## Usage

- To list all directories you have access to, run:

```sh
gh repo-fzf
```

- To list directories of a particular user / organisation:

```sh
gh repo-fzf <username/organisation-name>
```
