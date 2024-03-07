Fast Function Runner 
[Alt]+[R]
Your favorite Functions/Methods/Commands - in one place, with easy access to run or edit,
hotkeys and parameter customization. 
Ideal for fast prototyping, development, and workflow enhancement.

#Quick Start
1. Add:
Search and add any Method or Command at the bottom of window 

Or you can add [FastFunction] attribute to method/function


2.Run:  Press the button with the function name to run it. Even if the window is closed you can execute them by shortcuts.


	[Alt]+[1] - Choose Page 1  … [Alt]+[9] - Choose Page 9 
[Space]+[1] - Run Function 1 … [Space]+[9] - RunFunction 9
[Delete] + [Delete] - Remove Function
[M]+[1] - Move selected function to Page 1 … [M]+[9] - Move selected function to Page 9


Functions

To execute a function. Simply click on the button or press Hotkey: [Space]+1 to execute the first function in the current active page. Similarly you can press  [Space+2] … [Space+9] to run corresponding functions by their order number.

You can change position, icon, and the display name of  functions. Press the middle mouse button to change the display name of a function or page. To remove the function from the current page - select a function, press the small “-” button at the bottom of a list.
Also you can press: [Delete] / [M] to Delete/Move functions to another page;

You can run the methods with parameters. 
Parameters can be type of: Bool, Integer, Float, String, Vector2, Vector3, Quaternion, Color, UnityObject (like Sprites, Textures, Materials, GameObjects etc..) and so on. Also, custom classes are supported.

Limitation: custom structs (not built-in structs), since Unity3d doesn’t support serialized reference for structs
Pages
Press on page name (above functions list) to open the page chooser window. Here you can:  

Add/Remove page. 
Change positions. 
Rename page by pressing the middle mouse button.
Colorize your page.

Green dots are representing the functions count in a page.
Notice: The position of the page matters in the hotkeys system. 
Hotkeys:  [Alt+1] [Alt+2] … [Alt+9] to open the corresponding page in the main window.
When the Page Editor window is opened you can press digit [1][2]...[9] or [Del] to remove.
So: 
[M]+[1] Move selected page to Page1 
[Del]+[Del] Delete selected functions


Hotkeys
Special attention has been given to hotkeys in Function Runner. They provide convenience and efficiency. They are intuitive, simple, helping to focus on creativity and development.
Any button or function described with a hint.


Choose page: [Alt+[1-9] 
Previous page: [Alt]+[~]
Execute function: [Space]+[1-9] 
Move functions:[M]+[1-9]
Delete function: [Del]+[Del]
Zoom functions: [Ctrl]+mouse scroll wheel

You can assign some hotkeys in the options.
If there are conflicting hotkeys, the tool will notificate you, and will suggest you to remove it if you will.
Be careful! Deleting hotkeys cannot be undone (with Ctrl+Z) until you reassign them manually in the ShortcutsManager window (Edit>Shortcuts..).

If the main window is closed you can still use these hotkeys. It’s useful if you testing your gameplay and don’t want to open a window to run a function.  This behavior can be toggled in options
 

Extras
1. Rename Function/Page. You can press the Middle Mouse Button on Function or Page to start renaming. Mouse cursor has to be inside of function or page button while renaming. Moving mouse cursor outside will confirm the new name 


2. Set icon. Press on the index of function to set the icon for the function
Before:


After:


3. Switch to the previous page. Press RMB on page name button to switch to previous page
[Alt]+[~]


4. Zoom functions. By holding [Alt]: Page name button will turn into this:

Here you can find + and - buttons. Press and hold them to zoom in and zoom out functions.
Hotkeys: [Ctrl]+mouse scroll wheel. By picking the number while [Alt] is holding you will choose corresponding page
Zoom x1

Zoom x3



5. Copy Functions
You can make a copy of a function. Press the middle mouse button on the function and press “Make Copy” button several times and put different parameter values. 
Now you are able to call the same function but with different parameters. 
It’s very powerful  and useful when you are testing or prototyping your games.


Copied functions differ by color, indentation and name

6. Go To Functions Definition
When you right click on the function you are able to go right to the function definition your External script editor. Once again: It’s very comfortable to tweak your function when you testing or prototyping your games

7. Debug/Diagnostic mode


Where to use
Editor workflow improving
Prototyping 
Developing and Debugging


1.Find
To find any function You can just start typing the name of a static function or the path of the main menu command. Search is non-sensitive to upper/lower cases as well as whitespaces in command paths. 
2. Add
To add a function just hit on any found function name.
Another way of adding a function is the [FastFunction] attribute. It allows you to add non-static method as well
Please Notice. Non-static functions require the target for executing. If it’s set to null and you will try to execute the function then the tool will try to find the target automatically in the scene. So you don’t need to worry about the target. But be aware, because it can run on unwanted instance
3.Execute

Limitations: Due to the huge amount of non-static methods and functions only static functions are available for search. If you are interested in adding non-static functions you need to add [FastFunction] attribute to your method. 


For example
Page1 (Create asset):
 

Also there is hotkeys exist which 
Methods can be public or static
