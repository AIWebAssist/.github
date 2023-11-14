# Browser Assistant

Welcome to the Browser Assistant project! This project consists of a Chrome extension and a server-side component designed to enhance your browsing experience by providing intelligent assistance based on the user goal and web page content.

## Repository Organization

### 1. [Chrome Extension Repo](https://github.com/AIWebAssist/AIWebAssistExtension)

This repository contains the code for the Chrome extension. The structure is organized as follows:

- **`shared`**: Directory with the scripts that is loaded to the tab and used to extract information from the page and direct the user to the action.

- **`background.js`**: Script managing background functionality.

- **`content.js`**: Script handling content-related tasks.

- **`content_main.js`**: Script for the main content functionality.

- **`main.css`**: Stylesheet for the extension.

- **`main.html`**: HTML file defining the extension's main structure.

- **`main.js`**: Main script for extension functionality.

- **`manifest.json`**: Configuration file defining the extension's properties.

### 2. [Backend Repo](https://github.com/AIWebAssist/AIWebAssistServer)

This repository contains the server-side logic for processing user input and web page information. The organization is structured as follows:

Files to define docker / dev container:
- **`.devcontainer`**: Configuration for development container settings.

- **`.vscode`**: VSCode-specific settings, including launch configurations.

- **`Dockerfile`**: Configuration file for building a Docker image.
  
- **`docker-compose.yaml`**: Docker Compose configuration for easy deployment.

- **`requirements-dev.txt`**: List of development dependencies.

- **`requirements.txt`**: List of dependencies for the server.

Main logic files:
- **`examples`**: Directory containing usage examples.

- **`scrape_anything`**: Directory that contains the entire logic to process the request.




## Getting Started

Follow these steps to set up the Browser Assistant:

1. Clone the [Chrome Extension Repo](https://github.com/AIWebAssist/AIWebAssistExtension) to your local machine.
2. TBD: Modify the backend url.
3. Load the extension in Chrome by navigating to `chrome://extensions/` and selecting "Load unpacked." Choose the extension directory.
4. Clone the [Backend Repo](https://github.com/AIWebAssist/AIWebAssistServer) to your local machine.
5. TBD: start the backend using docker.

## Usage

Once both the Chrome extension and backend server are running, open Chrome and use the extension to input your queries. The extension will communicate with the backend, and you'll receive intelligent assistance based on the web page content and your input.

## Contributing

If you'd like to contribute to the development of Browser Assistant, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
