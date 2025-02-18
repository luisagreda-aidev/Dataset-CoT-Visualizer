# Chain-of-Thought Dataset Visualizer

Chain-of-Thought Dataset Visualizer is an open-source application designed to facilitate the visualization and management of datasets containing chain-of-thought reasoning processes. This tool is particularly valuable for researchers and developers working with large language models and natural language processing tasks, enabling them to explore and interact with datasets efficiently.

## Key Features

- **Dataset Management**: Easily load, view, and manage multiple JSON datasets. The application supports seamless integration of new datasets, allowing users to switch between them effortlessly.
- **Example Browsing**: Navigate through examples within the dataset with intuitive pagination controls. Each example includes detailed views of the question, reasoning process, and response.
- **Search Functionality**: Utilize the search bar to filter examples based on keywords in the question or reasoning process, making it easy to locate specific data points.
- **Editable Content**: Double-click to edit questions, reasoning processes, or responses directly within the interface. Changes are saved instantly, allowing for quick iterations and corrections.
- **Multilingual Support**: The application is available in multiple languages, ensuring broader accessibility for users around the world.
- **Cross-Platform Compatibility**: Available for macOS, Windows, and Linux, ensuring that users can access the tool regardless of their operating system.

## Installation Guide

### Prerequisites

- Ensure you have Node.js and npm installed on your system. You can download them from [nodejs.org](https://nodejs.org/).

### Steps to Install

1. **Download the Application**:
   - Visit the [releases page](https://github.com/your-repo/chain-of-thought-visualizer/releases) and download the appropriate installer for your operating system.

2. **Install the Application**:
   - **Windows**: Run the downloaded `.exe` file and follow the on-screen instructions to complete the installation.
   - **macOS**: Open the downloaded `.dmg` file and drag the application to your Applications folder.
   - **Linux**: Make the downloaded `.AppImage` file executable and run it from your terminal or file manager.

## For Developers

If you are a developer and wish to modify the application's code or run it in a development environment, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/chain-of-thought-visualizer.git
   cd chain-of-thought-visualizer
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```
   This command installs all the necessary Node.js modules required to run the application.

3. **Start in Development Mode**:
   ```bash
   npm start
   ```
   Running this command will start the application in development mode. This mode allows you to make changes to the code and see them reflected in the application in real-time with automatic reloading. This is ideal for development and debugging.

4. **Package the Application for Distribution**:
   ```bash
   npm run package
   ```
   When you are ready to build distributable packages for macOS, Windows, and Linux, run this command. It will package the application into platform-specific installers (like `.exe`, `.dmg`, and `.AppImage`) that you can then distribute to end-users.

## Usage Instructions

1. **Launch the Application**:
   - Open the installed application from your applications menu or desktop shortcut.

2. **Load a Dataset**:
   - Click on the "Cargar Nuevo Dataset" button to open a file dialog.
   - Select the JSON file containing your dataset to load it into the application.

3. **Browse Examples**:
   - Use the pagination controls to navigate through the examples in the dataset.
   - Click on an example to view its details, including the question, reasoning process, and response.

4. **Search for Examples**:
   - Use the search bar to filter examples based on keywords in the question or reasoning process. This feature helps in quickly locating specific examples within large datasets.

5. **Edit Content**:
   - Double-click on the question, reasoning process, or response to make it editable.
   - Make your changes and click outside the text area to save them. This feature is useful for correcting errors or updating information within the dataset.

6. **Manage Datasets**:
   - Load multiple datasets and switch between them using the dataset manager.
   - Delete datasets that are no longer needed to keep your workspace organized.

## Sample Dataset

This application includes a sample dataset that is fully functional for training Chain-of-Thought (CoT) large reasoning models. The dataset is designed to support fine-tuning, agent creation, and advanced reasoning systems, making it a valuable resource for researchers and developers working on NLP tasks.

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the Apache License 2.0. For more details, see the [LICENSE](LICENSE) file.

## Acknowledgments

- This project was inspired by the need for better tooling in the NLP research community.
- Built with Electron, Node.js, and a passion for open-source software.
- Developed by Luis Agreda. You can connect with him on [LinkedIn](https://www.linkedin.com/in/luis-agreda-artificial-intelligence-engineer/).

## Additional Works

- Explore Luis Agreda's other projects, such as [Tu Asesor Legal Virtual](https://tuasesorlegalvirtual.online), which showcases his expertise in artificial intelligence and software development.

---

This README provides a comprehensive guide on how to install and use the Chain-of-Thought Dataset Visualizer, making it accessible for users across different platforms. It also highlights the developer's contributions and additional works, providing context and recognition for the efforts behind the project.
=======
# Dataset-CoT-Visualizer
Chain-of-Thought Dataset Visualizer is an open-source application designed to facilitate the visualization and management of datasets containing chain-of-thought reasoning processes. 
