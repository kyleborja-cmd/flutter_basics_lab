# Answers

For the `_addGlass` experiment, I moved `_glasses++` outside `setState` and tapped `+`. The displayed count stayed at `0 / 6 glasses` because Flutter did not rebuild the widget. The state value changed, but the UI did not show it until a later rebuild. I moved the increment back inside `setState`.

For the weather layout experiment, I removed `Expanded` from the Rain `StatBox`. It became narrower than the other boxes, while the remaining three expanded to use the extra width. I restored `Expanded` so all four stat boxes share the row evenly.

For the theme components activity, I added a UI Design skill chip with a brush icon. I changed the elevated button corner radius from 8 to 20, making the buttons more rounded.
