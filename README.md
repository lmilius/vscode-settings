# vscode-settings

These settings are from my personal preference when switching from pycharm.

I have installed the following VSCode Extentions, some of which can be very useful for Cloudformation templates:

1. Indenticator
1. indent-rainbow
1. EditorConfig for VSCode
    - plus .editorconfig for any yaml files per repo
1. Sort lines
1. vscode-cfn-lint
    - first, `pip install cfn-lint`
1. YAML Support by Red Hat (YAML) author is Red Hat
1. Python
1. IntelliJ IDEA Keybindings
    - Also need to remove keybindings on "alt+left" and "alt+right" for previousEditor and nextEditor so that navigateBack and navigateForward works correctly


copy the following files into the respective directories:
- System settings:
    - settings.json -> ${APP_DATA}\Roaming\Code\User\settings.json
    - python.json -> ${APP_DATA}\Roaming\Code\User\snippets\python.json
    - keybindings.json -> ${APP_DATA}\Roaming\Code\User\keybindings.json
- Per Workspace settings:
    - tasks.json -> repo/.vscode/tasks.json
- Per Repo settings:
    - .editorconfig -> repo/.editorconfig
