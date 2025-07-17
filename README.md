# 💪 Flutter BMI Calculator App

A beautifully styled, fully offline **BMI Calculator** app built with Flutter.  
This app allows users to enter their **name**, **height**, and **weight**, and get personalized BMI results along with **category-based advice**, **emojis**, and a clean animated UI.

---

## ✨ Features

- 🔠 User enters their **name** for a personalized experience.
- 📏 Takes input for **height (in meters)** and **weight (in kg)**.
- 🧮 Calculates **BMI** and displays a result like:  
  `Alex, your BMI is 28.7. You’re overweight 😐 — time to workout! 🏋️`
- 🎨 **Color-coded results** based on BMI category.
- ❤️ Smooth **icon animation** on result display.
- 🔄 Includes **Reset** button to clear fields.
- 📱 Fully **offline**, **lightweight**, and **mobile responsive**.

---

## 🧠 BMI Categories Used

| BMI Range      | Category     | Message                           |
|----------------|--------------|-----------------------------------|
| < 18.5         | Underweight  | Eat well and stay healthy 🥲       |
| 18.5 – 24.9    | Normal       | You’re fit and healthy 😊         |
| 25 – 29.9      | Overweight   | Time to workout! 🏋️               |
| ≥ 30           | Obese        | Prioritize your health 😶         |

---

## 🛠 Tech Stack

- **Flutter** 3.x
- **Dart**
- No external packages (optional: `flutter_native_splash` if splash screen is added)

---

## 📷 Screenshots

| Input Form | BMI Result |
|------------|------------|
| ![input](assets/screens/input.png) | ![result](assets/screens/result.png) |

*(Add screenshots of your UI in `assets/screens/` and update links above)*

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/bmi-calculator-app.git
   cd bmi-calculator-app

   flutter pub get
   flutter run
   flutter build apk --release

  
📄 License
This project is open source and available under the MIT License.


