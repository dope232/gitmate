# GitMate: Simplifying Git Commands in Terminal to my life a bit easier 


## Getting Started

1. **Create a Repo:** Start by creating a repository on GitHub.
2. **Clone Repo:** Use `git clone` to clone the repository onto your local machine.

## Setup

Ensure that your GitHub and Git accounts are linked. 


## Installation

1. Navigate to the cloned repository directory.
2. Run `cargo build --release` to build the project.
3. Install the binary using `cargo install --path .`.

## Usage

1. Navigate to your Git repository in the terminal.
2. Use the following commands:

   - `gitmate [commit message]`: Commit changes, update the repository, and push changes to the remote.
   - `gitmate pull`: Pull changes from the main/master branch.
   - `gitmate branch [branch name]`: Create a new branch and switch to it.

### Example:

```bash
gitmate "Added new feature"
gitmate pull
gitmate branch feature-branch
