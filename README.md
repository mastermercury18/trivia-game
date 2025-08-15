# Fun Trivia Game 🎮

A SwiftUI-based trivia game for iOS with multiple game modes, difficulty levels, and score tracking.

## 🎯 Features

- **Multiple Game Modes**: Choose from different trivia categories
- **Difficulty Levels**: Adjust the challenge to your preference
- **Customizable Questions**: Select how many questions you want to answer (5-30)
- **Score Tracking**: Keep track of your high scores for each mode and difficulty
- **Animated UI**: Playful animations and transitions for an engaging experience
- **Timer**: Some modes include a time limit for added challenge
- **Lives System**: Get multiple chances to answer correctly

## 📱 Screenshots

*(You can add actual screenshots of your app here)*

## 🛠️ Technologies Used

- **SwiftUI**: For building the user interface
- **Swift**: Primary programming language
- **Xcode**: Development environment
- **Open Trivia Database API**: Source of trivia questions

## 🎨 UI Design

The app features a playful and engaging user interface with:
- Warm orange/yellow gradient backgrounds
- Rounded fonts with bold headings
- Animated elements with scaling effects
- Gradient buttons with shadows
- Consistent color scheme throughout the app
- Fun emojis to enhance the user experience

## 🧩 Game Components

### Home Screen
- Game mode selection
- Difficulty level picker
- Question count stepper
- High score display
- Start game button

### Game Screen
- Current score display
- Lives counter
- Progress indicator
- Timer (for timed modes)
- Question display
- Answer options with visual feedback
- Next question button

### Results Screen
- Final score display
- High score comparison
- Play again button
- Return to home option

## 🚀 Getting Started

### Prerequisites
- Xcode 14.0 or later
- iOS 16.0 or later
- macOS 12.0 or later (for development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/trivia-game-full.git
   ```
2. Open the project in Xcode:
   ```bash
   cd trivia-game-full
   open Trivia-Game-Full.xcodeproj
   ```
3. Build and run the project (⌘+R)

### Building
To build the project from the command line:
```bash
xcodebuild -project Trivia-Game-Full.xcodeproj -scheme Trivia-Game-Full -destination 'platform=iOS Simulator,name=iPhone 16' build
```

## 📁 Project Structure

```
Trivia-Game-Full/
├── Trivia-Game-Full/
│   ├── Assets.xcassets/
│   ├── ContentView.swift
│   ├── GameView.swift
│   ├── GameViewModel.swift
│   ├── Haptics.swift
│   ├── HomeView.swift
│   ├── Models.swift
│   ├── ResultsView.swift
│   ├── Services.swift
│   ├── TriviaGameApp.swift
│   └── data.txt
├── Trivia-Game-Full.xcodeproj/
├── Trivia-Game-FullTests/
└── Trivia-Game-FullUITests/
```

## 🧪 Testing

The project includes both unit tests and UI tests:

- **Unit Tests**: Located in `Trivia-Game-FullTests/`
- **UI Tests**: Located in `Trivia-Game-FullUITests/`

To run tests in Xcode:
1. Press `⌘+U` to run all tests
2. Or select `Product → Test` from the menu

To run tests from command line:
```bash
xcodebuild test -project Trivia-Game-Full.xcodeproj -scheme Trivia-Game-Full -destination 'platform=iOS Simulator,name=iPhone 16'
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Questions provided by [Open Trivia Database](https://opentdb.com/)
- Inspired by various trivia games and educational apps
- SwiftUI tutorials and documentation from Apple

## 📞 Contact

Your Name - [@your_twitter_handle](https://twitter.com/your_twitter_handle) - your.email@example.com

Project Link: [https://github.com/your-username/trivia-game-full](https://github.com/your-username/trivia-game-full)