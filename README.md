# line-highlighter README

This is the README for the line-highlighter extension. Given a filename, a line number and a color code, this extension will open the file and highlight the relevant line with the chosen color. The color code is a positive or negative number between 1 and 100. A negative number will show a shade of red, and a postive number a shade of green, with the number itself dictation the percenage shade of that color. For example -25 is 25% red, and 100 is 100% green.

## Features

To use the extension, open the Ctrl+Shift+P and type "Line Highlighter":

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example1.png)

If you do not have a workspace folder open, then specify an absolute file path, a line number and a color code:

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example2.png)

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example3.png)

If you have a workspace folder added, then the plugin will use this context, and allow you to specify a path relative to the workspace:

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example4.png)

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example5.png)

![](https://github.com/matthewhazlehurst/vscode-line-highlighter/raw/master/images/example6.png)

### 0.0.1

Initial release of line-highlighter