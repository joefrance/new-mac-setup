# new-mac-setup
When one gets a new Mac, what must/should one install?

- General
  - [Kindle](https://apps.apple.com/us/app/kindle/id405399194?mt=12)
  - MS Office and/or Keynotes, etc.
  - Google Chrome
  - [Microsoft Remote Destop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)
- Communications
  - Activate Messages WITH phone support
    - On Mac
      - In the `Messages` app go to 
        - `Preferences -> iMessages`
          - Check `Enable this account`
          - Check the phone number(s) to use for messaging
          - If multiple numbers then choose the one for `Start new conversations from:`
    - On your iPhone
      - Go to `Settings` app
      - `Messages -> Text Message Forwarding`
        - Turn on forwarding for each device (Find the Mac you're using)    
  - Slack
  -  Microsoft Teams
- Development
  - VS Code
    - Font ligatures
      - `brew tap homebrew/cask-fonts`
      - `brew cask install font-fira-code`
      - `Code -> Preferences -> Settings`
      - `Edit Settings`
        - `{` 
        - `"editor.fontFamily": "Fira Code",` 
        - `"editor.fontLigatures": true`
        - `}`
    - VS Code Printing Free (adds print icon to top-right menu)
    - Add VS Code to PATH so you can run `code .` from a folder and load it into VS Code
      - https://github.com/microsoft/vscode/issues/48124
      - TL;DR
        - `cat << EOF >> ~/.bash_profile`
        - `# Add Visual Studio Code (code)`
        - `export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"`
        - `EOF`
    - [.NET Core](https://dotnet.microsoft.com/download/dotnet-core)
  - Docker Desktop
  - git
  - home brew
  - dotnet SDK 3.1
  - Azure Data Studio
  - [npm](https://treehouse.github.io/installation-guides/mac/node-mac.html)
- Cloud
  - OneDrive
  - CrashPlan
