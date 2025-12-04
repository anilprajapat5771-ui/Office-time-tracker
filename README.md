# ⏱️ Anil's Time Tracker

A sleek, professional time tracking application built with vanilla HTML, CSS, and JavaScript. Perfect for hosting on GitHub Pages.

![Time Tracker Preview](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

### Core Timer Functionality
- **Start/Pause/Resume/Stop** - Full timer control with visual feedback
- **Real-time display** - Live updating timer with millisecond precision
- **Auto-save** - Entries saved automatically when timer stops

### Project Management
- **Create projects** with custom colors and descriptions
- **Client tracking** - Associate clients with projects
- **Sub-tasks** - Break down projects into manageable sub-tasks
- **Color coding** - Visual identification across entries

### Time Entry Details
- **Task descriptions** - Detailed notes for each entry
- **Priority levels** - Low, Medium, High with visual indicators
- **Billable tracking** - Mark entries as billable/non-billable
- **Tags system** - Add multiple tags for categorization
- **Notes field** - Additional context for entries

### Analytics & Reporting
- **Today's stats** - Hours worked and tasks completed
- **Weekly overview** - Track weekly progress
- **Project time breakdown** - See time spent per project
- **Generate reports** - Export summary reports

### Data Management
- **Local storage** - All data persists in browser
- **Export to JSON** - Full data backup
- **Export to CSV** - Spreadsheet compatible format
- **Manual entries** - Add past time entries manually

### User Experience
- **Dark theme** - Easy on the eyes
- **Responsive design** - Works on desktop, tablet, and mobile
- **Keyboard shortcuts** - Quick actions without mouse
- **Toast notifications** - Feedback on actions
- **Smooth animations** - Polished interactions

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `S` | Start timer |
| `P` | Pause timer |
| `X` | Stop timer |

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch and `/ (root)` folder
4. Your tracker will be live at `https://yourusername.github.io/time-tracker/`

### Option 2: Local Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/time-tracker.git
```

2. Open `index.html` in your browser

That's it! No build process, no dependencies.

## 📁 Project Structure

```
time-tracker/
├── index.html      # Complete application (single file)
├── README.md       # Documentation
└── LICENSE         # MIT License
```

## 💾 Data Storage

All data is stored in your browser's `localStorage`:
- **Projects** - Names, colors, clients, sub-tasks
- **Time entries** - All tracked time with metadata

Data persists between sessions but is browser-specific.

## 📤 Export Formats

### JSON Export
Complete data backup including:
- All projects with settings
- All time entries with full details
- Export timestamp

### CSV Export
Spreadsheet-friendly format with columns:
- Date, Task, Project, Sub-Task
- Duration (minutes), Start/End times
- Priority, Billable status
- Tags, Notes

## 🎨 Customization

The application uses CSS variables for easy theming:

```css
:root {
    --bg-primary: #0a0a0b;
    --accent-primary: #22d3ee;
    --accent-secondary: #a855f7;
    /* ... more variables */
}
```

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 🔮 Future Enhancements

- [ ] Weekly/Monthly calendar view
- [ ] Goal setting and tracking
- [ ] Pomodoro timer mode
- [ ] Cloud sync option
- [ ] Team features
- [ ] Invoice generation

## 📄 License

MIT License - feel free to use and modify!

---

Built with ❤️ by Anil Prajapat
