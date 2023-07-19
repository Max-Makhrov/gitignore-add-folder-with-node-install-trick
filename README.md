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
   [Ctrl] + [`]
   [Ctrl] + [Alt] + [n]
   => [Enter] this will install node + add my 'history/' to .gitignore
