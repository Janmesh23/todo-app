# Todo App

A simple, elegant todo list application built with React. Keep track of your tasks with an intuitive interface that lets you add, complete, and delete todos.

## Features

- ✅ Add new todos
- ✅ Mark todos as complete/incomplete
- ✅ Delete todos
- ✅ View todo statistics (total and completed count)
- ✅ Responsive design with a modern dark theme
- ✅ Keyboard support (press Enter to add todos)
- ✅ Visual feedback for completed tasks

## Demo

The app features:
- Clean, modern interface with a dark theme
- Real-time statistics showing total and completed todos
- Smooth hover effects and transitions
- Strikethrough text for completed todos
- Color-coded borders (blue for active, green for completed)

## Technologies Used

- **React 19.1.0** - Frontend framework
- **React Hooks** - State management (useState)
- **CSS3** - Styling and animations
- **Create React App** - Build tooling

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Janmesh23/todo-app.git
   cd todo-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Available Scripts

### `npm start`
Runs the app in development mode. The page will reload when you make changes.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder. The build is minified and optimized for best performance.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you can't go back!**

If you need to customize the build configuration, you can eject at any time.

## Usage

1. **Adding a Todo**: Type your task in the input field and either click "Add Todo" or press Enter
2. **Completing a Todo**: Click the checkbox next to any todo to mark it as complete
3. **Deleting a Todo**: Click the "Delete" button to remove a todo
4. **Viewing Statistics**: Check the bottom of the app to see your total and completed todo counts

## Project Structure

```
todo-app/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── App.js          # Main application component
│   ├── App.css         # Application styles
│   ├── index.js        # Application entry point
│   └── ...
├── package.json
└── README.md
```

## Key Components

- **App.js**: Main component containing all todo logic and UI
- **State Management**: Uses React hooks for managing todos and input state
- **Event Handlers**: Functions for adding, deleting, and toggling todos
- **Responsive Design**: CSS flexbox layout that works on all screen sizes

## Styling

The app uses a modern dark theme with:
- Dark background (#282c34)
- Accent color (#61dafb)
- Visual feedback for interactions
- Smooth transitions and hover effects

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Future Enhancements

Possible improvements:
- Local storage persistence
- Todo categories/tags
- Due dates
- Priority levels
- Search and filter functionality
- Drag and drop reordering
- Dark/light theme toggle
