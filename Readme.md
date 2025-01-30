# DevContainer Configuration For Web Development

This my personal setup DevContainer to provide a consistent development environment. Below are the details of the environment stack, VSCode extensions, and tools included in this configuration.

## Environment Stack

- **Base Image**: `mcr.microsoft.com/devcontainers/php:1-8.2-bookworm`
- **PHP**: Version 8.2
  - Extensions: `mysqli`, `pdo`, `pdo_mysql`, `intl`, `zip`
- **MariaDB**: Version 10.4
- **Node.js**: Latest LTS version (20.x)
- **Python**: Version 3.x
- **ngrok**: Version 3

## VSCode Extensions

The following VSCode extensions are included in the DevContainer configuration to enhance the development experience:

- `cweijan.vscode-database-client2`: Database Client
- `bradlc.vscode-tailwindcss`: Tailwind CSS IntelliSense
- `Vue.volar`: Vue Language Features
- `msjsdiag.vscode-react-native`: React Native Tools
- `dsznajder.es7-react-js-snippets`: React/Redux/GraphQL/React-Native snippets
- `esbenp.prettier-vscode`: Prettier - Code formatter
- `alfredbirk.tailwind-documentation`: Tailwind CSS Documentation
- `mhutchie.git-graph`: Git Graph
- `xdebug.php-debug`: PHP Debug
- `ryannaddy.laravel-artisan`: Laravel Artisan
- `svelte.svelte-vscode`: Svelte for VS Code

## Tools

The following tools are installed in the DevContainer:

- **MariaDB Client**: For interacting with MariaDB databases.
- **Node.js and npm**: For JavaScript development.
- **Python 3 and pip**: For Python development.
- **ngrok**: For secure introspectable tunnels to localhost.

## Usage

To use this DevContainer configuration, ensure you have Docker and VSCode with the Remote - Containers extension installed. Open the project in VSCode and it will prompt you to reopen the folder in the container.

For more information on DevContainers, visit the [DevContainers documentation](https://code.visualstudio.com/docs/remote/containers).
