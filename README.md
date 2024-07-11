Bit Manipulation in Java
Welcome to the Bit Manipulation in Java repository! This project is dedicated to showcasing various bit manipulation techniques and algorithms implemented in Java.

Table of Contents
Introduction
Prerequisites
Installation
Usage
Bit Manipulation Techniques
Examples
Contributing
License
Introduction
Bit manipulation is a powerful tool in programming that allows you to perform operations directly on binary digits (bits). This repository provides a collection of common bit manipulation techniques and examples to help you understand and apply these techniques in Java.

Prerequisites
Java Development Kit (JDK) 8 or higher
Basic knowledge of Java programming
Familiarity with binary numbers and bitwise operations
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/bit-manipulation-java.git
Navigate to the project directory:
sh
Copy code
cd bit-manipulation-java
Compile the Java files:
sh
Copy code
javac -d bin src/*.java
Usage
To run the examples provided in this repository, use the following command:

sh
Copy code
java -cp bin Main
Bit Manipulation Techniques
This repository includes implementations of various bit manipulation techniques, such as:

Setting a bit
Clearing a bit
Toggling a bit
Checking a bit
Counting set bits (Hamming weight)
Checking if a number is a power of two
Swapping two numbers without using a temporary variable
Finding the most significant bit
Reversing bits
Each technique is implemented in a separate method within the BitManipulation class.

Examples
Example 1: Setting a Bit
java
Copy code
public static int setBit(int num, int pos) {
    return num | (1 << pos);
}
Example 2: Clearing a Bit
java
Copy code
public static int clearBit(int num, int pos) {
    return num & ~(1 << pos);
}
Example 3: Toggling a Bit
java
Copy code
public static int toggleBit(int num, int pos) {
    return num ^ (1 << pos);
}
Example 4: Checking a Bit
java
Copy code
public static boolean checkBit(int num, int pos) {
    return (num & (1 << pos)) != 0;
}
For more examples and detailed explanations, please refer to the source code in the src directory.

Contributing
Contributions are welcome! If you have any suggestions, improvements, or new bit manipulation techniques to add, please open an issue or submit a pull request.

Fork the repository.
Create a new branch: git checkout -b feature/your-feature-name
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/your-feature-name
Open a pull request.

Feel free to clone this repository and experiment with the examples to enhance your understanding of loops in Java. Happy coding!
