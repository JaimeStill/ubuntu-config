# Apps

* curl
    ```bash
    sudo apt install curl
    ```
* [Visual Studio Code](https://code.visualstudio.com/docs/setup/linux)

    ```bash
    sudo snap install --classic code
    ```

* [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-365/microsoft-teams/download-app)

* [Google Chrome](https://www.google.com/chrome/)

* [Spotify](https://www.spotify.com/us/download/linux/)

    ```bash
    wget -O- https://download.spotify.com/debian/pubkey.gpg | sudo apt-key add -

    sudo add-apt-repository "deb http://repository.spotify.com stable non-free"

    sudo apt install spotify-client
    ```

* [Git](https://git-scm.com/download/linux)

    ```bash
    sudo add-apt-repository ppa:git-core/ppa
    sudo apt update
    sudo apt install git
    ```

    * `git config --global credential.helper store` - store git credentials

* [Discord](https://discord.com/download)

* [.NET Core SDK](https://docs.microsoft.com/en-us/dotnet/core/install/linux-package-manager-ubuntu-1910)

    ```bash
    wget https://packages.microsoft.com/config/ubuntu/19.10/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
    
    sudo dpkg -i packages-microsoft-prod.deb

    sudo apt-get update
    
    sudo apt-get install apt-transport-https

    sudo apt-get update

    sudo apt-get install dotnet-sdk-3.1
    ```

* [Node.js](https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions)

    ```bash
    curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -

    sudo apt-get install -y nodejs
    ```

* [Yarn](https://classic.yarnpkg.com/en/docs/install#debian-stable)

    ```bash
    curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
   
    echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

    sudo apt update && sudo apt install yarn
    ```

* [rEFInd](https://www.rodsbooks.com/refind/installing.html)

    > [AskUbuntu - Any Downside to Using rEFInd Instead of GRUB](https://askubuntu.com/questions/760875/any-downside-to-using-refind-instead-of-grub)

    ```bash
    sudo apt-add-repository ppa:rodsmith/refind

    sudo apt-get update

    sudo apt-get install refind
    ```

    > [rEFInd-ultra](https://github.com/JaimeStill/rEFInd-ultra)