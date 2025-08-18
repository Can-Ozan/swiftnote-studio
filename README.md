📝 SwiftNote Studio
A modern and dynamic note-taking web application. Categorize, tag, search, and organize your notes with ease.
✨ Features
 * 🎨 Modern Design: Glass morphism effects and smooth animations
 * 📁 Category System: Organize your notes into categories
 * 🏷️ Tagging System: Add tags to your notes
 * 🔍 Powerful Search: Search by title, content, and tags
 * ⭐ Favorites: Mark important notes as favorites
 * 💾 Auto-Save: Your data is saved securely
 * 📱 Responsive Design: Works perfectly on all devices
 * ⚡ Fast Performance: Instant search and smooth transitions
🛠️ Technologies
Frontend
 * React 18 - Modern UI framework
 * TypeScript - Type-safe development
 * Tailwind CSS - Utility-first CSS framework
 * Zustand - State management
 * Lucide Icons - Beautiful icon set
 * date-fns - Date formatting
 * Vite - Fast build tool
Backend & Database
 * Supabase - Backend as a Service
 * PostgreSQL - Robust database
 * Real-time subscriptions - Live updates
🖼️ Project Screenshots
Homepage Interface
🚀 Setup
Requirements
 * Node.js 18+
 * npm or yarn
Steps
 * Clone the repository
<!-- end list -->
git clone https://github.com/Can-Ozan/swiftnote-studio.git
cd swiftnote-studio

 * Install dependencies
<!-- end list -->
npm install
# or
yarn install

 * Start the development server
<!-- end list -->
npm run dev
# or
yarn dev

 * Open in your browser
<!-- end list -->
http://localhost:8080

📖 Usage
Creating a Note
 * Click the "New Note" button
 * Add a title and content
 * Select a category
 * Add tags (optional)
 * Click the "Save" button
Editing a Note
 * Click on the note you want to edit
 * Click the "Edit" button
 * Make your changes
 * Save with "Save"
Search and Filter
 * Search bar: Quickly search through your notes
 * Categories: Filter by categories from the sidebar on the left
 * Favorites: View your favorite notes
Keyboard Shortcuts
 * Ctrl + Enter: Save note
 * Esc: Cancel editing
🏗️ Project Structure
src/
├── components/          # React components
│   ├── ui/             # Shadcn/ui components
│   ├── Header.tsx      # Top header and search
│   ├── Sidebar.tsx     # Category navigation
│   ├── NoteList.tsx    # Note list
│   └── NoteEditor.tsx  # Note editor
├── store/              # Zustand store
│   └── noteStore.ts    # Note state management
├── types/              # TypeScript type definitions
│   └── note.ts         # Note types
├── pages/              # Page components
│   └── Index.tsx       # Homepage
└── lib/                # Helper functions
    └── utils.ts        # Utility functions

🎨 Design System
Colors
 * Primary: Deep Purple (#7c3aed)
 * Accent: Cyan Blue (#06b6d4)
 * Background: Dark theme with gradients
 * Glass Effects: Modern look with backdrop blur
Animations
 * Fade In: On page load
 * Slide Up: For list items
 * Scale In: For modals and popups
 * Hover Effects: For interactive elements
🔧 Development
Available Scripts
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint

# Type check
npm run type-check

Code Style
 * ESLint for code quality control
 * Prettier for code formatting
 * TypeScript for type safety
🤝 Contributing
 * Fork the repository
 * Create your feature branch (git checkout -b feature/amazing-feature)
 * Commit your changes (git commit -m 'Add amazing feature')
 * Push to your branch (git push origin feature/amazing-feature)
 * Open a Pull Request
📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
📞 Contact
 * Email: yusufcanozan9@gmail.com
 * GitHub: https://github.com/Can-Ozan/swiftnote-studio.git
Manage your notes in a modern and efficient way with SwiftNote Studio! ✨
