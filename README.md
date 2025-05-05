# create-etc-stack

[![npm version](https://badge.fury.io/js/create-etc-stack.svg)](https://badge.fury.io/js/create-etc-stack)

Quickly scaffold new, opinionated project structures suitable for medium-sized applications, enforcing strong specifications and best practices from the start.

## Features

* **Rapid Setup:** Get your project running in seconds with interactive prompts.
* **Opinionated Templates:** Start with well-defined structures and configurations.
* **Strong Specifications:** Includes configurations for tools like TypeScript, Biome (linter/formatter), and Tailwind CSS (in specific templates) to ensure code quality and consistency.
* **Focus on Modern Frameworks:** Currently provides templates tailored for modern web development (React focused initially).

## Getting Started

To create a new project, run the following command in your terminal:

```bash
npx create-etc-stack@latest your-project-name
```

Or using npm:

```bash
npm create aim@latest your-project-name
```

Or using yarn:

```bash
yarn create aim your-project-name
```

Or using pnpm:

```bash
pnpm create aim your-project-name
```

Or using bun:

```bash
bun create aim your-project-name
```

This will launch an interactive setup process where you can choose your desired template.

## Available Templates

* **`react-ts-biome-tailwind`**: A robust starting point for React projects using TypeScript, Biome for linting/formatting, and Tailwind CSS for styling. (Note: Ensure this template is available and uncommented in `src/index.ts`)
* Other community/official starters via custom commands (e.g., React Router, TanStack Router).

*(More templates might be available, check the interactive prompt for the full list)*

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.
