## Choose Architecture To Run Git










    - OSX Terminal App: /Applications/Utilities/Terminal ![image](64px-Terminalicon2.png)
    ```bash
    $ RUNNING_ON_UBUNTU_LINUX_SERVER_20=$( uname -a | grep -i 'ubuntu')
    $ if [ -z ${RUNNING_ON_UBUNTU_LINUX_SERVER_20} ]; then 

      fi
  $ brew doctor || /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  $ brew doctor
  $ brew install git
  $ git config -l
  ```
  - Stand Up + Access Local Ubuntu20Server VM
  ```bash
  $ vagrant init; vagrant up; vagrant ssh
  
  ```

