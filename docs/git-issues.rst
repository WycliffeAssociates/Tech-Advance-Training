Errors
======
- "fatal: detected dubious ownership in repository"

This error  occurs when Git detects that the current user executing a command is not the owner of the repository's top-level directory, which is a security measure introduced in Git version 2.35.2 and later.

The solution is to use the command `git config --global --add safe.directory «data path»/targetTranslations/*`

This will allow all of the repositories in targetTranslations to be trusted for all operations.
