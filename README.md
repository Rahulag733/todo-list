# My Daily Tasks - Todo List App

## What's This About?

This is a simple but stylish todo list app I built to help manage daily tasks. It's one of those projects that seems basic at first, but you learn a ton while making it!

I wanted something clean, easy to use, and that actually saves your tasks (because what's the point if you lose everything when you refresh the page, right?). So here it is - a fully functional task manager built with vanilla HTML, CSS, and JavaScript.

## What Can You Do With It?

- **Add Tasks**: Type in what you need to do and hit that Add button (or just press Enter)
- **Mark as Complete**: Click on any task to check it off - feels good, doesn't it?
- **Delete Tasks**: Made a mistake? No worries, just delete it
- **Clear Completed**: Clean up all those finished tasks with one click
- **Persistent Storage**: Your tasks are saved in your browser, so they'll be there even if you close the tab
- **Task Counter**: Always know how many tasks you have left to tackle

## The Tech Stack

Kept it simple and clean:
- **HTML5** - Structure
- **CSS3** - Made it look good with gradients, animations, and a responsive design
- **JavaScript (ES6)** - All the functionality and localStorage magic

## How to Use It

### Super Easy Setup:

1. Clone this repo or download the files:
```bash
git clone https://github.com/Rahulag733/todo-list.git
```

2. Open `index.html` in your browser

3. Start adding tasks!

That's it. No build process, no dependencies, no headaches.

## Features I'm Proud Of

### Design
- Modern gradient background (purple vibes!)
- Smooth hover effects
- Clean, minimalist interface
- Fully responsive - works on your phone too

### Functionality
- LocalStorage integration - your tasks persist
- Real-time task counter
- Keyboard shortcuts (Enter to add tasks)
- Smooth animations when adding/removing tasks

## What I Learned

Building this project taught me:
- How to work with localStorage API
- DOM manipulation with vanilla JavaScript
- Event handling and delegation
- CSS Flexbox for layouts
- Making things responsive
- Clean code organization

## Future Ideas

- Add task categories/tags
- Edit existing tasks
- Set due dates
- Priority levels (high, medium, low)
- Dark mode toggle
- Maybe even sync across devices?

## Project Structure

```
todo-list/
├── index.html    # Main HTML structure
├── style.css     # All the styling
├── script.js     # JavaScript logic
└── README.md     # You're reading it!
```

## Code Highlights

### Local Storage Magic
The app automatically saves and loads your tasks:
```javascript
// Save to localStorage
function saveTasks() {
    localStorage.setItem('tasks', JSON.stringify(tasks));
}

// Load from localStorage
let tasks = JSON.parse(localStorage.getItem('tasks')) || [];
```

### Task Structure
Each task is an object with:
- `id`: Unique timestamp
- `text`: What you need to do
- `completed`: Boolean for completion status

## Try It Live

Want to see it in action? Just open `index.html` in your browser and start managing your tasks!

## Contributing

Feel free to fork this project and make it your own! If you add something cool, I'd love to see it.

## About Me

**Rahul A G**  
Computer Science Student  
Alvas Institute of Engineering and Technology, Mangalore

I'm learning web development one project at a time. This todo list was a fun way to practice JavaScript and understand how web apps actually work.

Check out my other projects on [GitHub](https://github.com/Rahulag733)!

## License

Free to use for learning purposes. Do whatever you want with it!

---

*Built with ☕ and determination to actually finish a side project*
