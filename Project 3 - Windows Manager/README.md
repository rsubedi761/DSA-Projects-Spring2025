# 🪟 Project 2 – Window Manager (Spring 2025)

This project simulates a simplified **Window Manager** application using custom **linked lists** and **stacks**. The system allows adding, removing, sorting, and drawing windows containing colorful, interactive squares on a GUI. It reinforces deep understanding of linked list operations, custom data structures, sorting, and GUI development.

---

## 🔧 Key Components

- `Square.java` – Represents colored squares with position, size, and clickable boundaries.
- `SquareList.java` – A custom singly linked list of `Square` objects supporting add, remove, and sort.
- `Window.java` – Encapsulates a visual window and tracks square contents, position, and selection state.
- `WindowStack.java` – A stack-based structure managing multiple windows in the correct z-order.
- `ThreeTenLinkedList.java` – Fully custom linked list with generic sorting methods and stability checks.
- `Node.java` – Lightweight node class supporting linked list structure.

---

## 📌 Features

- Create and remove **squares** within a window
- Add new **windows**, remove existing ones, and bring windows to the foreground
- Click handling to identify squares/windows under cursor
- GUI drawing using Java’s AWT `Graphics` API
- Sort windows by **size** or **location**
- Sort squares by **creation time** or **position**

---

## 📁 Project Files

- `Square.java`
- `SquareList.java`
- `Window.java`
- `WindowStack.java`
- `ThreeTenLinkedList.java`
- `Node.java`
- `WindowManager.java` (GUI controller)

---

## ✅ Skills Demonstrated

- Singly linked list implementation without dummy nodes
- Stack-based structure for GUI layers
- Custom sorting using `Comparator` and generics
- Event-driven programming with mouse handling
- GUI rendering using `java.awt.Graphics`
- Big-O complexity adherence
- JavaDoc and Checkstyle compliance

---

## 🧪 Testing Strategy

- Manual GUI interaction to verify drawing and sorting
- Inline `main()` testing methods in non-GUI classes
- Unit-like behavior testing using console outputs
- Edge case testing (empty lists, removing head/tail/middle nodes)

---