# Random WordPair Generator

The Random WordPair Generator is a simple Flutter application that generates and allows users to save their favorite word pairs. It's a fun and educational app that showcases the capabilities of Flutter for mobile app development.

## Features

- Generate Random Word Pairs: The app can create random word pairs using the English Words package. These word pairs are displayed in a scrollable list.

- Save Favorites: Users can mark their favorite word pairs by tapping on them. The saved word pairs are highlighted and can be viewed later.

- View Saved WordPairs: The app provides an option to view the list of saved word pairs in a separate screen.

## Getting Started

Follow these steps to get started with the Random WordPair Generator:

1. Clone the repository or create a new Flutter project.

2. Add the necessary dependencies to your `pubspec.yaml` file:
   ```yaml
   dependencies:
     flutter:
       sdk: flutter
     english_words: ^4.0.0
   ```

3. Run `flutter pub get` to fetch and install the dependencies.

4. Replace the contents of your `main.dart` file with the provided code in the README.

5. Run your app using `flutter run` or your preferred method.

## How It Works

- The app starts with a home screen titled "WordPair Generation."

- A list of random word pairs is displayed on the home screen. These pairs are generated using the `english_words` package.

- Users can scroll through the list and tap on a word pair to mark it as a favorite. The favorite word pairs are highlighted and displayed with a red heart icon.

- To view saved word pairs, users can tap on the list icon (three lines) in the app bar. This action will navigate to a new screen titled "Saved WordPairs."

- The "Saved WordPairs" screen displays a list of the user's saved word pairs.

## Customization

You can customize the app's appearance, such as the app bar color and font size, by modifying the `_biggerFont` and `backgroundColor` variables in the code.

## Explore Flutter

The Random WordPair Generator is a great starting point for learning about Flutter. You can explore various Flutter concepts, including widgets, navigation, state management, and more.

Enjoy generating and saving your favorite word pairs with this simple yet engaging Flutter app!
