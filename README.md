TASK MANAGER - README

OVERVIEW
A simple task management web application that helps users organize their tasks efficiently. 
The application features a clean sidebar navigation, task filtering options, and a responsive design.

FEATURES
- Sidebar Navigation: Easy access to different task views
- Task Filtering: Filter tasks by status, priority, and time period
- Task Management: View task details with edit/delete options
- User Profile: Access profile settings and logout
- Notifications: Visual notification indicator
- Responsive Design: Works on different screen sizes

FILE STRUCTURE
index.html        - Main HTML file with page structure
styles.css        - Custom CSS styles for the application
README.txt        - This file

DEPENDENCIES
- Tailwind CSS (via CDN) - Utility-first CSS framework
- Font Awesome (via CDN) - Icon library

HOW TO USE

NAVIGATION
- All Tasks: View all tasks regardless of status
- Pending: View tasks that are not yet completed
- Completed: View completed tasks
- Today: View tasks due today
- This Week: View tasks due within the current week
- High Priority: View high priority tasks

TASK CARDS
Each task card displays:
- Task title
- Due date
- Action buttons (Edit and Delete)

SETUP INSTRUCTIONS
1. Open the index.html file in your web browser
2. No additional setup required - all dependencies are loaded via CDN

CUSTOMIZATION
Colors can be modified by changing the CSS variables in the :root section of styles.css:
- --primary-color: Main accent color
- --secondary-color: Task border color
- --danger-color: Delete/red elements
- --success-color: Success/green elements

FUTURE IMPROVEMENTS
- Add task creation form
- Implement task editing functionality
- Add due date filtering
- Implement task categories
- Add user authentication
- Add local storage persistence
- Implement drag-and-drop task reordering

COPYRIGHT
This is a frontend-only implementation. For a complete solution, backend functionality would need to be added.
