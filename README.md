# Digital Clock App ⏰

A beautiful and interactive digital clock application built with React and Vite, featuring real-time updates and an elegant design.

## ✨ Features

- **Real-time Clock**: Displays current time with seconds, updating every second
- **12-hour Format**: Shows time in AM/PM format with proper formatting
- **Beautiful UI**: Elegant design with background image and modern styling
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Zero-padded Time**: Consistent time formatting with leading zeros

## 🚀 Getting Started

1. **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd clock-app
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Run the development server:**
    ```bash
    npm run dev
    ```

4. Open [http://localhost:5173](http://localhost:5173) to view the app in your browser.

## 📁 Project Structure

```
clock-app/
├── public/
│   └── vite.svg                 # Favicon
├── src/
│   ├── assets/
│   │   ├── background_clock.jpg # Background image
│   │   └── react.svg           # React logo
│   ├── App.jsx                 # Main App component
│   ├── App.css                 # App styles
│   ├── DigitalClock.jsx        # Digital clock component
│   ├── index.css               # Global styles
│   └── main.jsx                # React entry point
├── index.html                  # HTML template
├── package.json                # Dependencies and scripts
└── README.md                   # Project documentation
```

## 🛠️ Technologies Used

- **[React](https://react.dev/)** - Frontend library with hooks (useState, useEffect)
- **[Vite](https://vitejs.dev/)** - Fast build tool and dev server
- **[ESLint](https://eslint.org/)** - Code linting and formatting
- **CSS3** - Modern styling with gradients and animations

## ⚙️ Key Components

### DigitalClock Component
- **State Management**: Uses `useState` to track current time
- **Real-time Updates**: `useEffect` with `setInterval` for live time updates
- **Time Formatting**: Custom functions for 12-hour format and zero-padding
- **Cleanup**: Proper interval cleanup to prevent memory leaks

### Features Implemented
- Live time display (HH:MM:SS AM/PM)
- Automatic updates every second
- Clean component architecture
- Memory-efficient with proper cleanup

## 🎨 Customization Ideas

- **Themes**: Add dark/light mode toggle
- **Time Zones**: Support for multiple time zones
- **Alarms**: Add alarm and timer functionality
- **Analog Clock**: Create an analog clock option
- **Animations**: Add smooth transitions and effects
- **Date Display**: Show current date alongside time

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ using React and Vite
