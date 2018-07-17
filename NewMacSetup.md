- Install stuff from Mac store (bear/magnet/...)

- [git](https://git-scm.com/download/mac)
  - set it up with multiple config if needed
  ```sh
  # ~/.gitconfig
  [user]
  name = Nam Nguyen
  
  [includeIf "gitdir:~/github/"]
  path = ~/.gitconfig-personal
  
  [includeIf "gitdir:~/github/workstuff"]
  path = ~/.gitconfig-work
  
  # ~/.gitconfig-personal
  email = personal@email.com
  
  # ~/.gitconfig-work
  email = work@email.com
  ```
  - [use personal access token for private github](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)


- zshell with prezto
  - https://github.com/sorin-ionescu/prezto
  - prompt -h steeeef
  
- iterm2
  - Profiles
    - Terminal
      - Unlimited scrollback
  - Apperance
    - Theme: Dark
    - Show per-pane title bar with split panes: False

- docker

- nvm
  - https://github.com/creationix/nvm

- OSX
  - Preferences
    - Keyboard/shortcuts - turn off all the unused shortcuts (everything except for Screenshots)
  -   