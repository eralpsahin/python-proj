# Python Project Template

This is a simple Python project template I have been using mostly configured for Visual Studio Code.

## Project Setup
```
git clone https://github.com/eralpsahin/python-proj.git [my-project]
cd [my-project]
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```



## VS Code Settings
`settings.json` and `launch.json` files are configured for the virtualenv path above. Project uses `Pylint`, inserts spaces instead of tabs and indentation size is 4. `launch.json` is configured to be able to debug basic Python files.

### Start Debugging
1. Open your main Python file in VS Code.
2. Set a breakpoint in any of your files by clicking on the left of the line number. Red dot should appear for the breakpoint.
3. Press <kbd>F5</kbd> or click the green play button on the top left to start debugging. A debugger bar should appear and debugging should start.
4. Use the buttons on the bar or <kbd>F10</kbd> to step over and <kbd>F11</kbd> to step into.
