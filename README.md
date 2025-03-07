# **🍽️ Meals Recipe App**

The **Meals Recipe App** is a simple and easy-to-use Flutter application that helps users explore different meal options, view detailed recipes, and save their favorite meals. It comes with dietary filters, allowing users to personalize their experience based on their food preferences.

---

## **✨ What You Can Do**

- **Browse Meal Categories:** Discover meals organized into different categories.
- **View Recipe Details:** Check out ingredients, step-by-step instructions, and meal complexity.
- **Save Favorites:** Keep track of meals you love by adding them to your favorites list.
- **Apply Dietary Filters:** Choose from gluten-free, vegetarian, vegan, and lactose-free options to find meals that match your preferences.

---

## **📁 How the App is Structured**

- **[main.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/main.dart)** - Sets up the app, including theming and navigation.
- **[categories.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/screens/categories.dart)** - Displays a list of meal categories.
- **[category.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/models/category.dart)** - Defines how meal categories are structured.
- **[meals.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/screens/meals.dart)** - Shows meals based on the selected category.
- **[meal.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/models/meal.dart)** - Defines meal details, including ingredients and preparation steps.
- **[meal_details.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/screens/meal_details.dart)** - Provides an in-depth look at a selected meal.
- **[filters.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/screens/filters.dart)** - Lets users customize their meal preferences.
- **[tabs.dart](https://github.com/Yashwant1105/meals-app/blob/main/lib/screens/tabs.dart)** - Handles bottom navigation between categories and favorite meals.

---

## **🔹 Flutter Features Used**

- **State Management:** Uses `StatefulWidget` and `flutter_riverpod` for handling app state.
- **Navigation & Routing:** Implements smooth screen transitions with `Navigator.push()`.
- **Favorites Handling:** Manages favorite meals using `Riverpod` state management.
- **Async Programming:** Uses `async/await` to ensure smooth app performance.

---

## **🚀 Getting Started**

### **What You Need**

Make sure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/)

### **How to Run the App**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Yashwant1105/meals-app.git
   cd meals-app
   ```

2. **Install Dependencies**:
   ```bash
   flutter pub get
   ```

3. **Launch the App**:
   ```bash
   flutter run
   ```



