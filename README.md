# vscode-jq

jq Language Support for VS Code

> [!warning]
> This project isn't going to be maintained. It's recommended to use <https://github.com/wader/vscode-jq>

## Features

- Syntax highlighting
- Auto completion
- File icons

Syntax highlighting

![Syntax highlighting](./images/examples/convert.png)

Auto completion

![Auto completion](./images/examples/convert.gif)

> Color Theme is [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

## Install

### From extension marketplace

Not yet

### From source code

```sh
# Clone the repository
git clone https://github.com/juemuren/vscode-jq.git
cd vscode-jq
# Package
npx @vscode/vsce package
# Install
code --install-extension vscode-jq-*.vsix
```
