# 🗣️ SpeakSync

A simple, client-side web application that converts typed text into synthesized speech using the browser's native **Web Speech Synthesis API**.

This project is hosted entirely on **GitHub Pages**, demonstrating the power of modern browser APIs without requiring any backend services.

## 🚀 Live Demo

**[CLICK HERE TO VISIT THE LIVE PAGE](https://faiz1310.github.io/Texpify/)**



## ✨ Features

* **Instant Conversion:** Converts text to speech immediately upon clicking the "Listen" button.
* **Voice Selection:** Automatically loads and allows selection from all available voices installed on the user's operating system (e.g., standard English, regional accents, etc.).
* **Customization:** Control the **speed (rate)** and **pitch** of the synthesized voice using easy-to-use sliders.
* **Client-Side Only:** No server processing, ensuring fast, private, and free operation.

## ⚙️ Technology Used

This project is a prime example of a **static web application** built with standard web technologies:

* **HTML5:** Provides the structure of the application.
* **CSS3:** Styles the application for a clean, user-friendly interface.
* **JavaScript:** Implements the core functionality using the **Web Speech Synthesis API**.

## 💻 How to Use

1.  **Enter Text:** Type or paste the text you want to hear into the main text area.
2.  **Select Voice:** Choose your preferred voice and language from the dropdown menu (voices vary by browser and operating system).
3.  **Adjust Controls:** Fine-tune the **Speed** and **Pitch** sliders to change the tone and cadence.
4.  **Listen:** Click the **"🔊 Listen"** button to start the audio playback.

## 🌐 Hosting and Deployment

This application is built for easy deployment via **GitHub Pages**.

### Steps to Host:

1.  **Repository Setup:** Create a new GitHub repository and upload the `index.html` file to the root directory.
2.  **Enable Pages:** Go to **Settings** -> **Pages** and set the source to deploy from the `main` branch.
3.  **Access:** GitHub will provide a public URL (e.g., `https://username.github.io/repo-name/`) where your application is live.

## ⚠️ Browser Compatibility

The core functionality relies on the **Web Speech Synthesis API**. While widely supported, behavior and available voices may differ between browsers (Chrome, Edge, Firefox, Safari).

* **iOS/Safari:** Sometimes requires a user gesture (a button click) to initialize voices.
* **General:** Voices are sourced from the operating system, meaning voice quality and selection are dependent on the user's device.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests! Ideas for improvements include:

* Adding a progress bar for speech playback.
* Implementing a volume control slider.
* Improving CSS responsiveness for mobile devices.
