## Install

[Ctrl]+[Sift]+[P] => search

```
Open Keyboard Shortcuts (JSON)
```

Add this command:

```
{
  "key": "ctrl+alt+n",
  "command": "workbench.action.terminal.sendSequence",
  "args": {
    "text": "& {npm init -y; Add-Content -Path '.gitignore' -Value '.history/'}"
  }
}
```

Change ".history/' to your forder or file.

## Usage. Creating a new project lacallly


New project:

1. terminal
   `npm init vite@latest`
   `cd path`
   `code .`
2. Vs code
   * [Ctrl] + [`], 
   * [Ctrl] + [Alt] + [n], 
   * => [Enter] this will install node + add my 'history/' to .gitignore

## Notes
```
SvelteKit + Firebase
  1.[+] Install Svelte Latest as usual
  2.[+] Install Firebase
     [+] Go to FireBase site, create new...
     [+] install in command line
         npm install firebase
        .env https://youtu.be/8NlUTFppJkU?t=446
        fitebase.client.js: https://github.com/jamezmca/sveltekit-auth/blob/main/src/lib/firebase/firebase.client.js
        (once) npm install -g firebase-tools
   2.[ ] Whats next: auth? firestore? analytics?

Web Dev
  Chrome Dev Tools
    [Ctrl]+[Shift]+[J]
  VS Code
    Shortcuts
      arrows -> select last entered Commands
      tab -> autocomplete direction after cd
      interface
        Ctrl+Shift+P  - see all commands
      Terminal
        Ctrl + L   - clear terminal
        Ctrl + Shift + `  - create new terminal
    Useful
      Run code from single file
        node ./src/day.js
    npm
      npm-run-all   - A CLI tool to run multiple npm-scripts in parallel or sequential.
    package.json
      Commands
        npm init    - generate valid package.json or rewrite defaults
          npm init --y    - with defaults
        npm config  - change config and save them in memory
          npm config set init.licence MIT
          npm config set init.author.name Max Makhrov
          npm config set init.author.email m@m
          npm config set init.author.url ct.onl
            after config ???
              rm package.json
              npm init --y
        npm cli     - add/remove/upd dependencies
      Git
        git init → git add . → git commit -m "first"
        git remote add origin https\github.gg    - add github origin
      Apsp Script Autoclomplete
        npm install --save @types/google-apps-script
      Clasp
        npm run clasp:login   - opens standard Google Authorization window
          Default credentials saved to: ~\.clasprc.json (C:\Users\Asus\.clasprc.json)
        clasp:create          - create new AppsScript?
        "rpm run deploy"      - "run-s bundle clasp:push"
        clap clone            - clones gas project => link project to VS-Code
        clasp push -w     - push once and watch changes
        .claspignore
          **/**              - ignore all files…
          !**/*.gs           - except the extensions…
        clasp push -w  >   so that changes are pushed every few seconds to Drive automatically
        clasp open > open in browser
        clasp pull > code to PS
        clasp push > code to Google Drive
        clasp setting projectId ID > set Google Cloud Project ID
        clasp settings > get script id
      Useful
      clear
        cd > go to directory [use TAB-autocomplete]
        cd .. > one folder up
        ls > get subfolders
        md > create directory = folder
        rd > remove directory [use TAB-autocomplete]
        rm > remove file or directory
      Modules
        Day.js
          npm i dayjs
```
