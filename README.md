# To-Do List App 📝

A simple, beautiful, and functional to-do list application built with **HTML**, **CSS**, and **JavaScript**. Perfect for learning frontend development!

## Features ✨

- ✅ **Add tasks** - Quickly add new to-do items
- 🗑️ **Delete tasks** - Remove tasks you no longer need
- ✔️ **Mark complete** - Check off finished tasks
- 🔍 **Filter tasks** - View All, Active, or Completed tasks
- 💾 **Local storage** - Your tasks persist even after closing the browser
- 📱 **Responsive design** - Works beautifully on desktop and mobile
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations

## Demo

Open `index.html` in your web browser to start using the app!

### Live Demo
You can view this project live on GitHub Pages:
- Add the repo to GitHub Pages settings to see it live

## How to Use

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. **Add tasks** by typing in the input field and pressing Enter or clicking the "Add" button
4. **Check off tasks** by clicking the checkbox when you complete them
5. **Delete tasks** by clicking the "Delete" button
6. **Filter tasks** using the All, Active, and Completed buttons
7. **Clear completed tasks** using the "Clear Completed" button

## Project Structure

```
to-do-list-app/
├── index.html      # HTML structure
├── styles.css      # Styling and animations
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Key Learning Concepts

This project teaches:

- **HTML Semantics** - Proper structure and form elements
- **CSS Styling** - Flexbox, gradients, animations, and responsive design
- **JavaScript DOM Manipulation** - Adding/removing elements, event listeners
- **Local Storage API** - Persisting data in the browser
- **Array Methods** - `filter()`, `map()`, `push()` for managing todos
- **Event Handling** - Click and keyboard events
- **Conditional Rendering** - Showing/hiding elements based on state
- **Data Filtering** - Displaying todos by status

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, animations, gradients
- **JavaScript (Vanilla)** - No frameworks, pure JS
- **Local Storage API** - Browser data persistence

## Features Breakdown

### Add Task
- Press Enter or click the "Add" button
- Input validation prevents empty tasks
- Auto-focus on input after adding

### Complete/Uncomplete
- Click the checkbox to toggle completion
- Completed tasks show strikethrough text
- Updates automatically in local storage

### Delete Task
- Click the "Delete" button to remove a task
- Changes persist in local storage

### Filter Tasks
- **All** - Shows all tasks
- **Active** - Shows only incomplete tasks
- **Completed** - Shows only completed tasks

### Clear Completed
- Removes all completed tasks at once
- Confirmation dialog prevents accidental deletion

## Customization Ideas

Enhance the app with these features:

- 🏷️ **Add categories/tags** to organize tasks
- ⏰ **Add due dates** to tasks
- 📊 **Show task statistics** (total, completed, pending)
- 🎨 **Theme switcher** (dark mode/light mode)
- 🔍 **Search functionality** to find tasks
- 📌 **Priority levels** for tasks (High, Medium, Low)
- 🔊 **Sound notifications** when tasks are completed
- 📤 **Export/Import** tasks to JSON

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Tips for Learning

1. **Read the code** - Understand how each part works
2. **Modify it** - Change colors, fonts, or functionality
3. **Add features** - Implement the customization ideas above
4. **Debug it** - Use browser DevTools to inspect and test
5. **Share it** - Deploy to GitHub Pages and share your portfolio

## File Explanations

### index.html
- Input field and Add button for creating tasks
- Unordered list to display all tasks
- Filter buttons for task status
- Task counter and Clear Completed button

### styles.css
- Modern gradient background
- Smooth animations and transitions
- Responsive layout using Flexbox
- Custom scrollbar styling
- Mobile-friendly design

### script.js
- `addTodo()` - Creates new task
- `deleteTodo(id)` - Removes task
- `toggleComplete(id)` - Marks task as done
- `renderTodos()` - Updates the UI
- `saveTodos()` / `loadTodos()` - localStorage management
- Filter logic for active/completed tasks

## License

This project is open source and available for learning and modification.

---

**Happy Coding! 🚀**

If you found this helpful, please star ⭐ this repository and share it with others learning frontend development!
