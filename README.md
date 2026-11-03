# IT313_Ontario_Francismie_CoreComponents

## Laboratory 6 – IT 313 Mobile Programming

## Problem description
The Student Directory Viewer is a small Expo (React Native) application that allows an adviser to browse five students who need academic advising. The adviser can search students by name and flag or unflag a student for advising.

### `StudentCard` (`components/StudentCard.js`)
The reusable child component receives `id`, `name`, `year`, `photoUrl`, `flagged`, and `onToggleFlag` as props. It displays the student's photo, name, year level, and a `Pressable` control. The control's appearance changes when it is pressed and when the student's flagged state changes.

## React Native core components used
- **View:** Groups and arranges the screen elements and each student card.
- **Text:** Displays headings, student names, year levels, and button labels.
- **Image:** Displays each student's remote profile photo with a fixed width, height, and rounded corners.
- **ScrollView:** Makes the student cards scrollable.
- **TextInput:** Accepts the search text. Its `value` and `onChangeText` props keep it controlled by React state.
- **Pressable:** Makes the advising flag control respond to touch and show pressed/flagged styles.

## How to run the app

1. Install Node.js LTS if it is not already installed.
2. Open this project folder in Visual Studio Code.
3. Open the VS Code terminal (**Terminal → New Terminal**).
4. Install the project dependencies:

   ```bash
   npm install
   ```

5. Start Expo:

   ```bash
   npx expo start
   ```

6. Open Expo Go on your phone and scan the QR code, or run the project in an available emulator.

If the development server has cache issues, stop it with `Ctrl + C` and run:

```bash
npx expo start -c
``
I Create a **public** GitHub repository named:
`IT313_Ontario_Francismie_CoreComponents`
