# TaskFlow - Task Management App

A beautiful, responsive task management application built with HTML, CSS, and vanilla JavaScript. TaskFlow helps you organize your tasks with a friendly dark-themed interface.

Features

Core Functionality
- Add Tasks: Create new tasks with name, due date, and priority level
- Edit Tasks: Modify existing tasks using the built-in modal editor
- Delete Tasks: Remove tasks with confirmation prompts
  -Toggle Completion: Mark tasks as complete or incomplete with one click
- Real-time Counters: Live updates of total, active, and completed task counts

 Organization Tools
- Filter Tasks: View All, Active, or Completed tasks
- Sort Options: Sort by due date, task name, or priority level
- Priority Levels: High (red), Medium (amber), and Low (blue) priority indicators
- Visual Status: Completed tasks have distinct green styling
How it looks
<img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/fedf03cb-c83a-4969-9872-30731570ee25" />
<img width="938" height="400" alt="image" src="https://github.com/user-attachments/assets/03d18141-e346-4bf0-a161-d960a69ef892" />


 How to Use it

 Getting Started
1. Open `index.html` in your web browser
2. The app loads with sample tasks to demonstrate functionality

Adding Tasks
1. Fill in the "Task Name" field
2. Select a due date using the date picker
3. Choose priority level (High, Medium, or Low)
4. Click "Add Task" button

Managing Tasks
- Complete Task: Click the green checkmark button
- Edit Task: Click the blue edit button to open the modal editor
- Delete Task: Click the red delete button (confirms before deletion)

 Filtering and Sorting
- Use the **All/Active/Completed** buttons to filter tasks
- Use the **Sort by** dropdown to organize tasks by:
  - Due Date (earliest first)
  - Task Name (alphabetical)
  - Priority (high to low)

File Structure

taskflow-app/
├── index.html          # Main application file
└── README.md          # This documentation


 Technologies Used

- HTML5: Structure and semantic markup
-  JavaScript: Interactive functionality (beginner-friendly code)
- Tailwind CSS: Utility-first CSS framework for rapid styling

 Sample Data

The app comes pre-loaded with sample tasks to demonstrate all features:
- Website redesign project (High priority)
- Team meeting preparation (Medium priority)
- Code review tasks (Low priority)
- Various completion states and due dates

Browser Compatibility

TaskFlow works in all modern browsers including:
- Chrome 
- Firefox 
- Edge 

#Local Development

No build process required! Simply:
1. Download or clone the files
2. Open `index.html` in your browser
3. Start managing your tasks

Features Breakdown

 Status Dashboard
- Total Tasks: Shows count of all tasks
- Active Tasks: Shows incomplete tasks only
- Completed Tasks: Shows finished tasks count

 Task Priority System
- High Priority: In Red color
- Medium Priority: In Amber color  
- Low Priority:In Blue color

Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Touch-friendly buttons and interactions

Contributing

This is a simple, educational project for:
- Learning JavaScript
- Understanding DOM manipulation
- Practicing responsive design
- Exploring local storage concepts

