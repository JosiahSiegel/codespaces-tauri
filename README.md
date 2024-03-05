# codespaces-tauri

[![Pre-Release](https://github.com/JosiahSiegel/codespaces-tauri/actions/workflows/pre-release.yml/badge.svg)](https://github.com/JosiahSiegel/codespaces-tauri/actions/workflows/pre-release.yml)

## Get started

 1. Run Codespaces in browser
 2. Create app:
    * Interactive example: `npm create tauri-app@latest`
    * Non-interactive example:
      ```sh
      cargo install create-tauri-app;
      cargo create-tauri-app --force --yes my-tauri-app --template vue --manager npm
      ```
 3. Install app:
    * ```sh
      cd my-tauri-app
      npm install
      ```

 4. Run app in VNC (http://localhost:6080):
    * `WEBKIT_DISABLE_COMPOSITING_MODE=1 npm run tauri dev`
    * Env variable resolves failure running app within VNC
