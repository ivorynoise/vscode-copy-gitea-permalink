# vscode-copy-gitea-permalink

Originally forked from [hogashi/vscode-copy-github-permalink](https://github.com/hogashi/vscode-copy-github-permalink).


Copies Gitea permalink of active file (name and line) to clipboard on VSCode. https://marketplace.visualstudio.com/items?itemName=ivorynoise.vscode-copy-gitea-permalink

## Features

- Open command pallete (with Cmd-Shift-P or so)
- Input to search `Copy Gitea Permalink` and select it
- Then your clipboard has a Gitea permalink generated by your workspace's git info and active file (name / line number)
  - Like this: `https://gitea.com/repository/src/commit/24025d3c788c0518811ebc3fc9f402c768cdb331/ivorynoise/first_env.sh#L7`
  - Multiple-lined permalink will be copied if multiple lines are selected: `https://gitea.com/repository/src/commit/24025d3c788c0518811ebc3fc9f402c768cdb331/ivorynoise/first_env.sh#L3-L7`

## Requirements

- Workspace is with git
- File is opened

## Extension Settings

- Nothing

