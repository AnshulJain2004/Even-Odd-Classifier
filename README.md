# **Even-Odd Classifier**

Welcome to the **Even-Odd Classifier** repository! This project demonstrates a straightforward approach in Java to separate user-entered integers into even and odd categories. It consists of two Java files:  
1. **EvenOddClassifier.java** – Contains the main class and user interaction logic.  
2. **NumberSeparator.java** – Handles the separation of numbers into even and odd arrays.

---

### How It Works
1. The program prompts the user to enter the size of an array.  
2. It then accepts integer inputs from the user, one at a time.  
3. Each integer is immediately classified as _even_ or _odd_ and stored in a corresponding array within the `NumberSeparator` class.  
4. After all inputs have been collected, the program displays the stored even numbers followed by the stored odd numbers.

---

### Project Structure
- **EvenOddClassifier.java**  
  - Uses a `Scanner` to read input from the console.  
  - Creates a `NumberSeparator` instance with a user-specified size.  
  - Iterates to read each number from the user and passes it to `NumberSeparator`.  
  - Finally, it calls methods to display the collected even and odd numbers.

- **NumberSeparator.java**  
  - Maintains two arrays: one for even numbers and one for odd numbers.  
  - Methods provided:
    - `addNumber(int num)`: Classifies and stores the number into the correct array.  
    - `displayEvenNumbers()`: Prints all stored even numbers.  
    - `displayOddNumbers()`: Prints all stored odd numbers.

---

### Getting Started
1. **Clone or download** this repository.  
2. **Compile** the Java files:  
   ```bash
   javac EvenOddClassifier.java NumberSeparator.java
   ```  
3. **Run** the program:  
   ```bash
   java EvenOddClassifier
   ```  
4. **Follow** the prompts in your console window. You will be asked for:  
   - An integer indicating the array size.  
   - That many integers to classify.  

---

### Example
```
Enter the size of the array: 5
Enter number 1: 2
Enter number 2: 5
Enter number 3: 7
Enter number 4: 10
Enter number 5: 12

Even numbers:
2 10 12

Odd numbers:
5 7
```

---

### Why This Project?
- **Practical Demonstration**: Shows basic input handling and array operations in Java.  
- **Modular Approach**: Separates logic into two classes for better readability and scalability.  
- **Educational Value**: Ideal for beginners learning about conditionals, arrays, and class-based organization in Java.

---

### Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have improvements or suggestions—whether that’s optimizing the logic, adding new features, or enhancing documentation.

---

### License
This project is released under the [MIT License](LICENSE), allowing you to modify and distribute the code freely.  
