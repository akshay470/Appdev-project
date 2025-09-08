This project is a Tic-Tac-Toe game app built with Kotlin in Android Studio.
The app supports both offline and online multiplayer gameplay, making it simple yet powerful. 
In offline mode, two players can play on the same device. In online mode, the app uses Firebase Firestore to create or join game sessions with a unique 4-digit game ID, 
allowing real-time synchronization of moves across devices.

The app follows a clean structure with XML layouts for UI, ViewBinding for smooth interaction,
and Firebase Firestore for backend functionality. The game logic is handled in Kotlin classes (GameActivity, GameModel, GameData), 
while Firebase ensures that players’ moves are updated instantly for online matches.

This project demonstrates knowledge of mobile app development, Firebase integration, and real-time data handling. 
It is designed with a simple, user-friendly interface and can be extended with features like authentication, leaderboards, or animations in the future.
