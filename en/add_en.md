## Gameplay - Part 7 (Advanced Level)

### Introduction to Numbers

Without assigning numerical values to commands (above or below the command), the robot uses default movement parameters:  
- Move forward by 10 cm (100 mm).  
- Turn by 90 degrees.  

You can control these values by adding numerical parameters to commands in paired cells.  

Example: Add the value **200** to the **"Forward"** command and observe how far the robot moves. Add the value **180** to the **"Turn"** command and evaluate the changes.  

![example1](images/example1.excalidraw.svg)

> **Important:** The remote control retains the last set value for movement and turning. 
- If a command is used without specifying a new value, the last recorded value is applied until the remote is turned off! 
- Thus, setting a new parameter changes the default value.  
- You can restore the original values (100 mm and 90°) by explicitly specifying them in the commands or by turning the remote off and on again.  

Flexible number control expands learning possibilities. By changing the distance and rotation angle, you can:  
- Create complex shapes.  
- Program movement along a curved trajectory.  
- Implement new movement scenarios.  

Use variable parameters to take robot control to a new level. Check out examples on the [mathematical drawings page](/ru/math_drawings_ru).

---

## Gameplay - Part 8 (Advanced Level)

### Introduction to Arithmetic Operations

Numeric values with arithmetic operations modify movement commands. This allows dynamically changing movement commands (Forward, Backward, Left, Right), making robot control more flexible.

How does it work?
When you add an arithmetic operation, the remote control modifies the stored number for the movement command and sends the new value to the robot.

Example:
The command "Forward 200" will make the robot move 200 mm (20 cm).
If the next command is "Forward +100," the robot will move 300 mm (30 cm).

![example2](images/example2.excalidraw.svg)

If such commands are used in a loop, they can create number sequences—arithmetic and geometric progressions.

> Important point: If a command decreases the value to a negative number, the robot will perform the opposite action: 
Instead of moving forward, it will move backward.
Instead of turning left, it will turn right.

Available arithmetic operations:
- Addition (+) — increases the value.
- Subtraction (-) — decreases the value.
- Multiplication (*) — increases the number multiple times.
- Division (/) — reduces the number.
- Square root (√) — extracts the square root.
- Power (^) — raises to the specified power.

Want to see how to create complex mathematical patterns with these operations? Check out the [mathematical drawings page](/ru/math_drawings_ru)!

---

## Play and Learn with Children!

You know your students and how to work with them better than anyone. The development and education of children depend on you. PrimaSTEM is a universal tool for teaching children not only logic and programming but also other subjects. Use its flexibility and versatility to create a playful learning environment. It all depends on your imagination!