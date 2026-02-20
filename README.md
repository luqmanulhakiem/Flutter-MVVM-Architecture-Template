# FLutter MVVM Architecture
This repository provides a clean, scalable implementation of the **Model-View-ViewModel (MVVM)** architectural pattern in Flutter. It is designed to separate concerns, making your code easier to test, maintain, and scale.

## 🧠 What is MVVM?

MVVM is an architectural pattern that facilitates a clear separation between the development of the graphical user interface (the View) and the development of the business logic or back-end logic (the Model).

* **Model:** Represents the data layer (entities, repositories, and API providers). It is responsible for fetching and managing data.
* **View:** The UI layer (Widgets and Screens). It only cares about how things look and sends user events to the ViewModel.
* **ViewModel:** The "brain" of the View. It transforms data from the Model into a state the View can easily consume. It handles business logic without being tied to a specific UI.

### 🌟 Perfect Usage Scenarios
MVVM is the ideal choice when:
* **Enterprise Applications:** You are building complex apps that require high maintainability and long-term support.
* **Test-Driven Development (TDD):** You need to write unit tests for business logic without mocking UI elements.
* **Team Collaboration:** Designers/UI Developers can work on the **View** while Logic Developers work on the **ViewModel** simultaneously.
* **State Management:** You want to use reactive frameworks like `Provider`, `Riverpod`, or `ChangeNotifier` to bind data to the UI efficiently.

---

## 📂 Folder Structure
<!-- TREEVIEW START -->
├── lib/
│  ├── data/           # Repositories, API providers, Models
│  ├── viewmodels/     # Business logic & State management
│  ├── views/          # UI Screens and Widgets
│  ├── core/           # Constants, Themes, Utilities
└── main.dart       # App entry point
<!-- TREEVIEW END -->

## 🛠️ Setup & Installation

Follow these steps to get the project running on your local machine:

### 1. Clone the Repository
Open your terminal and run:
```bash
git clone [https://github.com/luqmanulhakiem/Flutter-MVVM-Architecture-Template.git](https://github.com/luqmanulhakiem/Flutter-MVVM-Architecture-Template.git)
cd Flutter-MVVM-Architecture-Template
```
