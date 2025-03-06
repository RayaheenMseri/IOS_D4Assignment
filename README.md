# SwiftUI User Profile UI

## Overview

This SwiftUI app displays a simple user profile UI with three elements:
- A Text label displaying the user's name
- An Image representing the user's profile picture
- A Button that triggers an action when pressed (in this case, changes the text color)

The app is built using a `ZStack` for the background, `VStack` for vertical layout, and basic SwiftUI elements like `Text`, `Image`, and `Button`.

## Code Structure

- **ContentView.swift**: Contains the main view that structures the UI using SwiftUI's layout system (`VStack`, `ZStack`,`HStack` ).
  - **ZStack** is used to place the background color.
  - **VStack** arranges the image, text, and button vertically.
  - **HStack** arranges the image, text, and button horizontally
  - **Image** represents the profile picture.
  - **Text** displays the user's name.
  - **Button** allows interaction, changing the displayed name when pressed.

## Customization

- **Profile Image**: Currently using a system image (`person.circle.fill`). You can replace this with a custom image by updating the `profileImage` variable.
- **User Name**: The default name is "Rayaheen Mseri". This is displayed using a `Text` view and can be modified based on user interaction or data.
- **Button Action**: The button changes the displayed text color when pressed, but this can be customized to perform other tasks.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

