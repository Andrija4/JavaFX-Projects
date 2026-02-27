# ☕ JavaFX Projects

A collection of JavaFX desktop applications demonstrating GUI development using Java and JavaFX.

This repository contains multiple small projects and exam practice applications built with JavaFX, focusing on UI design, event handling, and basic application architecture.

---

## 🚀 Overview

These projects demonstrate:

- JavaFX UI controls (Button, Label, TextField, ComboBox, TableView, ListView, etc.)
- Layout management (VBox, HBox, GridPane, BorderPane)
- Event handling
- Scene and Stage management
- Basic MVC structure
- Data handling and filtering
- Working with collections in JavaFX

Each project is self-contained and can be run independently.

---

## 🛠 Requirements

To run these projects you need:

- **JDK 17+ (Java 21 recommended)**
- **JavaFX SDK** (if using JDK 11 or newer)
- An IDE such as **IntelliJ IDEA**, **Eclipse**, or **NetBeans** (recommended)

> Note: JavaFX is not included in JDK 11+ by default. You must download and configure the JavaFX SDK separately.

---

## 📥 Clone the Repository

```bash
git clone https://github.com/Andrija4/JavaFX-Projects.git
cd JavaFX-Projects
```

---

## ▶ Running the Project (Recommended – IDE)

1. Open the project in your IDE.
2. Configure JavaFX SDK in project settings.
3. Set the VM options:

```
--module-path "PATH_TO_FX/lib" --add-modules javafx.controls,javafx.fxml
```

4. Run the `Main` class of the desired project.

---

## ▶ Running from Command Line

1. Download and extract JavaFX SDK.
2. Navigate to the `src` directory of the project.
3. Compile:

```bash
javac --module-path "PATH_TO_FX/lib" --add-modules javafx.controls,javafx.fxml application/*.java model/*.java view/*.java
```

4. Run:

```bash
java --module-path "PATH_TO_FX/lib" --add-modules javafx.controls,javafx.fxml application.Main
```

Adjust package names if needed.

---

## 📂 Project Structure (Typical)

```
JavaFX-Projects/
│
├── ProjectName/
│   └── src/
│      ├── application/
│      ├── model/
│      └── view/
│   
│
└── README.md
```

---

## 🎯 Purpose

This repository serves as:

- Practice for JavaFX development
- Exam preparation projects
- GUI architecture exercises
- Examples of Java desktop applications

---

## 🤝 Contributing

Contributions are welcome. You can:

- Improve UI design
- Refactor architecture
- Add new JavaFX demo projects
- Fix bugs or improve structure

---

## 📜 License

This repository currently does not include a specific license and is provided **"as-is"**.

If you plan to use this code publicly, consider adding an open-source license (e.g., MIT).

---

## 👨‍💻 Author

Andrija Ilic  
GitHub: https://github.com/Andrija4
