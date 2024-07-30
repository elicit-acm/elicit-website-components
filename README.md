# Elicit Website Components

Welcome to the **Elicit Website Components** repository! This project is a collaborative effort to create reusable and responsive components for a website, using React and Tailwind CSS.

## Table of Contents
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Code Guidelines](#code-guidelines)
- [Branching Strategy](#branching-strategy)
- [Naming Conventions](#naming-conventions)
- [Resources](#resources)

## Getting Started

To get started with development, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/[your-username]/elicit-website-components.git

2. **Navigate to the project directory:**
   ```bash
   cd elicit-website-components

3. **Install the dependencies:**
   ```bash
   npm install
   
4. **Start the development server:**
   ```bash
    npm run dev
   
5. **Open the project in your browser:**
6. **Make changes to the codebase and see the changes live!**

## Contributing

We welcome contributions from everyone! To contribute:

1. **Fork the repository.**

2. **Create a new branch with your name.**  
   Example:  
   ```bash
   git checkout -b your-name

3. **Make your changes.**
4. **Commit your changes.**
   ```bash
   git commit -m "Add [description of your changes]"

5. **Push your changes to your branch.**
   ```bash
    git push origin your-name

6. **Create a pull request to the main branch**
7. **Wait for your pull request to be reviewed and merged!**

## Code Guidelines

- **Component Structure:**
  - Use functional components.
  - Use hooks for state and side effects.
  - Each component should be in its own folder with a `.jsx` file and a corresponding `.css` file if needed.

- **Styling:**
  - Use Tailwind CSS utility classes.
  - Avoid using inline styles unless absolutely necessary.
  - Custom styles should be defined in a `.css` file using Tailwind's `@apply` directive.

- **Responsiveness:**
  - Ensure components are responsive and work well on different screen sizes.
  - Use Tailwind's responsive utility classes.

## Branching Strategy

1. **Main Branch:**
   - The `main` branch contains the stable version of the project.

2. **Feature Branches:**
   - Create branches using your name only (e.g., `lalit-rao`).

3. **Bug Fix Branches:**
   - Use your name for bug fix branches as well.

## Naming Conventions

- **Component Names:**
  - Use PascalCase for component names (e.g., `HeaderComponent`).

- **File Names:**
  - Use PascalCase for file names (e.g., `HeaderComponent.jsx`, `HeaderComponent.css`).

- **CSS Classes:**
  - Use descriptive names that reflect the purpose of the class.
  - Follow BEM (Block Element Modifier) naming convention where applicable.

## Resources

- [React Documentation](https://react.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Vite Documentation](https://vitejs.dev/guide/)
