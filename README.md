# Todo List Application

A minimalist and responsive Todo List application built with **React.js**, **Vite**, and **Tailwind CSS**. The app enables users to add, edit, delete, and search tasks with real-time updates, featuring a user-friendly interface designed based on a **Figma** layout. It includes a light/dark theme toggle for enhanced user customization. Optimized state management ensures seamless performance and an engaging user experience.

## Features
- **Task Management**: Add, edit, and delete tasks effortlessly.
- **Search Functionality**: Quickly locate tasks with real-time search.
- **Real-Time Updates**: Instant feedback on task modifications.
- **Theme Toggle**: Switch between light and dark modes for a personalized experience.
- **Responsive Design**: Adapts to various screen sizes and devices.
- **Modern UI**: Clean and intuitive interface styled with Tailwind CSS, based on a Figma design.
- **Optimized Performance**: Efficient state management for a smooth experience.

## Tech Stack
- **Frontend**: React.js, Vite, Tailwind CSS
- **Design**: Figma-based UI
- **State Management**: React hooks for efficient updates

## Prerequisites
Before setting up the project, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- A modern web browser for testing

## Installation

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AmeneAhmadi/todo-list-app.git
   cd todo-list-app
   ```

2. **Install Dependencies**:
   Using npm:
   ```bash
   npm install
   ```
   Or using yarn:
   ```bash
   yarn install
   ```

3. **Set Up Tailwind CSS** (if not pre-configured):
   If Tailwind CSS needs initialization, run:
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```
   Update `tailwind.config.js` to include your content paths and enable dark mode:
   ```js
   module.exports = {
     content: ["./src/**/*.{js,jsx,ts,tsx}"],
     darkMode: 'class', // Enables class-based dark mode
     theme: { extend: {} },
     plugins: [],
   };
   ```
   Ensure Tailwind directives are added to your CSS file (e.g., `src/index.css`):
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

4. **Run the Development Server**:
   Start the Vite development server:
   ```bash
   npm run dev
   ```
   Or with yarn:
   ```bash
   yarn dev
   ```
   The app will be available at `http://localhost:5173` (or another port if specified).

5. **Build for Production** (optional):
   Create a production-ready build:
   ```bash
   npm run build
   ```
   The output will be in the `dist` folder.

## Usage
- Open the app in your browser.
- Add, edit, or delete tasks, and use the search bar to filter them.
- Toggle between light and dark themes to customize the appearance.
- Enjoy a clean, responsive interface inspired by a Figma design.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.
