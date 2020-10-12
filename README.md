# cugraph-vscode
Visual Studio Code configuration files for developing [RAPIDS.ai/cuGraph](https://github.com/rapidsai/cugraph)


  
## Included
 - `tasks.json`: Configurations for build (cmake, make, cython) and test (gtest pytest) tasks.
 - `cugraph.code-workspace`: Settings, file associations/exclusions, search path

## Tasks install
  1. Copy (or merge) the the contents of the `.vscode` directory into your `cugraph/.vscode` directory.
  2. Update `tasks.json` with your local path to conda `activate`
  3. `mkdir cpp/build`
  4. Try Command+Shift+B
  
## Auto C++ format with clangd
  - Install clangd on the machine (`sudo apt-get install clangd-9` for Ubuntu) and vscode plugin `llvm-vs-code-extensions.vscode-clangd`. 
  - set `“clangd.path”` to the correct path in `cugraph.code-workspace`.

## Auto Python format with Black
- `pip install black`
- In VSCode:
  - `Ctrl+Comma` search for `Python Formatting Black` 
  - make sure `Python › Formatting: Black Path` is set to the correct location and review options

## Useful packadges

Code
- llvm-vs-code-extensions.vscode-clangd
- ms-python.python
- kriegalex.vscode-cudacpp
- ms-vscode.cmake-tools
- tcwalther.cython

Remote work
- ms-vscode-remote.remote-ssh
- ms-vscode-remote.remote-ssh-edit

Other
- streetsidesoftware.code-spell-checker
- github.vscode-pull-request-github

## To do
  - debug configuration
