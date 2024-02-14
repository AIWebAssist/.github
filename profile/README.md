# Browser Assistant

Welcome to the Browser Assistant project! This project consists of a Chrome extension and a server-side component designed to enhance your browsing experience by providing intelligent assistance based on the user goal and web page content.

## Repository Organization

1. [Chrome Extension Repo](https://github.com/AIWebAssist/AIWebAssistExtension) - this repository contains the code for the Chrome extension. 

2. [Backend Repo](https://github.com/AIWebAssist/AIWebAssistServer) - this repository contains the server-side logic for processing user input and web page information.

## Overall setup:
 - We offer to work with [VScode IDE](https://code.visualstudio.com/) for both project.

 - All of the setup code here is for Linux, if you are using Windows we offer to use [WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

 - While you may not use it, we recommend installing [docker](https://www.docker.com/products/docker-desktop/)

 - For developer we recommend cloning first the extension and then cloning the server and continue the setup for there.

## Running locally.

Follow these steps to set up the Browser Assistant:

1. Clone the [Chrome Extension Repo](https://github.com/AIWebAssist/AIWebAssistExtension) to your local machine.
3. Load the extension in Chrome by navigating to `chrome://extensions/` and selecting "Load unpacked." Choose the `extension` directory.
4. Clone the [Backend Repo](https://github.com/AIWebAssist/AIWebAssistServer) to your local machine.
5. Follow the instruction in the repo README.md to run the server. 

## Usage

Once both the Chrome extension and backend server are running, open Chrome and use the extension to input your queries. The extension will communicate with the backend, and you'll receive intelligent assistance based on the web page content and your input.

## Contributing

If you'd like to contribute to the development of Browser Assistant, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
