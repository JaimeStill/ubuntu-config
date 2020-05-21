# Setup

* Remove Desktop Icons

    ```bash
    sudo apt install gnome-tweak-tool
    ```

    > Open **Tweaks** app. `Extensions -> Desktop Icons Settings`

* [Install Third-Party Codecs & Extras](https://linuxconfig.org/things-to-do-after-installing-ubuntu-20-04-focal-fossa-linux#h3-3-install-third-party-codecs-extras)

    ```bash
    sudo apt install ubuntu-restricted-extras
    ```

* [Install Microsoft Fonts](https://linuxconfig.org/install-microsoft-fonts-on-ubuntu-20-04-focal-fossa-desktop)

    ```bash
    sudo apt install ttf-mscorefonts-installer

    sudo fc-cache -vr
    ```

* [Docker](https://linuxconfig.org/how-to-install-docker-on-ubuntu-20-04-lts-focal-fossa)

    ```bash
    sudo apt install docker.io

    sudo systemctl enable --now docker

    sudo usermod -aG docker SOMEUSERNAME

    docker --version

    docker run hello-world
    ```

* [Docker Compose](https://linuxconfig.org/how-to-install-docker-compose-on-ubuntu-20-04-focal-fossa-linux)

    ```bash
    sudo apt install docker-compose

    docker-compose version
    ```

* [Kubernetes](https://linuxconfig.org/how-to-install-kubernetes-on-ubuntu-20-04-focal-fossa-linux)

    > Not installed, just here for future reference