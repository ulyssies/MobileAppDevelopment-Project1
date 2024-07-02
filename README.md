# monexp

## Features

- **Home Screen**:
  - Displays a list of categories.
  - Shows a chart for visualizing expenses.
  - Displays the total balance.
  - Shows the percentage of expenses in each category.
- **Add Expense**: Floating action button to add new expenses.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) should be installed on your machine.
- A suitable IDE like [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/).

### Installation

1. **Clone the repository**

   git clone https://github.com/your-username/monexp.git
   cd monexp

2. ***Install dependencies**

    flutter pub get

3. ***Run the app**

flutter run

Project Structure
css
Copy code
lib/
  main.dart
  screens/
    all_expensees.dart
    category_screen.dart
    budget_screen.dart
  widgets/
    all_expenses_screen/
      all_expenses_fetch.dart
      all_expenses_list.dart
      expense_search.dart
    category_screen/
      category_fetcher.dart
      category_chart.dart
      category_balance.dart
      category_percentage.dart
    expense_screen/ 
      confirm_box.dart
      expense_card.dart
      expense_fetcher.dart
      expense_list.dart
      expense_form.dart
main.dart

This is the entry point of the application. It sets up the routes and initializes the app.

screens/category_screen.dart
This screen displays the categories, a chart for visualizing expenses, the total balance, and the percentage of expenses in each category. It includes a bottom navigation bar for navigating between the home and budget screens and a floating action button for adding expenses.

widgets/category_screen/category_fetcher.dart
A widget that fetches and displays categories.

widgets/category_screen/category_chart.dart
A widget that displays a chart for visualizing expenses.

widgets/category_screen/category_balance.dart
A widget that displays the total balance.

widgets/category_screen/category_percentage.dart
A widget that displays the percentage of expenses in each category.

widgets/expense_form.dart
A widget that displays a form for adding new expenses.

Usage
Home Screen:
View your categories.
Visualize expenses with charts.
Check your total balance.
See the percentage of expenses in each category.
Add Expense: Click the floating action button to add a new expense.
Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/fooBar).
Commit your changes (git commit -am 'Add some fooBar').
Push to the branch (git push origin feature/fooBar).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Flutter - The framework used
Android Studio - Recommended IDE
Visual Studio Code - Another great IDE


This `README.md` file now includes a detailed description of the features available on the home screen, including categories, charts, balance, and percentage in each category.
# MobileAppDevelopment-Project1
