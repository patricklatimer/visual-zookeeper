# Visual ZooKeeper

Visually manage your ZooKeeper in Visual Studio Code.

[![version badge](https://img.shields.io/visual-studio-marketplace/v/gaoliang.visual-zookeeper?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=gaoliang.visual-zookeeper)

<a href="https://www.producthunt.com/posts/visual-zookeeper?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-visual&#0045;zookeeper" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=337006&theme=light" alt="Visual&#0032;ZooKeeper - Visually&#0032;manage&#0032;your&#0032;ZooKeeper&#0032;in&#0032;Visual&#0032;Studio&#0032;Code&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

## Features
1. 🚀 Edit and view data on ZooKeeper using the perfect VSCode's editor.
![json data edit](screenshots/1-json.png)
![yaml data edit](screenshots/2-yaml.png)
2. 🚀 View node statistics info
![stat info](screenshots/3-stat-info.png)
3. 🚀 Add nodes directly from the page
![add node](screenshots/4-add-node.png)
4. 🚀 Support Command Palette
![commands](screenshots/5-commands.png)

## Extension Settings

- `visualZooKeeper.zooKeeperServer`, default ``
- `visualZooKeeper.nodeLanguage`, default `yaml`


## Commands

- `visualZooKeeper.editNode`
- `visualZooKeeper.refreshNode`
- `visualZooKeeper.configureServer`
- `visualZooKeeper.addNode`
- `visualZooKeeper.viewNodeStat`
- `visualZooKeeper.copyPath`

## Development

Follow the vscode extension documentation: https://code.visualstudio.com/api/get-started/your-first-extension 

- Install node.js and Git
- `npm install -g yo generator-code`
- `npm install -g yarn`
- `yarn` to install the project dependencies
- Use vsce to build the .vsix file for installation https://code.visualstudio.com/api/working-with-extensions/publishing-extension 
    - `npm install -g @vscode/vsce`
    - Build with `vsce package`


## Release Notes

### 1.0.4

- Alphabetized ZK nodes in explorer
- Default language setting for nodes without extension
- Default ZK host configured on startup

### 1.0.0

Initial release of Visual ZooKeeper
