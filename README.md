# Recursion & Call Stack Explorer 🔍

This interactive web tool is designed to help students visualize and truly understand one of the trickiest concepts in computer science: **Recursion**. 

If you've ever felt confused about how a function can "call itself" without getting stuck in an infinite loop, this tool is for you!

## 🌟 What You Will Learn
- **How Recursion Works**: Watch step-by-step as a problem is broken down into smaller pieces.
- **The Call Stack**: See exactly how the computer's memory manages multiple paused functions, stacking them like plates.
- **The Base Case**: Understand why the "anchor" condition is critical to prevent your program from crashing.

## 🚀 How to Use the Explorer

1. **Choose Your Language**: At the top of the code box, select either **Python** or **C++** to see the code in the language you are most comfortable with.
2. **Select an Input**: Use the dropdown menu `Calculate for n =` to pick a starting number (e.g., 3, 4, or 5).
3. **Step Through the Code**: 
   - Click the **Next** button (or press the `Right Arrow` key on your keyboard) to move forward one step.
   - Watch the **yellow highlight** move through the code to see exactly which line is executing.
   - Read the **"What is happening?"** box for a plain-English explanation of the current step.
4. **Watch the Call Stack**: Keep an eye on the right side of the screen. You will see new boxes (function calls) being pushed onto the stack. Notice how older functions are marked as **Paused** while they wait for the newer functions to finish!
5. **Restart**: Want to see it again? Click the red circular arrow button to reset the simulation.

## 🧠 Key Concepts to Look Out For

- **Pushing to the Stack**: Every time `factorial()` calls itself, a new frame is added to the *top* of the stack.
- **Popping from the Stack**: Once the *Base Case* (`n == 1`) is reached, the function finally returns a real number. Watch as the stack frames begin to resolve and disappear ("pop") one by one, multiplying the numbers together on their way down.
- **LIFO (Last In, First Out)**: Notice that the *last* function called is always the *first* one to finish.

## 🌐 Language Support
Click the **中 / EN** button in the top right corner to instantly switch the entire application between English and Traditional Chinese.
