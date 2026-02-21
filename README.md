# Inventory-Management-System
A desktop-based Inventory Management System (IMS) built in Java that allows users to manage, search, sort, and persist inventory data using a clean, layered architecture. This project was designed to demonstrate strong object‑oriented principles, file I/O, and structured system design.

🚀 Features
Add, edit, and remove inventory items

Multiple item types using inheritance and polymorphism

Perishable Items
Electronic Items
Clothing Items
Automatic unique ID generation

Search functionality (ID-based and attribute-based)

Sorting utilities (custom sorting logic)

Persistent storage using CSV files

User-friendly GUI built with Java Swing

Error handling & validation for safe data entry

🧱 System Architecture
The application follows a multi-layered architecture for maintainability and scalability:

UI Layer
 └── MainFrame, Toolbar, Dialogs

Controller / Logic Layer
 └── InventorySystem

Model Layer
 ├── Item (Interface)
 ├── BaseItem (Abstract Class)
 │    ├── PerishableItem
 │    ├── ElectronicItem
 │    └── ClothingItem

Data / Persistence Layer
 └── CSV Reader & Writer
This separation ensures:

Clean responsibility boundaries
Easier debugging and testing
Extensibility for new item types or storage formats
🖥️ Technologies Used
Java (JDK 8+)
Java Swing – GUI
Object-Oriented Programming
File I/O (CSV persistence)
Custom sorting & searching algorithms
📂 File Structure
InventorySystem/
├── src/
│   ├── ui/
│   ├── controller/
│   ├── model/
│   └── data/
├── inventory.csv
├── README.md
└── .gitignore
📝 How Data Persistence Works
Inventory data is stored in a CSV file
On application startup, data is loaded into memory
All changes (add/update/delete) are written back to the CSV
Ensures data is preserved between sessions
▶️ How to Run
Clone the repository

git clone https://github.com/your-username/inventory-system.git
Open the project in IntelliJ IDEA / Eclipse / VS Code

Ensure you are using JDK 8 or higher

Run the Main class

🎯 Learning Outcomes
This project demonstrates:

Strong understanding of OOP concepts (inheritance, abstraction, polymorphism)
Practical use of interfaces and abstract classes
Real‑world file handling and persistence
GUI development with Swing
Designing software using clean architecture principles
🔮 Future Improvements
Switch from CSV to database storage (SQLite / MySQL)
Add user authentication & roles
Implement advanced filtering & reporting
Export inventory reports (PDF / Excel)
Improve UI styling with custom themes
📄 License
This project is for educational purposes. Feel free to fork, modify, and build upon it.

👤 Author
Divy Patel Specialized Honours BA – Information Technology York University

If you’re an employer or collaborator reviewing this project: this system was designed with clarity, structure, and real‑world applicability in mind.
