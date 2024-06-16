# webMAN MOD - Extensions

This project is designed to enhance your applications by leveraging the functionalities provided in the `WebManExtensions.cs` file. This README will guide you through the main purpose and usage of this project.

## Overview

The **webMAN Extensions** repository contains a set of utilities and extensions encapsulated within the `WebManExtensions.cs` file. These extensions aim to simplify and streamline common tasks in web development, providing you with reusable code to enhance your projects.

## Features

- **Utility Functions**: A collection of helper methods to perform common tasks efficiently.
- **Extension Methods**: Extend the functionality of existing classes to make your code cleaner and more readable.
- **Modular Design**: Easily integrate and use only the components you need.

## Getting Started

To get started with **Webman Extensions**, follow these simple steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ohhsodead/webman-extensions.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd webman-extensions
    ```
3. **Include the `WebManExtensions.cs` file in your project**.

## Usage

To use the functionalities provided by `WebManExtensions.cs`, you need to include it in your project. Here's a quick example:

```csharp
using WebmanExtensions;

class Program
{
    static void Main()
    {
        // Mount a game using the games folder, and then launch it
        WebManExtensions.MountGameFromPath("192.168.0.69", "game-path-here");
        WebManExtensions.Launch("192.168.0.69");

        // Sends a notify message to the console
        WebManExtensions.Notify("192.168.0.69", "Hello, World!");
    }
}
```

## Contributing

We welcome contributions from the community! If you have an idea for an improvement or find a bug, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or need further assistance, please open an issue on the repository or contact me on Discord: ohhsodead

Happy coding!

## Credits
[aldostools](https://github.com/aldostools) for creating the plugin!

---

Thank you for using **Webman Extensions**! We hope it makes your development process more efficient and enjoyable.
