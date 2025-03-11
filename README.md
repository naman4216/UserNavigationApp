# User Profile Viewer

## Overview
This is a React Native application that fetches and displays random user profiles from an API. Users can view profile details, including an avatar, name, email, and other relevant information. Navigation buttons allow users to browse through multiple profiles.

## Features
- Fetches user profiles from an external API.
- Displays user information in a beautifully styled UI.
- Allows users to navigate between profiles using "Previous" and "Next" buttons.
- Provides a loading indicator while fetching data.

## Installation and Running the Application
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)
- [Android Studio](https://developer.android.com/studio) (For Android emulation) or Xcode (For iOS development)

### Steps to Run Locally
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Run the application:**
   - For Android:
     ```sh
     npx react-native run-android
     ```
   - For iOS (MacOS only):
     ```sh
     npx react-native run-ios
     ```

## Additional Notes
- Ensure that your emulator or physical device is connected before running the app.
- If you encounter any issues, try cleaning the build cache:
  ```sh
  cd android && ./gradlew clean && cd ..
  ```
- The API used in this project is `https://random-data-api.com/api/users/random_user?size=1`.
- The UI follows a simple and clean card-based layout.

## License
This project is licensed under the MIT License.

## Contact
For any issues or contributions, feel free to open an issue or create a pull request on the GitHub repository.

