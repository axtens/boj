boj
===

Bruce's Own Joblog

BOJ prompts for whatever the user has been doing up to the point of its appearance. 
The user selects the "department" (or accepts the default) that the log applies to (in the author's case, either
HOME, WORK or OTHER) and enters text into an HtmlEdit control. The date, the "department" 
and the entered text are appended to an HTML log file.
 
The jar, the log and an ini defining the "departments" are stored together. In the 
author's case, these files are stored in %USERPROFILE%\.joblog

In the ini file, the default "department" is prefixed with an asterisk.

The program is executed according to a schedule defined in Task Scheduler. In this author's 
case, this is once every 15 minutes. 

The window is undecorated so as to force the user to hit "Save" or "Cancel".

BOJ renders in B4J an app written previously in VB6. 

License: MIT License.
