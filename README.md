# my-first-project
# PomodoroTodo

A beautiful productivity web application that seamlessly combines task management with the Pomodoro technique. Built with React, TypeScript, and Tailwind CSS.

## Features

### 🍅 Pomodoro Timer
- Realistic tomato-shaped timer with smooth animations
- Customizable work/break durations
- Automatic break cycles with long break support
- Visual and audio notifications
- Elegant progress tracking

### ✅ Task Management
- Create, edit, and delete tasks
- Mark tasks as complete with smooth animations
- Track Pomodoros completed per task
- Clean, intuitive interface

### 📊 Progress Dashboard
- Daily statistics and completion tracking
- Visual progress bars and charts
- Focus time tracking
- Task completion rates

### ⚙️ Customization
- Multiple color themes (Tomato Red, Mint Green, Midnight Blue)
- Adjustable timer durations
- Auto-start preferences
- Sound and notification settings

### ⌨️ Keyboard Shortcuts
- `Space` - Start/pause timer
- `S` - Open settings
- `Ctrl+A` - Add new task
- Full keyboard navigation support

### 🎨 Beautiful Design
- Modern, clean interface with soft shadows and rounded corners
- Responsive design for mobile and desktop
- Smooth transitions and micro-interactions
- Accessibility-focused with proper contrast ratios

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd pomodoro-todo
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
src/
├── components/          # React components
│   ├── Dashboard/       # Progress tracking and statistics
│   ├── Header/          # App header with navigation
│   ├── Layout/          # Main app layout
│   ├── PomodoroTimer/   # Timer components and tomato interface
│   ├── Settings/        # Settings modal and preferences
│   └── TodoList/        # Task management components
├── context/             # React Context providers
├── hooks/               # Custom React hooks
├── types/               # TypeScript type definitions
├── utils/               # Utility functions
└── styles/              # Global styles
```

## Technology Stack

- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **State Management**: React Context API
- **Persistence**: localStorage
- **Accessibility**: Full ARIA support and keyboard navigation

## Features in Detail

### Pomodoro Timer
The timer features a realistic tomato design with:
- Circular progress indicator
- Embossed 3D effects with highlights and shadows
- Smooth animations and transitions
- Theme-based color variations
- Break mode with coffee cup styling

### Task Management
- Add tasks with intuitive form interface
- Edit tasks inline with keyboard shortcuts
- Delete tasks with confirmation
- Visual feedback for completed tasks
- Pomodoro count tracking per task

### Settings & Customization
- Work duration (1-60 minutes)
- Break duration (1-30 minutes)
- Long break duration and intervals
- Auto-start preferences
- Theme selection
- Audio and notification toggles

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Touch-friendly interactions
- Optimized for tablets and desktops

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by the Pomodoro Technique® by Francesco Cirillo
- Design inspiration from modern productivity apps
- Icons provided by Lucide React
