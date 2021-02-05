# Best Practices
## Name everything meaningfully
`def a(f):` doesn't mean much, but `def getFileContents(filePath):` tells you a lot more about what the function does.

By naming your variables, functions, and files meaningfully, you save a few seconds in the future from trying to figure out "what does this function do?" when trying to debug any issues.

## Stick to one naming convention for your variables
Usually, we would adopt the programming language's convention - if you're using Python, we would follow the [naming conventions of Python](https://www.datacamp.com/community/tutorials/pep8-tutorial-python-code#naming).

Following conventions make your code easier to read, which in turn helps with the debugging process.

## Leave comments liberally
Leaving a brief description about what a function does also aids debugging. 

If the functionality implemented is simple, i.e. read a file and return its contents, then semantic naming of the function (`getFileContents`) might suffice for debugging. However, if the functionality is more complex, leaving comments for each executed step will help jog your memory of what the step does, saving you time from trying to figure out what's going on.
