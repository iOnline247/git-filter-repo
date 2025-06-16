# git-filter-repo
It's apparent that I need this...

## Prerequisites
Follow this install guide for up to date information: https://github.com/newren/git-filter-repo/blob/main/INSTALL.md#pre-requisites  

### Steps I've Used
- `winget install Python.Python.3.13`
- Ensure Python is available within the shell. e.g. Check the `$env:PATH` variable or type `python --version`
- Download the `git-filter-repo` script and do not add an extension. Keep the name of the file as: `git-filter-repo`
- Run this command to purge file locally: `python "<FILE_PATH_TO>\git-filter-repo" --path "<FILE_PATH_TO_PURGE>\oopsie-file.txt" --invert-paths`
  - https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository#purging-a-file-from-your-local-repositorys-history-using-git-filter-repo
- From local, force push the new reality: `git push origin main:main --force`
  - Don't do that again 🫡
