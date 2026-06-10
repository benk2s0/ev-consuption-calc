# ⚡ EV Range Simulator (EV Calc)

A sleek, mobile-first, and highly interactive Web Application designed to calculate and estimate the real-world range of Electric Vehicles (EVs). Built with pure HTML, CSS, and JavaScript, it requires no installation or build steps.

## ✨ Features

* 📱 **Mobile-First & PWA Ready:** Beautiful, app-like interface that can be installed directly to your iOS or Android home screen (includes `manifest.json` and Apple Touch Icons).
* 🔋 **Battery Health (SoH) Integration:** Accurately calculates usable battery capacity based on the battery's current State of Health.
* 🔌 **Daily Usage Window:** Set your minimum and maximum charging limits (e.g., 20% to 80%) to see your practical daily range without degrading the battery. Includes safety logic to prevent invalid ranges.
* ⚙️ **Dual Consumption Sync:** Instantly converts and syncs consumption metrics between **Electrical (kWh/100km)** and **Mechanical (HPh/100km)** in real-time.
* 📊 **Granular Insights:** Displays Total Range, Window Range, and a quick **km per 1% charge** metric for easy mental math while driving.
* 💾 **Persistent Memory:** Uses browser `localStorage` to automatically save your last inputted values and preferences.
* 🌍 **Internationalization (i18n):** Bilingual support (English and Portuguese). Auto-detects the user's browser language on the first visit and allows manual toggling.

## 🚀 How to Use

Since this project is built with vanilla web technologies, there are no dependencies or complex setups required.

1. Access https://ev-autonomy-calc.netlify.app/
3. Adjust the sliders or input numbers directly to see real-time estimations!

### Running as a Web App (PWA)
* **iOS (Safari):** Tap the "Share" icon at the bottom and select "Add to Home Screen".
* **Android (Chrome):** Tap the three dots menu at the top right and select "Add to Home screen".

## 🛠️ Built With

* **HTML5** (Semantic structure)
* **CSS3** (Custom variables, Flexbox, responsive design, modern UI/UX)
* **Vanilla JavaScript** (DOM manipulation, Event Listeners, Local Storage, i18n logic)

## 📁 Project Structure

\`\`\`text
├── index.html       # Main application file (UI + Logic + Styles)
├── manifest.json    # PWA configuration for Android
├── icone.png        # 512x512 App Icon for iOS/Android home screens
└── README.md        # Project documentation
\`\`\`

## 👨‍💻 Author

Developed with ⚡ by **[Fernando Garcez]** *Feel free to reach out via [Email](mailto:fernandogarcez@gmail.com) for feedback or suggestions!*