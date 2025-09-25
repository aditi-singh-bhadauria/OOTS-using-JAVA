# OOTS-using-JAVAOOTS using JAVA
This repository contains modular Java programs designed to demonstrate core concepts of Object-Oriented and Theoretical Systems (OOTS) using clean, extensible code. Each module is organized for clarity, dry-run validation, and compatibility with CodeTantra lab submissions.

📂 Folder Structure
OOTS using JAVA/
├── Array1/                     # Array operations and dry-run examples
├── Assertion and Localization/ # Java assertions and i18n basics
├── Exception1/                 # Exception handling with try-catch-finally
├── lambda1/                    # Lambda expressions and functional interfaces
├── Package2/                   # Package creation and access modifiers
├── String/                     # String, StringBuffer, StringBuilder examples
├── Thread/                     # Thread creation, Runnable, synchronization



📚 Topics Covered
- ✅ Arrays and memory layout
- ✅ Exception handling (checked, unchecked, custom)
- ✅ Lambda expressions and functional programming
- ✅ Package structure and access control
- ✅ String handling (immutable, mutable, performance)
- ✅ Multithreading (extends Thread, implements Runnable)
- ✅ Assertions and Localization (basic i18n)

🧪 Sample Code Highlights
🔹 String Handling
String s = "Hello";
String s2 = s.concat(" World");
System.out.println(s);  // Hello
System.out.println(s2); // Hello World


🔹 Exception Handling
try {
    int x = 5 / 0;
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
} finally {
    System.out.println("Cleanup done");
}


🔹 Thread Creation
class MyThread extends Thread {
    public void run() {
        System.out.println("Thread running");
    }
}
new MyThread().start();



🧠 How to Use
- Clone the repo:
git clone https://github.com/your-username/OOTS-using-JAVA.git
- Open in VS Code or your preferred IDE.
- Run individual .java files to test each concept.
- Use README.md comments and dry-run logic for lab documentation.

📄 License
This project is licensed under the MIT License — feel free to use, modify, and share with attribution.

