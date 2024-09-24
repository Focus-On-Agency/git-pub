# git-pub

`git-pub` is a bash script that simplifies the formatting and management of Git commits. The script guides the user through several prompts to collect the necessary information and automatically generates a formatted commit with the type, task number, title, and an optional body.

## Features

- Prompts the user to specify the commit type (FIX, UPDATE, ADD, PARTIAL).
- Allows optional input for a task number.
- Requires a commit title.
- Allows an optional commit body.
- Uses icons based on the commit type:
  - `FIX`: 🔧
  - `UPDATE`: 🔄
  - `ADD`: ➕
  - `PARTIAL`: ✳️
- Executes `git add`, `git commit`, and `git push` in sequence, handling any errors.

## Usage Instructions

1. Place the `git-pub` file in the `~/bin` directory or any directory of your choice.

2. Ensure that the directory where you saved the script is included in your `$PATH`. To do this, add the following line to your `.bashrc`, `.bash_profile`, or `.zshrc` file (depending on your shell):

   ```bash
   export PATH="$HOME/bin:$PATH"
   ```
   
   Then, run `source ~/.bashrc` (or the corresponding file for your shell) to apply the changes.

3. Make the script executable by running:

   ```bash
   chmod +x ~/bin/git-pub
   ```

4. Use the script by running the `git pub` command in the Git repository directory where you want to make the commit.

5. Follow the prompts to enter the required information for the commit.

## Example

Here's an example of how to use `git-pub` to make a commit:

1. Run `git pub` in the Git repository directory.

2. Enter the commit type (e.g., `FIX`).

3. Enter the task number (optional).

4. Enter the commit title.

5. Enter the commit body (optional).

6. The script will automatically run `git add`, `git commit`, and `git push`.

## Note

- Make sure you have Git configured with your username and email before using the script.
- The script is designed to work on Unix-like systems with Bash. It may not work correctly on Windows or with other shells.

With `git pub`, you can streamline the process of creating and formatting commits in Git, ensuring greater consistency and clarity in your commit messages. Try using this script to enhance your versioning experience with Git!