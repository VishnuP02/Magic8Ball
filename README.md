# Magic8Ball
### Overview
The Magic 8-Ball App is an interactive Android application that simulates a classic fortune-telling toy. Users can ask a question either by speaking into their device or typing it, then "shake" the 8-Ball to receive a randomly generated answer. The app utilizes voice recognition for a hands-free experience, allowing users to speak their questions out loud.

### Features
Voice Recognition: Users can ask questions using voice input, thanks to integrated speech recognition.
Interactive Response: Shake the app's button to generate a randomized answer, just like the original Magic 8-Ball toy.
Dynamic UI: A user-friendly interface built using Jetpack Compose for a modern and responsive design.
Sound Effects: Optional sound effects to enhance the user experience.
### Tech Stack
 - Language: Kotlin
 - Framework: Jetpack Compose
 - Libraries/Tools:
   SpeechRecognizer for voice input handling;
   MediaPlayer for sound effects;
   Material3 for UI components
### Installation
Clone this repository:
- git clone https://github.com/yourusername/magic8ball.git
- Open the project in Android Studio.
- Build and run the project on an emulator or a physical device with Android 7.0 (API 24) or higher.
### Usage
- Launch the app.
- Press the "Shake the 8-Ball" button to activate voice recognition.
- Ask a question and wait for the app to recognize your voice.
- View the response generated by the Magic 8-Ball.
### Permissions
The app requires the following permissions:
- Microphone: For capturing voice input. Ensure that these permissions are granted when prompted during app installation or by manually enabling them in the device settings.
### Code Structure
- MainActivity.kt: Handles voice recognition logic, UI initialization, and lifecycle management.
- Magic8BallScreen.kt: Contains the main composable function for the app's user interface.
- Theme.kt: Defines the app's theme and UI styling.
### Contributing
Feel free to submit issues, fork the repository, and make pull requests. Contributions are always welcome!
### Acknowledgements
Inspired by the classic Magic 8-Ball toy.
