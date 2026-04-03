# MY FIRST JFRAME APPS on NETBEANS

FIRST OF ALL , huge thanks to **[Mukul Saini Skills](https://www.youtube.com/watch?v=Kq-GsRdn5dY&list=PLjJmj2FyqToambmQaaGFgzB3M3OCuGGEG)** !

This project was developed for educational purposes following the tutorials of Mukul Saini. I built it to practice Java Swing and GUI logic.

**The aim:** These projects help me understand GUI development and improve my hands-on coding skills.

## Building Simple Calculator
Previously, operators like '+' were hidden during input.So at the first time I couldn't understand whether the calculator works or not . Now, the display shows the full expression (e.g., 2 + 2) in real-time for better clarity.

## Distance Speed Time Calculator

A basic,practical desktop application built with **Java Swing** that calculates Distance, Speed, or Time based on user input. This project helped me to understand the gap between theoretical math formulas and real-world GUI application logic.

### What I Learned & Applied

* **Input Handling:** Converting String inputs from text fields into `double` for calculations using `Double.parseDouble()`.
* **Precision Control:** Used `String.format("%.2f", value)` to ensure results are clean and rounded to 2 decimal places (e.g., showing **3.33** instead of **3.33333333**).
* **User Feedback:** Mastered the use of **JOptionPane** for error handling and information dialogs.
* Special thanks to **[Mkyong.com](https://mkyong.com/swing/java-swing-how-to-make-a-simple-dialog/)** for the detailed examples of `showMessageDialog` versions.

## Mini Piano

In this project, I built a Mini Piano by following Mukul Saini's tutorials to practice Java Swing and audio handling. I implemented a sound system using **AudioInputStream** and **Clip** within a **try-catch** block for error management. Additionally, I encountered a GUI challenge where the background color wouldn't update through the properties panel; I resolved this by forcing the color change using **getContentPane().setBackground()**

### I learned in this project : 

* **Audio Handling:** Using AudioSystem to load and play .wav files.

* **Error Management:** Wrapping sensitive operations in try-catch blocks.

* **GUI Customization:** bypassing IDE limitations by using getContentPane().setBackground() to ensure the background displays as pink.

## Basic Interest Calculator 

This project is a financial tool that calculates interest based on user-provided principal, rate, and time. It focuses on clean GUI logic by followong Mukul Saini's tutorials and especially I specialized this project with robust error handling.

### WHAT I learned in this project ?

* **Dynamic Formulas:** Implemented both Simple Interest ($I = P \times r \times t / 100$) and Compound Interest ($A = P(1 + r/n)^{nt}$) logic.
* **Robust Error Handling:** Used try-catch blocks specifically to handle NumberFormatException. This prevents the application from crashing if a user enters letters or symbols instead of numeric values.
* **User Feedback:** Integrated JOptionPane to provide real-time alerts for empty fields or invalid inputs.
