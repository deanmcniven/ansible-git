# git

Installs and configures Git.
Sets diff tool to Meld.

## Variables
* `git_email` (required): Email address to use for commits
* `git_username` (optional): Defaults to the current users full name

## Optional Variables
The following variables can be set to adjust the behaviour of the git role.
* `git_ignore_intellij_project_files`: Add IntelliJ Idea project file patterns to the global gitignore file, Defaults to true
* `git_ignore_maven_target_directory`: Add maven target directory to the global gitignore file, Defaults to true
* `git_ignore_additional_patterns`: Additional patterns to add to the global gitignore file

