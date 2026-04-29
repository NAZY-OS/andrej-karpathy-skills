Please write a code in english, wit kiss code style. 

Prefer prozudurale coding, with functional coding (with functions that can get parameters !!)!

Ask me, if you want to use object orianted coding!


- write the script with shebang and with help page, (use libs or commands, that not be part of special system just if needet and write a depencie file for this command or lib sperately)
(in bash with some new tools like getopt to use parameters).

sets local variables like $1 $2 for the path and script name.

write the license and maintainer + version.

Please use smart, echo variant with colored codes that are working with a funktion,

with multiple ways to display code... with options like show spezicif error code... show real error code number .. and easy way to color output with small instructions 

fast and good

----------
E.g. Bash Logging Cookbook

This cookbook serves as a comprehensive guide for implementing a robust logging system in Bash scripts, adhering to Unix standards for error handling, logging, and script clarity.
Overview

    Logging Functionality: Create a logging function that properly handles various log levels: info, warn, error, and fatal.
    Content Handling: Capture both standard output and error output, directing appropriate messages to the console and/or a log file.
    Color-Coded Output: Use ANSI escape codes to provide colored output in the console for better visibility.
    Exit Code Management: Capture and log exit codes from executed commands to facilitate error tracking.
    Log Filtering: Implement functionality to filter logged messages using regex patterns.
---------------

Please Think Before Coding,

Use the following rules: 


    State your assumptions explicitly. If uncertain, ask.
    If multiple interpretations exist, present them - don't pick silently.
    If a simpler approach exists, say so. Push back when warranted.
    If something is unclear, stop. Name what's confusing. Ask.


No error handling for impossible scenarios.
No features beyond what was asked.


Generel, if I want to change code, use this rules please! And follow them in the feature!


(Surgical Changes)

Touch only what you must. Clean up only your own mess.

When editing existing code:

    Don't "improve" adjacent code, comments, or formatting.
    Don't refactor things that aren't broken.
    Match existing style, even if you'd do it differently.
    If you notice unrelated dead code, mention it - don't delete it.

When your changes create orphans:

    Remove imports/variables/functions that YOUR changes made unused.
    Don't remove pre-existing dead code unless asked.

The test: Every changed line should trace directly to the user's request.


