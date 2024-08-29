# focusStateDemo

`focusStateDemo` is a demonstration application built using SwiftUI, focusing on managing input field focus using `FocusState` and `FocusedValue`. This project illustrates how to handle focus in SwiftUI effectively.

## Project Structure

The project is organized into the following files and directories:

```
focusStateDemo/
├── focusStateDemoApp.swift
├── FocusStateDemoView.swift
├── CommentPreview.swift
├── FocusedValues+CommentFocusedValue.swift
├── Assets/
└── Preview Content/
```

### File Descriptions:

- **`focusStateDemoApp.swift`**: The entry point of the application. It sets up the main scene and initializes `FocusStateDemoView` as the root view.
  
- **`FocusStateDemoView.swift`**: The primary view that includes multiple text fields and a button for managing focus. It utilizes `FocusState` to switch focus between different fields.

- **`CommentPreview.swift`**: A view that displays the content of the currently focused text field using `FocusedValue`. It is used to provide real-time feedback based on the user's input focus.

- **`FocusedValues+CommentFocusedValue.swift`**: This file contains the custom `FocusedValueKey` and its associated extension to manage focused values within the application.

- **`Assets/`**: The directory containing the assets (like images) used in the application.

- **`Preview Content/`**: The directory used for previewing the content during development.

## Features

- **Focus Management**: Using `FocusState`, the application manages focus between multiple input fields.
- **Custom Focused Values**: The application uses `FocusedValue` to track and display the currently focused text field's content.
- **User Interface**: A simple and intuitive user interface to demonstrate focus management in SwiftUI.

## Installation and Running

To run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/parkmino86/swiftUI-focusStateDemo.git
    ```

2. **Open in Xcode**:
    ```bash
    open focusStateDemo.xcodeproj
    ```

3. **Build and run**:
    Open the project in Xcode and click the `Run` button to build and launch the application.

## Usage

- **Text Fields**: Enter text into the `Name`, `Email`, and `Any comment?` fields. The focus can be switched between these fields using the `FocusState`.
  
- **Submit Button**: Clicking the `Submit` button will clear the focus from all fields.

- **CommentPreview**: This view dynamically displays the content of the currently focused text field.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contribution

Contributions are welcome! Please submit a pull request with any improvements, bug fixes, or additional features you think would enhance this project.

---

This README provides a comprehensive overview of the project, including how it is structured, its main features, and how to set it up and run it.
