# My Changes

## build

根据[资料](https://github.com/LuaLS/vscode-lua/wiki/Build) 修改如下：

- Install sumneko.lua in VSCode
- Install extension-path in VSCode
- Install ninja
- Clone source code

```cmd
git clone https://github.com/sumneko/vscode-lua
cd vscode-lua
git submodule update --init --recursive
cd server
make.bat
```

Open repo and execute tasks in VSCode

1. PreCompile
1. Compile
1. Install

Restart VSCode and open your lua project. Enjoy!

## Change Log

1. change icon
1. change author
	"author": "sumneko", ---> "jack"

1.