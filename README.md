# Template for building JUCE plugins and apps in with VSCode

# Required Extensions
- C/C++
- CMake
- CMake Tools

# Usage
- click "Use this template" on github
- clone newly created repo and init submodules (git submodule update --init --recursive)
- open workspace with vscode (.vscode/JUCE-template.code-workspace) and check that you can
  - configure CMake (search for CMake configure in vscode command pallete)
  - build project
  - run/ debug project (play/ bug button at bottom of vscode). Window may appear behind vscode window
- rename folder & workspace file to your project name
- in CMakeLists.txt replace all "JUCE_TEMPLATE" / "juce template" etc. with your project name
- search and replace JUCEtemplate with yourProjectName
- check CMake configure/ build/ run still work
- happy days, develop whatever you want

# Info
- need to build with cmake to generate build/compile_commands.json which allows intellisense to work properly (jump to definition, autocomplete etc.)