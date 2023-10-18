# learn-shell
In this repo we will keep the shell scripting fies.

# **Shell Topics:**
------------

1. Printing
2. Variables
3. Functions
4. Conditions
5. Loops
6. Exit Status
7. Inputs
8. Quotes
9. Redirectors
10. SED Editors


***Color Codes***
----------------
In Linux, color codes are used to add color and formatting to text output in the terminal. These codes are often referred to as ANSI escape codes. They use special escape sequences to change the appearance of text in the terminal. Here's a breakdown of the syntax for color codes in Linux:

****Escape Character:**** Color codes start with an escape character, which is represented as \033 in octal notation or \e in some contexts.

****Opening Bracket:**** After the escape character, an opening square bracket [ is used to indicate that the escape sequence is starting.

****Formatting Code:**** The formatting code is an integer or a semicolon-separated list of integers that specifies the desired formatting and color changes. These codes are used to set text color, background color, and text formatting.

****Closing "m" Character:**** After specifying the formatting code, the escape sequence ends with the letter "m." This character indicates the end of the formatting code.

****Text to Format:**** After the closing "m" character, you provide the text that you want to format with the specified settings.

****Reset Code:**** To reset the formatting and color to their default settings, you can use the reset code, which is \033[0m.

****Basic Formatting Codes:****

* 0: Reset all formatting and color.
* 1: Bold or increased intensity.
* 2: Faint (rarely supported).
* 3: Italic (rarely supported).
* 4: Underlined.
* 5: Blinking text (not recommended).
* 7: Inverted colors (swap foreground and background).
* 8: Hidden text (hidden from display).

****Text Color Codes:****

* 30: Black
* 31: Red
* 32: Green
* 33: Yellow
* 34: Blue
* 35: Magenta (purple)
* 36: Cyan
* 37: Light gray

****Background Color Codes:****

* 40: Black background
* 41: Red background
* 42: Green background
* 43: Yellow background
* 44: Blue background
* 45: Magenta background
* 46: Cyan background
* 47: Light gray background

****Usage Examples:****

* To print red text: echo -e "\033[0;31mThis text is red.\033[0m"
* To print bold and underlined blue text: echo -e "\033[1;4;34mBold, underlined blue text.\033[0m"
* To change the background color to green: echo -e "\033[0;42mText on a green background.\033[0m"
* These are just some basic examples. You can combine formatting and color codes to achieve various visual effects. However, be aware that not all terminals support all formatting options, so it's a good idea to test your codes in your specific terminal environment.