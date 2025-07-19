
# 🚆 Train Ticket Booking System

A simple **console-based Java application** for booking train tickets. It features user registration, login, train search, and ticket booking functionality. Designed as a beginner-friendly project to demonstrate core Java concepts like OOP, file I/O, collections, and service-layer separation.

---

## 📂 Project Structure

```
ticketBookingApp/
├── app/
│   ├── src/
│   │   ├── main/java/ticket/booking/
│   │   │   ├── App.java                    # Entry point
│   │   │   ├── entities/                   # Domain models (Train, Ticket, User)
│   │   │   ├── service/                    # Business logic for booking
│   │   │   └── util/                       # Utility functions
│   │   └── test/java/ticket/booking/       # Unit tests
├── build.gradle                            # Gradle build file
├── settings.gradle
└── gradle.properties
```

---

## 🛠️ Features

- ✅ **User Sign-up & Login**
- 🚉 **Add/View Trains**
- 🎟️ **Book Tickets**
- 📃 **View User Bookings**
- 🧹 **Admin-only controls for managing train data**
- 💾 **Data stored in local files (file I/O)**

---

## 🧰 Technologies Used

- Java 17+
- Gradle (Build Tool)
- File-based persistence (no external DB)
- OOP Principles (Encapsulation, Abstraction, Inheritance, Polymorphism)

---

## ▶️ How to Run

### Clone the repository:

```bash
git clone https://github.com/your-username/ticketBookingApp.git
cd ticketBookingApp
```

### Build the project:

```bash
./gradlew build
```

### Run the application:

```bash
./gradlew run
```

### Alternatively, using Java CLI:

```bash
cd app/src/main/java
javac ticket/booking/App.java
java ticket.booking.App
```

---

## 🧪 Running Tests

To execute unit tests:

```bash
./gradlew test
```

---

## 📌 Notes

- Data is stored in local `.txt` files. Make sure your program has the necessary permissions to read/write.
- The application is terminal-based and ideal for understanding the flow of a basic ticket management system.
- Easily extendable to include real databases or GUI features.

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 👤 Author

**Dipak Borkhatariya**  
Connect with me on [LinkedIn]( https://www.linkedin.com/in/dipak-borkhatariya-ab4104274 )
