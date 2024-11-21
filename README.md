# Virtenv-Convenience
A Bash function and script to list and activate virtual environments.

Usage:
  - ve list
    - List all virtual environments in the current directory.
  - ve activate <env_name>
    - Activate the specified virtual environment.

You can shorten the "activate" command to "act" for convenience. 
 
You can enter the first few characters of the environment name instead of the full name. If multiple environments are found, only the first one found will be activated.

## Future additional features.

- [ ] List resources used by each virtual environment.
- [ ] Remove a virtual environment.
- [ ] Compare one virtual environment with another.
