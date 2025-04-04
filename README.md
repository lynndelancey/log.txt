#  JavaFX Menu Application

## **Project Overview**
This is a simple **JavaFX GUI application** that provides menu-based functionality:
- **Show Date & Time**: Displays the current system date and time in a text field.
- **Save to Log File**: Writes the contents of the text field to `"log.txt"`.
- **Change Background Color**: Applies a **random green hue** to the background.
- **Exit Program**: Closes the application.

## **Requirements**
- Java Development Kit (JDK) 17+
- JavaFX SDK
- Git for version control

## **Setup & Execution**
1. **Clone the repository**:
    ```sh
    git clone https://github.com/YOUR_USERNAME/JavaFX-Menu-App.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd JavaFX-Menu-App
    ```
3. **Compile & Run using JavaFX**:
    ```sh
    javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml UserInterfaceApp.java
    java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml UserInterfaceApp
    ```

## **Version Control Guidelines**
- Commit code changes using meaningful messages.
- Push updates to GitHub regularly.
- Maintain repository structure:
    ```
    ├── src/
    │   ├── UserInterfaceApp.java
    ├── README.md
    ├── log.txt
