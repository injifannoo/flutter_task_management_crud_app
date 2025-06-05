# task_management

# Flutter Task Management CRUD App

A simple Task Management mobile application built with **Flutter**, implementing **CRUD** (Create, Read, Update, Delete) functionalities using the **BLoC pattern** and following **Clean Architecture** principles.

This project was developed as a pre-interview technical task for the **Flutter Developer** position at **Evergreen Technologies**.

---

## 🛠 Features

- ✅ Add new tasks
- ✅ View a list of tasks
- ✅ Edit/update existing tasks
- ✅ Delete tasks
- ✅ State management using **BLoC**
- ✅ Clean Architecture with clear separation of Data, Domain, and Presentation layers
- 🔄 (Optional) Real-time socket integration *(Not implemented)*

---

## 📱 APK Download

[Click here to download the APK](#) <!-- Replace `#` with actual link if available -->

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (version >= 3.x.x)
- Dart SDK
- Android Studio or VS Code

### Run the App Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/flutter_task_management_crud_app.git
   cd flutter_task_management_crud_app
   ```
   
2. **Install dependencies:**

```bash
flutter pub get
```
3. **Run the app:**

```bash
flutter run
`
``
**📁 Project Structure (Clean Architecture)**

```bash
lib/
│
├── data/                # Data layer: models, repositories, and data sources
├── domain/              # Domain layer: entities and use cases
├── presentation/        # UI layer: widgets, screens, and BLoC
├── core/                # Shared code (constants, utilities)
└── main.dart            # Entry point
```
**🤔 Assumptions**
Tasks have a title and description only (no due dates, priority, or tags).

No backend integration; data is stored in-memory.

UI is designed for simplicity and functionality, not styling.

**⚡ Bonus (Real-time Feature)**
Not implemented. If implemented, the app would use WebSocket or Firebase for broadcasting CRUD events across clients and showing an active user count.

**📧 Contact**
Developed by Enjifano Tamiru
Email: injifanotu@gmail.com
GitHub: @injifannoo

**📝 License**
This project is licensed under the MIT License.
