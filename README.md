# VS Code Dev Containers Multi-Language

## git sync Dev Containers repo

```
# 强制重置子模块状态
git submodule deinit -f --all

# 
git submodule update --init --recursive
```

## git add submodule

```
git submodule add https://github.com/microsoft/vscode-remote-try-node node

git submodule add https://github.com/microsoft/vscode-remote-try-python python

git submodule add https://github.com/microsoft/vscode-remote-try-go go

git submodule add https://github.com/microsoft/vscode-remote-try-java java

git submodule add https://github.com/microsoft/vscode-remote-try-dotnet dotnet

git submodule add https://github.com/microsoft/vscode-remote-try-rust rust

git submodule add https://github.com/microsoft/vscode-remote-try-cpp cpp

git submodule add https://github.com/microsoft/vscode-remote-try-php php
```

This repository contains multiple language samples for VS Code Dev Containers.

## Sample Projects

If you want to try a sample project which already has a Dev Container, check out one of the following repositories:

- [Node Sample](https://github.com/microsoft/vscode-remote-try-node)
- [Python Sample](https://github.com/microsoft/vscode-remote-try-python)
- [Go Sample](https://github.com/microsoft/vscode-remote-try-go)
- [Java Sample](https://github.com/microsoft/vscode-remote-try-java)
- [.NET Core Sample](https://github.com/microsoft/vscode-remote-try-dotnet)
- [Rust Sample](https://github.com/microsoft/vscode-remote-try-rust)
- [C++ Sample](https://github.com/microsoft/vscode-remote-try-cpp)
- [PHP Sample](https://github.com/microsoft/vscode-remote-try-php)

## Dev Containers Repository

For more information about VS Code Dev Containers, visit the official repository:
[https://github.com/microsoft/vscode-dev-containers](https://github.com/microsoft/vscode-dev-containers)