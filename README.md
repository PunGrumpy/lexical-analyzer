# 🔍 Lexical Analyzer Project

Welcome to our Lexical Analyzer project! This tool helps break down source code into meaningful tokens. 🚀

## ✨ Features

Our Lexical Analyzer can identify:

- ➕ Operators (+, -, \*, /, =, >, >=, <, <=, ==, ++, --)
- 🎭 Parentheses and semicolons
- 🔑 Keywords (if, then, else, endif, while, do, endwhile, print, newline, read)
- 🔢 Integers
- 🆔 Identifiers
- 📜 Strings
- 💬 Comments (both single-line and multi-line)

## 🛠 Prerequisites

Before you begin, ensure you have met the following requirements:

- ☕ Java Development Kit (JDK)
- 🦊 JFlex

## 🚀 Installation

1. Clone the repository:
   ```
   git clone https://github.com/PunGrumpy/lexical-analyzer.git
   ```
2. Navigate to the project directory:
   ```
   cd lexical-analyzer
   ```

## 🏃‍♂️ Usage

1. Generate the Lexer Java file:

   ```
   jflex src/Lexer.flex
   ```

2. Compile the Java files:

   ```
   java src/*.java
   ```

3. Run the analyzer:
   ```
   java -cp src Main <input_file>
   ```

## 📁 Project Structure

```
project_root/
│
├── src/
│   ├── Lexer.flex   🧩 JFlex specification file
│   └── Main.java    🎯 Main application file
│
├── input_1.txt      📄 Sample input file
├── input_2.txt      📄 Sample input file
├── input_3.txt      📄 Sample input file
└── .gitignore       🙈 Git ignore file
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 Fork the project
2. 🔧 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔀 Open a pull request

---

Happy coding! 💻✨
