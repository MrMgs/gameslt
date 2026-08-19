\# 🧪 Quantum Ooze



!\[Quantum Ooze](preview.png)



\*\*Quantum Ooze\*\* is an animated HTML5 slot game with a sci-fi laboratory theme, responsive UI, interactive reel mechanics, bonus features, sound effects, and Android support.



The project is built with \*\*HTML, CSS, and vanilla JavaScript\*\*, with no frontend framework required.



> 🎮 This project is intended as a game/demo project using simulated credits. It does not include real-money gambling, deposits, or cash withdrawals.



\---



\## 🎮 Features



\* 🎰 5-reel animated slot machine

\* 🧪 Sci-fi / experimental laboratory theme

\* 💰 Virtual balance and betting system

\* 🎯 19 paylines

\* 🧬 Wild symbols

\* 🌀 Scatter symbols

\* 🎁 Free Spins

\* ⚡ Turbo Spin mode

\* 🔄 Auto Spin

\* 🔊 Sound effects

\* 💥 Win animations and particle effects

\* 📈 Portal Instability multiplier system

\* ✨ Wild Reel multipliers

\* 📱 Responsive mobile layout

\* 🤖 Android WebView version

\* 📦 Ready-to-install debug APK



\---



\## 🕹️ Gameplay



The goal is to match \*\*3 or more identical symbols\*\* across an active payline.



The game includes several symbols such as:



\* 🧬 \*\*WILD\*\*

\* 🌀 \*\*SCATTER\*\*

\* 🧠 \*\*BRAIN\*\*

\* 👾 \*\*ALIEN\*\*

\* ⚗️ \*\*SERUM\*\*

\* 🛸 \*\*UFO\*\*

\* 🦠 \*\*OOZE\*\*

\* 💎 \*\*CORE\*\*



\### Wild



Wild symbols can substitute for regular symbols and can activate special \*\*Wild Reel multipliers\*\*.



Possible multipliers include:



```text

×2

×3

×5

×10

```



\### Scatter \& Free Spins



Landing enough Scatter symbols activates the bonus feature.



```text

3 Scatters → 8 Free Spins

4+ Scatters → 12 Free Spins

```



\### Portal Instability



Every spin increases the \*\*Portal Instability Meter\*\*.



As instability increases, the global multiplier can progress through:



```text

×1 → ×2 → ×3 → ×5 → ×10 → ×25

```



\---



\## 🎛️ Controls



| Control   | Action                         |

| --------- | ------------------------------ |

| 🎰 Spin   | Spin the reels                 |

| `+` / `-` | Increase or decrease bet       |

| MAX BET   | Set maximum bet                |

| AUTO      | Enable automatic spins         |

| TURBO     | Increase spin speed            |

| ♪         | Toggle sound                   |

| ☰         | Open game information/paytable |

| Spacebar  | Spin using the keyboard        |



\---



\## 📱 Responsive Design



Quantum Ooze is designed to adapt to desktop and mobile screens.



\### Mobile Preview



!\[Mobile Preview](phone-390x844.png)



The repository also contains additional previews for different resolutions.



\---



\## 🛠️ Technologies



The project uses:



```text

HTML5

CSS3

JavaScript

Canvas API

Web Audio API

Android WebView

Gradle

```



No React, Vue, Angular, or other frontend framework is required.



\---



\## 📂 Project Structure



```text

gameslt/

│

├── index.html

├── style.css

├── game.js

│

├── assets/

│   └── game images and graphical assets

│

├── android-app/

│   ├── app/

│   ├── build.gradle

│   ├── settings.gradle

│   └── README.md

│

├── Quantum-Ooze-debug.apk

│

├── preview.png

├── phone-390x844.png

├── phone-412x915.png

├── phone-844x390.png

│

└── .gitignore

```



\---



\## 🚀 Running the Web Game



Clone the repository:



```bash

git clone https://github.com/MrMgs/gameslt.git

```



Enter the project:



```bash

cd gameslt

```



You can then open:



```text

index.html

```



directly in your browser.



For development, you can also start a simple local HTTP server.



Using Python:



```bash

python -m http.server 8000

```



Then open:



```text

http://localhost:8000

```



\---



\## 📱 Android Version



An Android version of Quantum Ooze is included in:



```text

android-app/

```



The Android application packages the HTML5 game inside a native \*\*Android WebView\*\*.



\### Using Android Studio



Open:



```text

android-app/

```



as an Android Studio project and build/run the application.



\### Build from Command Line



From the Android project directory:



```bash

cd android-app

```



Then:



```bash

gradlew.bat assembleDebug

```



The generated APK will normally be located at:



```text

app/build/outputs/apk/debug/app-debug.apk

```



\---



\## 📦 APK



A compiled debug APK is already included in the repository:



```text

Quantum-Ooze-debug.apk

```



It can be used to test the game directly on an Android device.



> Android may require permission to install applications from unknown sources when installing a debug APK manually.



\---



\## 🎨 Game Design



Quantum Ooze uses a stylized sci-fi casino interface inspired by futuristic laboratory experiments.



The interface includes:



\* Animated reels

\* Glowing controls

\* Laboratory environment

\* Portal effects

\* Particle animations

\* Responsive mobile controls

\* Animated win feedback

\* Dynamic multipliers

\* Bonus events



\---



\## 🧠 Core Game Logic



The main gameplay logic is located in:



```text

game.js

```



It handles:



\* Symbol generation

\* Reel animation

\* Payline evaluation

\* Wild behavior

\* Scatter detection

\* Free Spins

\* Multipliers

\* Balance calculation

\* Betting

\* Auto Spin

\* Turbo mode

\* Audio

\* Particle effects

\* Win animations



\---



\## 🔮 Future Improvements



Potential additions include:



\* \[ ] More bonus games

\* \[ ] Additional slot themes

\* \[ ] Improved sound design

\* \[ ] More reel animations

\* \[ ] Persistent player settings

\* \[ ] Better mobile optimization

\* \[ ] Progressive jackpot animation

\* \[ ] Achievement system

\* \[ ] Statistics screen

\* \[ ] Production Android release build



\---



\## 👨‍💻 Author



Developed by \*\*MrMgs\*\*



GitHub: \*\*@MrMgs\*\*



\---



\## ⚠️ Disclaimer



Quantum Ooze is a software/game development project intended for entertainment, demonstration, and portfolio purposes.



The credits displayed in the game are virtual and have no monetary value.



\---



⭐ If you like the project, consider giving the repository a star!



