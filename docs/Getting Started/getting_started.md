# Getting Started

The best way to download yoyoengine, is to install the :simple-github: [yoyoengine hub](https://github.com/yoyoengine/launcher) and use it to manage your editor installations.


!!! warning
    yoyoengine is under ***active development*** and may be unstable. Your bug reports help!

![yoyoengine hub](https://raw.githubusercontent.com/yoyoengine/launcher/main/.github/media/gui_example.png)

Check out the above repo for additional installation methods, but here is a one liner to install on linux:

```bash
curl -sL https://raw.githubusercontent.com/yoyoengine/launcher/main/install.sh | sudo bash
```

## Dependencies

The launcher should warn you if you are missing any dependencies, but here is a command to install the necessary packages for debian based systems:

```bash
sudo apt update && sudo apt install git cmake make gcc g++ curl zenity
```

If you wish to build for windows and web, you will also need to install the following packages:

```bash
sudo apt install mingw-w64 g++-mingw-w64 gcc-mingw-w64
```

As well as [emscripten](https://emscripten.org/docs/getting_started/downloads.html) for web builds.

## Wrap up

Once you've installed the hub, you can launch it and click "install" on your preferred version of yoyoeditor. The hub will then download and install it, and from there you can launch it directly from the hub.

After launching yoyoeditor, it should be self explanatory to create and build a project. If you have any questions, feel free to ask in the :simple-github: [yoyoengine editor](https://github.com/yoyoengine/yoyoeditor) repo!

Please note, **this documentation is by no means exhaustive or comprehensive**. Please feel free to reach out for help or clarification on anything. I'm more than happy to help you out!
