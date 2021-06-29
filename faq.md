Frequently asked questions and issues
Issues
The wrong character set being used
I see this issue a lot, you muse set the character set to muli-byte. If you do not you will see an error like this.
Go into the project properties and follow change the character set to multi-byte.
Fix for VS Community IDE 2017
Fix for VS Community IDE 2019

Cannot open source file "pch.h" or "stafdx.h"
This issue comes from not creating an empty project file. This is very easy to fix, and the error will look like this.
First delete the line that says #include "pch.h" or #include "stafdx.h"
Go into the project properties and turn off using pre-compiled headers.
