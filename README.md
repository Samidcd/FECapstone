# FECapstone
Final Frontend course
# Task Timer App

A simple React-based task management app that allows users to add tasks, set timers for focused work, and export tasks to a calendar file.

## Features
- **Task Management**: Add, edit, and delete tasks.
- **Focus Timer**: Start, pause, and reset timers for each task.
- **Task Prioritization**: Mark tasks as high-priority.
- **Calendar Export**: Generate `.ics` files for easy calendar import.
- **Persistent Storage**: Save tasks using `localStorage`.

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **State Management**: React useState, useEffect
- **Storage**: LocalStorage
- **Optional API**: Google Calendar API (Future Feature)

## Project Timeline (5 Weeks)

### Week 1: Project Setup & Task Management
- Initialize React project and GitHub repository.
- Build `TaskList` and `TaskItem` components.

### Week 2: Task Form & Data Storage
- Develop `TaskForm` for adding/editing tasks.
- Implement `localStorage` for persistent task storage.

### Week 3: Timer Implementation
- Create `Timer` component with start/pause/reset functionality.
- Ensure timers are linked to tasks.

### Week 4: Calendar Export & UI Enhancements
- Develop `ExportButton` to generate `.ics` calendar event files.
- Improve UI with Tailwind CSS for a clean design.

### Week 5: Testing & Optional API Integration
- Perform final testing and bug fixes.
- Optionally integrate Google Calendar API for real-time sync.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task-timer-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd task-timer-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Future Improvements
- Add Pomodoro mode for work/break cycles.
- Implement cloud-based task storage with Firebase.
- Enhance UI/UX with animations and dark mode support.

## Contributions
Pull requests are welcome! Feel free to submit issues and suggestions to improve the project.

## License
MIT License
