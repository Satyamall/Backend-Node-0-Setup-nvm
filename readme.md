
### Setup nvm in Windows

-To install or update nvm
# command run in terminal step by step: 
- npm install -g nvm
1. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
2. export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ]                      && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
3. [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

4. To verify that nvm has been installed, do:

- command -v nvm
![Screenshot (112)](https://user-images.githubusercontent.com/80479635/151222242-54f9685f-c4f9-4a9f-9b0c-9c0c7745c511.png)
