# What Went Wrong? Troubleshooting JavaScript

Name some key differences between a Syntax Error and a Logic Error.

- syntax errors are basically beefed up typos. these usually have an error message that points to them and cause the program to not run or stop working part way through.
- logic errors are harder to fix and result from syntax being structurally sound but giving out invalid or improper results. these also don't often have error messages.

List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

- NaN or not a number error. when script was expecting a number value and recieved another type of information. used .tonumber to fix.
- MIME type error , this was from improperly ordered functions and broken links

How will this topic continue to influence your long term goals?

- by knowing where to look when things break wew can save ourselves limitless time and energy, compared to just stubbornly stabbing in the dark. like I'm prone to do.

## The JavaScript Debugger

How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

- It is a baked in tool in the broswer to help find what section of code is throwing errors and what those errors entail in a broad sense. It typically tells the user the type of error and its location within the code.

- From MDN: accessed like this;
To get to the debugger:

Firefox: SelectFirefox menu icon that has more options to customize and control Firefox.➤ Web Developer ➤ Debugger or press Ctrl + Shift + S to open the JavaScript Debugger. If the tools are already displayed, click on the Debugger tab.

Chrome: Open the Developer tools and then select the Sources tab. (Opera works the same way.)

Edge and Internet Explorer 11: Press F12 and then, Ctrl + 3, or if the tools are already displayed, click on the Debugger tab.

Safari: Open the Developer Tools and then select the Debugger tab.

Define what a breakpoint is.

- a breakpoint is where you tell the code to stop running / freeze in place. This in combination with console logging can paint a clearer picture of whats going on under the hood.

What is the call stack?

- the call stack is a section that displays what code was run to get to the current line or breakpoint.
