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
  
## Useful packadges

Code
- llvm-vs-code-extensions.vscode-clangd
- ms-python.python
- ms-vscode.cpptools
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
