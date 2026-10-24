https://github.com/kyleborja-cmd/flutter_basics_lab.git
Actvity 2 - The program tracks daily water intake with a goal of 6 glasses. The (+) button adds a glass, the (−) button removes one, and Reset returns the count to zero. The progress bar updates automatically, and a success message appears when the goal is reached.
Observations 2,3 and 5 - I observed that Code File 2 uses setState() to update the water tracker, Code File 3 uses layout widgets to display weather information, and Code File 5 uses a switch to change between light and dark themes.
//Review questions
Answers:
1. A StatelessWidget does not change its own state, like ProfileCard in Activity 1. A StatefulWidget can update its state, like WaterTrackerPage in Activity 2.
2.The StatefulWidget creates the widget, while its State class stores changeable data and updates the UI.
3. The displayed count did not update immediately because Flutter was not notified to rebuild the screen.
4. It is called when the widget is first displayed and when Flutter rebuilds it after state changes.
5. In a Row, the main axis is horizontal and the cross axis is vertical. In a Column, the main axis is vertical and the cross axis is horizontal.
6. The StatBox widgets may take their natural width and overflow the available space. Expanded makes them share the available width equally.
7. It displays menu items in a grid and efficiently builds items as needed, unlike a Column that arranges children vertically.
8. Stack layers widgets on top of each other, while Positioned places the Best seller badge at the top-left corner of the menu card.
9. ThemeData customizes the appearance of multiple widgets across the app, such as the theme in Activity 5. A widget style customizes one widget, such as the rounded corners of an ElevatedButton.
10. ThemeDemoAppState holds the _isDark state. The switch calls onDarkChanged, which updates the state using setState(), and MaterialApp receives the updated value through themeMode.