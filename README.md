# Drag-and-Drop Low-Code Website Builder - Frontend Repository

This repository contains the frontend codebase for the Drag-and-Drop Low-Code Website Builder project. The application is designed to empower users to create websites effortlessly by utilizing a drag-and-drop interface and pre-defined components.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Setup and Installation](#setup-and-installation)
- [Development Guidelines](#development-guidelines)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
The frontend of the Drag-and-Drop Low-Code Website Builder is built to provide users with a seamless, intuitive interface for designing web pages using pre-built components. This repository implements the user interface, interaction logic, and API integrations with the backend.

---

## Tech Stack
- **React.js**: Core framework for building the user interface.
- **TypeScript**: Adds type safety to the codebase.
- **Redux Toolkit**: Manages application state efficiently.
- **Tailwind CSS**: Used for styling and creating a responsive design.
- **React DnD**: Implements the drag-and-drop functionality.
- **Axios**: Handles API requests and responses.
- **ESLint & Prettier**: Ensures code quality and consistency.

---

## Features
- **Drag-and-Drop Interface**: Users can drag and position components on a canvas.
- **Component Library**: A collection of pre-built, customizable components.
- **Responsive Design**: Automatically adjusts for different screen sizes.
- **Export to HTML/CSS**: Generate clean, exportable HTML/CSS code for designed pages.
- **Undo/Redo Functionality**: Navigate through changes made on the canvas.
- **Integration with Backend**: Fetch templates and save user designs.

---

## Folder Structure
```
frontend/
├── public/               # Static assets
├── src/
│   ├── assets/           # Images, icons, etc.
│   ├── components/       # Reusable React components
│   ├── features/         # Redux slices and feature logic
│   ├── hooks/            # Custom hooks
│   ├── layouts/          # Page layouts
│   ├── pages/            # Individual page components
│   ├── services/         # API service integrations
│   ├── styles/           # Global and shared styles
│   ├── utils/            # Utility functions and helpers
│   └── App.tsx           # Root component
├── .env                  # Environment variables
├── .eslintrc.js          # ESLint configuration
├── .prettierrc           # Prettier configuration
├── package.json          # Project dependencies
└── tsconfig.json         # TypeScript configuration
```

---

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-org/drag-drop-builder-frontend.git
   cd drag-drop-builder-frontend
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Setup Environment Variables:**
   Create a `.env` file in the root directory and configure the following variables:
   ```env
   REACT_APP_API_BASE_URL=https://api.example.com
   ```

4. **Run the Application:**
   ```bash
   npm start
   ```

5. **Build for Production:**
   ```bash
   npm run build
   ```

---

## Development Guidelines

- **Branch Naming:** Use the following convention for branch names:
  - `feature/<feature-name>` for new features.
  - `fix/<bug-name>` for bug fixes.
  - `hotfix/<issue-name>` for urgent fixes.

- **Code Quality:**
  - Run `npm run lint` to check for linting issues.
  - Format your code using Prettier before committing changes.

- **Commit Messages:** Use meaningful commit messages:
  - `feat: Add drag-and-drop functionality`
  - `fix: Resolve button alignment issue`

- **Testing:** Write unit tests for new components and features.

---

## Contributing
We welcome contributions from the community! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

---

## License
This project is licensed under the [MIT License](LICENSE).
