		  ----VBS MAKER TUTORIAL----

	WHAT IS .VBS?

    A .vbs file is a script file written in VBScript (Visual Basic Scripting Edition). VBScript is a scripting language developed by Microsoft and is designed for use in Windows environments. VBScript is often employed for tasks related to automation, system administration, and scripting within the Windows operating system.

   Here are some key points about .vbs files and VBScript:

Scripting Language: VBScript is a scripting language interpreted and executed by the Windows Script Host (WSH). It's similar to other scripting languages like JavaScript.

Text-Based: A .vbs file is a plain text file containing VBScript code. You can create and edit .vbs files using a simple text editor like Notepad.

Automation: VBScript is commonly used for automating repetitive tasks, interacting with system components, and performing various operations on Windows-based systems.

Windows Script Host (WSH): The Windows Script Host is a component of the Windows operating system providing an environment for executing scripts written in scripting languages like VBScript. It allows scripts to interact with the operating system and other Windows components.

Examples of Use: .vbs scripts can perform tasks such as file manipulation, system configuration, interaction with the Windows Registry, network operations, and more. They are often employed in scenarios requiring automation and scripting.

Event Handling: VBScript can be used to respond to events, such as system events or user interactions, making it useful for creating custom automation solutions.

Overall, a .vbs file is a text file containing VBScript code that can be executed to perform various operations on a Windows system. It provides a way to automate tasks and customize the behavior of a Windows environment through scripting.

	HOW TO USE THE TOOL:

  The tool is designed to create such a file more efficiently, with the user only having to select what kind of commands to input into the file.

  The tool consists, at the start, of a simple layout involving the Banner and three options:

 	-Create: This option creates a FILE.vbs file that can be additionally modified. This option can only create .vbs files with this exact name. If you want to create another or more .vbs files, you'll need to change the name or directory of the file. When a FILE.vbs already exists, the "Create" option will be replaced by the "Open" option, which additionally lets you edit the file.
	-Help: This option, which probably led you here.
	-Menu: This option sends you back to the main screen of the script.
The editor consists of seven actions:

	-[1] Delay: The delay command inserts an amount of time the script should wait, usually used between commands that start apps and need time to wait for startup (a casual example). Also, the value 1000 is equivalent to 1 second.
	-[2] Press key: The press key command will lead you to a two-option menu consisting of the following: -- One key, where you only need to insert the name of the key (e.g., "ENTER" or "SPACE"); and the: -- Multiple keys. The format that should be followed should look like "^"+"{ESC}" (this is the combination of keys that simulates the Windows key since not all keyboards might have it + there isn't any .vbs command for it, or at least in my field of knowledge), where the key itself is between "{}" and a normal text key just in "". The script will simulate the pressing of the keys as if the user were using it. REMINDER: UAC, the pop-up GUI, deactivates any in-run scripts like .vbs.
	-[3] Insert text: The insert text command is pretty self-explanatory. It's a command that inserts text, preferably somewhere where text can be inserted, like a text-based file or a web search box (or in the Windows search menu after pressing the Windows key).
	-[4] Remove last line: Coming soon (I'm only human, after all). As an alternative, you can delete the lines by opening the .vbs file with Notepad or Notepad++.
	-[5] View: Showcases all the commands that the .vbs file contains.
	-[6] Delete: Deletes the entirety of the .vbs file forever (a very long time).
	-[7] Exit: Exits the editor menu.
