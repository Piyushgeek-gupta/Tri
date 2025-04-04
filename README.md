# Blind Nav - Android App with Hindi Language Support

This Android application provides assistance to blind or visually impaired users through several specialized modes:

- **Blind Mode**: For navigation assistance with object detection
- **Reading Mode**: For reading text from various sources using the camera
- **Currency Detection**: For identifying paper currency and notes

## Hindi Language Support

The app now supports both English and Hindi languages. All interfaces, voice commands, and responses from the app (including Gemini AI responses) are available in Hindi.

### Language Features

- **Toggle Language**: Users can switch between English and Hindi at any time with:

  - Voice command: Say "change language" or "भाषा बदलें"
  - Button: Tap the language toggle button in the top-left corner of the main screen

- **Localized Voice Commands**: All voice commands work in both English and Hindi:

  - Blind Mode: "blind mode"/"ब्लाइंड मोड"
  - Reading Mode: "reading mode"/"रीडिंग मोड"
  - Currency Detection: "currency detection"/"मुद्रा पहचान"

- **Localized Responses**: All app feedback and Gemini AI responses are provided in the selected language

### Natural Hindi Speech with Indian Accent

The app features enhanced Text-to-Speech for Hindi with natural-sounding Indian accent:

- **Indian Voice Selection**: Prioritizes female Hindi voices with Indian accent
- **Optimized Speech Parameters**: Adjusted rate and pitch for authentic Hindi pronunciation
- **Natural Pauses**: Strategic pauses at punctuation marks for more natural rhythm
- **SSML Enhancements**: Improved prosody and expression for Hindi speech
- **Automatic Language Installation**: Checks and installs Hindi language data if needed

For more details, see [Text-to-Speech Documentation](docs/TextToSpeech.md).

### Technical Details

- The app uses a `LanguageManager` class to manage language settings and provide localized messages
- Language settings are persisted using Android SharedPreferences
- Text-to-Speech (TTS) configuration adapts based on the selected language
- Gemini AI models are configured with language-specific system instructions to provide responses in Hindi when selected

## Using Gemini AI

The app uses two Gemini AI models:

1. **ReadModel**: For extracting and reading text from images
2. **CurrencyModel**: For identifying currency notes and their denominations

Both models are now localized to provide responses in Hindi when the app language is set to Hindi.

## Voice Commands

Voice commands are available throughout the app in both English and Hindi. Here are some examples:

### English Commands

- "open blind mode"
- "reading mode"
- "currency detection"
- "change language"

### Hindi Commands

- "ब्लाइंड मोड खोलें"
- "रीडिंग मोड"
- "मुद्रा पहचान"
- "भाषा बदलें"

## Accessibility Features

- Large buttons and simple interface
- Voice feedback for all actions
- Voice commands for hands-free operation
- High contrast visual elements
- Language toggle for language preference
- Vibration feedback for button presses
- Natural-sounding speech with appropriate pauses

## Technical Requirements

- Android 8.0 (API level 26) or higher
- Camera and microphone permissions
- Internet connection for AI-based features
- Google Text-to-Speech engine with Hindi language pack installed

# Blind-Nav---Android-App-for-Blind-persons

![Asset 3](https://github.com/user-attachments/assets/d49f6059-cffb-4cef-93cb-886c1484e657)

### ⭕ Blind Nav is an Android Application which helps the Blind people to navigate their surroundings and Environment just with the help of their Mobile Phones Camera and the Internet.

# Youtube Demo Video: https://www.youtube.com/watch?v=GD4iuPCIXTc&t=116s

#### LETS START

![1](https://github.com/user-attachments/assets/b55143ac-98ff-4c34-a27c-3f409998e59f)

# Features:

This app has the 3 main features.

1️⃣ **Navigation Mode**: when the app is opened and the new session has been created then first Navigation Mode will be opened which will help the users in Navigation.

![WhatsApp Image 2024-08-10 at 12 17 19 AM (2)](https://github.com/user-attachments/assets/42866c75-480b-4761-92a6-3cf0159a7bab)

2️⃣ **Assistant Mode**: By double tap in the Navigation Mode then the Assistant Mode will be activated and the purpose of the Assistant Mode is that user can ask any question about its
environment is like, what is the color of the car, Color of the bottle, how is the weather and any specific thing. users can also ask about anyother things like who is Elon Musk.

![3](https://github.com/user-attachments/assets/150214b9-3d79-43d6-9107-b308434cd91e)

3️⃣ **Reading Mode** : Reading mode is a mode which will help the user in reading sign-boards or books etc. It's basic feature is to read the text on anything.

![4](https://github.com/user-attachments/assets/2037617e-d0c2-497a-a0ad-41472889a0e4)

# Setup:

⭕ for the setup of this app we just need 1️⃣ third part Dependency which is Gemini AI API key which is doing all our main work so this is mandatory.

🔎 you just have to clone the repository from the github and then just open the Android Studio and in the following files (GeminiAI.kt, GeminiAI 1.kt, GeminiAI 2.kt) just add your API Key.

👉To get the Gemini API key just go to the following(https://ai.google.dev/) link and just get your API key you do not have to make an new model as I already did you just need your API key.

![23](https://github.com/user-attachments/assets/f4e5aebc-37e2-417e-a381-16d6ca432032)

✔(by-the-way for eaesiness I have maked an video which is uploaded to the youtube so kindly refer to that video by pressing on the link.)

🛑ok kindly do your collaborations and also let me know that how good app is and are the improvements that are needed

# LICENSE

MIT License

Copyright (c) 2024 Muhammad Ahad Naseer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE
#   T r i  
 #   t r i n e t r a  
 #   t r i n e t r a  
 