
### Setup nvm in Windows

-To install or update nvm
# command run in terminal step by step: 
1. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
2. export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ]                      && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
3. [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

4. To verify that nvm has been installed, do:

- command -v nvm
