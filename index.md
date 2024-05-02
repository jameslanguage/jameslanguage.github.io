# James Programming Language: User Manual
This user manual is for JAMES88, updated for v1.0.

# 1. Functions in Programs
`james`\
Initializes the system and declares the start of the program. Only put this once, at the start of your program. If you do not type this, no commands will work.

`create [variable]`\
Declares a variable for use. A newly created variable will hold the value `null`.

`set [variable] [value]`\
Overwrites the current value of a variable, and sets it to a value or another variable.

`add [variable] [value]`\
Adds a value or another integer/float variable to a variable. Note that the existing variable must hold a value of an integer or a float, otherwise it will return a Jamal value. [Read here](#jamals) for more information.

`destroy [variable]`\
Destroys a variable. Do note that the value that the variable holds will also be destroyed in the process. Not quite practical, but kind of fun to use.

`print [value]`\
Prints a value or a variable onto the screen.

`jamal`\
Jamals the system. Check below for more info.

`wait [seconds]`\
Pause the program for a specified time.

`clear`\
Clears everything on the screen.

# 2. Commands on the Command Line

`run`\
Runs the code.

`edit`\
Edit the current code, starting at the last line.

`edit line`\
Edits the current code at a specified line.

`add line`\
Inserts a new line under the current editing line.

`export`\
Exports the current program to a shareable code. Also copies the code to the clipboard.

# 3. Data Types

### Integers
Integers are whole numbers like `1`, `-3`, `888`, `234567`.

### Floats
Floats are numbers with decimals like `2.0`, `0.17`, `-1.11`, `3.1415926`.

### Strings
Strings are text surrounded by parentheses, like `(James)`, `(Hello World!)`, `(12 quick brown foxes)`, `(AAAAAAAAAAAAAAAAAAAAA)`

### Jamals
Jamals are a special type of data which corrupts the program. These usually come from an error.\
An example of such a value is `JAMES88-JML!%&??1!$!`.\
> **Did you know?**\
> A Jamal can easily be found from attempting to `add` an integer value into a variable that contains a string.

# 4. System Values
The `system` variable keeps data about the current session. It cannot be read or written onto.\
> **Did you know?**\
> `jamal` works by setting this variable to a [Jamal value](#jamals).

# 5. Examples
*This section is coming soon...*
