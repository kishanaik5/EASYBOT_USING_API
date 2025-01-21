# EasyBot Using API

## Project Overview
**EasyBot** is an intelligent chatbot application developed using Android Studio, leveraging the power of Google's Gemini API for natural language understanding and response generation. This project showcases seamless integration of API services to deliver a robust chatbot experience.

---

## Features
1. **Natural Language Understanding**: EasyBot processes user input with advanced AI provided by Google's Gemini API.
2. **Conversational Responses**: Generates context-aware, human-like responses.
3. **User-Friendly Interface**: Designed for ease of use with an intuitive UI in Android.
4. **API Key Configuration**: Easily set up and manage the API key securely.

---

## Requirements
### Software Requirements
1. **Android Studio** (Latest version recommended).
2. **Java 8+** or **Kotlin** (Preferred language for Android development).
3. **Gradle Build Tool**.

### Dependencies
The following dependencies are used in the project:
- **Retrofit**: For making API requests.
- **Gson**: For parsing JSON responses.
- **Material Components**: For building modern, accessible UI.

---

## Installation Steps
### Step 1: Clone the Repository
1. Open your terminal and navigate to your desired project directory.
2. Clone the repository:
   ```bash
   git clone https://github.com/kishanaik5/EASYBOT_USING_API.git
   ```
3. Navigate into the project folder:
   ```bash
   cd EASYBOT_USING_API
   ```

### Step 2: Configure the API Key
1. Obtain your **Google Gemini API key** from the Google Cloud Console.
2. Paste the obtained API KEY in the constants.kt file

### Step 3: Open the Project in Android Studio
1. Open **Android Studio**.
2. Select **Open an Existing Project** and navigate to the cloned repository.
3. Let Android Studio sync the Gradle files and dependencies.

### Step 4: Build and Run the Project
1. Connect an Android device or start an emulator.
2. Click the **Run** button in Android Studio.
3. The EasyBot app will launch on your device.

---

## Usage
1. Open the EasyBot app on your Android device.
2. Enter your query in the chatbox.
3. View the chatbot's response powered by Google's Gemini API.

---

## Folder Structure
```
EASYBOT_USING_API/
├── app/                   # Main Android app folder.
│   ├── src/               # Source files.
│   │   ├── main/          # Main application files.
│   │   │   ├── java/      # Java/Kotlin files.
│   │   │   ├── res/       # Resources (layouts, strings, etc.).
│   ├── build.gradle       # App-level Gradle configuration.
├── build.gradle           # Project-level Gradle configuration.
├── settings.gradle        # Gradle settings.
├── README.md              # Project documentation.
```

---

## Security Notes
1. **API Key Management**: Ensure the `secrets.xml` file is not included in version control by adding it to `.gitignore`.
2. **Secure Communication**: Use HTTPS for all API requests.

---

## Future Improvements
1. Add support for multi-language conversations.
2. Implement offline chatbot functionality using local models.
3. Enhance UI/UX with animations and voice input.
4. Integrate push notifications for proactive bot interactions.

---

## License
This project is licensed under the MIT License.

