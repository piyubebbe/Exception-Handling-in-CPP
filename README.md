# Implementation of Exception Handling in C++

**Aim:** Implementation of exception handling in C++  
**Software:** Mingw C++ compiler, VS Code, Online C/C++ compiler  

---

## Program 1: For Numbers

### Theory with Explanation
This C++ program demonstrates exception handling during division. It prompts the user to input two floating-point numbers, `n1` and `n2`. Before performing division, it checks if `n2` is zero to avoid a runtime error. If `n2 == 0`, it throws an exception, which is caught by the `catch` block, displaying an error message. Otherwise, it computes and prints the result of `n1 / n2`.  

This approach ensures safe execution and prevents undefined behavior due to division by zero. The use of `try-catch` enhances robustness and user feedback in mathematical operations.

### Algorithm
1. Start  
2. Input `n1` and `n2`  
3. If `n2 == 0`, throw exception  
4. Else, compute `ans = n1 / n2`  
5. Display result  
6. Catch and display error if exception occurs  
7. End  

---

## Program 2: For Age

### Theory with Explanation
This C++ program uses exception handling to validate age input. It prompts the user to enter an age and checks if the value is below 18. If the age is less than 18, the program throws an exception, which is caught by the `catch` block and displays an error message indicating the person is underage.  

If the age is 18 or above, it prints an approval message. This structure ensures that invalid inputs (underage cases) are handled gracefully, improving program reliability and user feedback. The use of `try-catch` makes the logic robust and suitable for real-world validation scenarios.

### Algorithm
1. Start  
2. Prompt user to input age (`n1`)  
3. If `n1 < 18`, throw exception  
4. Else, print `"APPROVED"`  
5. Catch and display `"UNDERAGE"` error with age  
6. End  

---

## Conclusion
Both programs showcase the practical use of exception handling in C++ to ensure safe and user-friendly execution.  

- The first code prevents division by zero, a common runtime error.  
- The second validates age input to enforce a minimum threshold.  

By using `try-catch` blocks, the programs gracefully handle invalid conditions without crashing, enhancing reliability and clarity. These examples highlight how exceptions can be used not just for error control, but also for enforcing logical constraints in real-world applications.  

Such structured handling improves user experience and sets a foundation for building robust, interactive systems with clear feedback and validation logic.  
