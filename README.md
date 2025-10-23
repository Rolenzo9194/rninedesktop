# rninedesktop

Project rninedesktop is a fast Min fork that protects your privacy. It includes an interface designed to minimise distractions, and features such as:

- Full-text search for visited pages
- Ad and tracker blocking
- Automatic reader view
- Tasks (tab groups)
- Bookmark tagging
- Password manager integration
- Dark theme

Download rninedesktop from the [releases page](https://github.com/Rolenzo9194/rninedesktop/releases).




## Screenshots

<img alt="The search bar, showing information from DuckDuckGo" src="http://minbrowser.org/tour/img/searchbar_duckduckgo_answers.png" width="650"/>

<img alt="The Tasks Overlay" src="http://minbrowser.org/tour/img/tasks.png" width="650"/>

<img alt="Reader View" src="https://user-images.githubusercontent.com/10314059/53312382-67ca7d80-387a-11e9-9ccc-88ac592c9b1c.png" width="650"/>

## Installing

You can find prebuilt binaries for rninedesktop [here](https://github.com/Rolenzo9194/rninedesktop/releases). Alternatively, skip to the section below for instructions on how to build rninedesktop directly from source.

### Installation on Linux

- To install the .deb file, use `sudo dpkg -i /path/to/download`
- To install the RPM build, use `sudo rpm -i /path/to/download --ignoreos`

## Getting Started

* The [wiki](https://github.com/minbrowser/min/wiki) provides an overview of the the features available in rninedesktop, a list of available keyboard shortcuts, and answers to some [frequently asked questions](https://github.com/minbrowser/min/wiki/FAQ).
* rninedesktop supports installing userscripts to extend its functionality. See the [userscript documentation](https://github.com/minbrowser/min/wiki/userscripts) for instructions on writing userscripts, as well as a collection of scripts written by the community.
* If you have questions about using rninedesktop, need help getting started with development, or want to talk about what we're working on, join our [Discord server](https://discord.gg/bRpqjJ4).

## Developing

If you want to develop rninedesktop:

- Install [Node](https://nodejs.org).
- Run `npm install` to install dependencies.
- Start rninedesktop in development mode by running `npm run start`.
- After you make changes, press `alt+ctrl+r` (or `opt+cmd+r` on Mac) to reload the browser UI.

### Building binaries

In order to build rninedesktop from source, follow the installation instructions above, then use one of the following commands to create binaries:

- `npm run buildWindows`
- `npm run buildMacIntel`
- `npm run buildMacArm`
- `npm run buildDebian`
- `npm run buildRaspi` (for 32-bit Raspberry Pi)
- `npm run buildLinuxArm64` (for 64-bit Raspberry Pi or other ARM Linux)
- `npm run buildRedhat`

Depending on the platform you are building for, you may need to install additional dependencies:

- If you are building a macOS package, you'll need to install Xcode and the associated command-line tools. You may also need to set your default SDK to macOS 11.0 or higher, which you can do by running `export SDKROOT=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX11.1.sdk`. The exact command will depend on where Xcode is installed and which SDK version you're using.
- To build on Windows, you'll need to install Visual Studio. Once it's installed, you may also need to run `npm config set msvs_version 2019` (or the appropriate version).

## Contributing to rninedesktop

Thanks for taking the time to contribute to rninedesktop!

### Getting Help

If you're experiencing a bug or have a suggestion for how to improve rninedesktop, please open a [new issue](https://github.com/Rolenzo9194/rninedesktop/issues/new/choose).

### Contributing Code

- Start by following the development instructions listed above.
- The wiki has an [overview of rninedesktop's architecture](https://github.com/minbrowser/min/wiki/Architecture).
- rninedesktop uses the [Standard](https://github.com/feross/standard) code style; [most editors](https://standardjs.com/#are-there-text-editor-plugins) have plugins available to auto-format your code.
- If you see something that's missing, or run into any problems, please open an issue!
- Thanks to PalmerAL and Min Browser for the open-source nature.
