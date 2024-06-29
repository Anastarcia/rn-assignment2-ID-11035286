# rn-assignment2-ID-11035286
STUDENT ID: 11035286
![WhatsApp Image 2024-06-29 at 14 00 02_7d3c7d9d](https://github.com/Anastarcia/rn-assignment2-ID-11035286/assets/173105893/f0538afd-9129-4b8b-ba87-d8e36bbd3c6b)

Description:
Imports:

The code imports necessary components from the expo-status-bar and react-native libraries:
StatusBar from expo-status-bar: Used to control the app's status bar.
StyleSheet, Text, and View from react-native: Used to create and style the application's components.
App Component:

The default exported App function component represents the main part of the application.
JSX Structure:

The component returns a View component that serves as a container for other components and applies styles from styles.container.
Inside the View:
A Text component displays the message "My name is Anastarcia", with part of the text being bold. This is achieved by nesting a Text component inside another Text component.
The StatusBar component is included with auto styling to handle the status bar's appearance.
Styles:

The StyleSheet.create method is used to define a set of styles:
container: Styles applied to the outer View component. It makes the container fill the entire screen (flex: 1), sets the background color to a cyan shade (#00ffff), and centers its children both vertically and horizontally (alignItems: 'center' and justifyContent: 'center').
text: Styles applied to the main Text component. It sets the font size to 24.
boldText: Styles applied to the nested Text component to make the name "Anastarcia" bold (fontWeight: 'bold').
