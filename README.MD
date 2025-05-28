## Kalogon printer profiles

nothing in the master branch, checkout the other branches for printer configs.

to use, clone this repo to the config directory of the slicer with
`git clone --branch <branch-name>`

or, to clone into the existing directory, use:

```bash
cd ~/.config/<slicer-name>
git init
git remote add origin git@github.com:KalogonTech/print-profiles.git
git fetch
git checkout <branch-name>
```

|  branch name  |        linux path        |         win path         |
| :-----------: | :----------------------: | :----------------------: |
| `PrusaSlicer` | `~/.config/PrusaSlicer/` | `%APPDATA%\PrusaSlicer\` |
| `BambuStudio` | `~/.config/BambuStudio/` | `%APPDATA%\BambuStudio\` |
| `OrcaSlicer`  | `~/.config/OrcaSlicer/`  | `%APPDATA%\OrcaSlicer\`  |