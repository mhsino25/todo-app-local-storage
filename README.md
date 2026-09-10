# To-Do List Application

A modern, responsive to-do list application with local storage functionality. All your tasks are saved locally in your browser and persist across sessions.

## Features

✨ **Core Functionality**
- ✅ Add, complete, and delete tasks
- 💾 Automatic local storage persistence
- 🔄 Real-time task counter
- 🎯 Filter tasks (All, Active, Completed)
- 🧹 Clear all completed tasks at once
- 📱 Fully responsive design
- ⌨️ Keyboard support (Enter key to add)

## How to Use

1. **Add a Task**: Type your task in the input field and click "Add Task" or press Enter
2. **Complete a Task**: Check the checkbox next to a task to mark it as complete
3. **Delete a Task**: Click the "Delete" button to remove a task
4. **Filter Tasks**: Use the filter buttons to view All, Active, or Completed tasks
5. **Clear Completed**: Click "Clear Completed" to remove all finished tasks

## Local Storage

All tasks are automatically saved to your browser's local storage. This means:
- Your tasks persist even after closing the browser
- No server required
- No account needed
- Data stays on your device

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No dependencies
- **Local Storage API** - Data persistence

### Browser Support
- Chrome 4+
- Firefox 3.5+
- Safari 4+
- IE 8+
- Mobile browsers (iOS Safari, Chrome Mobile, etc.)

## File Structure

```
todo-app-local-storage/
├── index.html      # Main HTML file
├── styles.css      # Styling and animations
├── script.js       # Application logic
└── README.md       # Documentation
```

## Features in Detail

### Task Management
- Each task has a unique ID (timestamp-based)
- Tasks store completion status and creation date
- XSS protection with HTML escaping

### User Interface
- Modern gradient design with purple theme
- Smooth animations and transitions
- Responsive layout for mobile and desktop
- Custom scrollbar styling

### Local Storage Structure
```javascript
// Each task object:
{
  id: 1234567890,           // Unique identifier
  text: "Buy groceries",    // Task description
  completed: false,          // Completion status
  createdAt: "2024-..."     // ISO timestamp
}
```

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/mhsino25/todo-app-local-storage.git
   cd todo-app-local-storage
   ```

2. Open in your browser
   - Simply open `index.html` in any web browser
   - No build process or dependencies needed

## Live Demo

Just open the `index.html` file in your browser to start using the app!

## Security

- Input sanitization to prevent XSS attacks
- No external API calls
- No sensitive data transmission
- All data stays locally in your browser

## License

MIT License - Feel free to use and modify as needed.

## Contributing

Feel free to fork, modify, and submit pull requests!

## Author

Created by mhsino25
