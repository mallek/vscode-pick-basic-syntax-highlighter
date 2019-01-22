# README
## Pick Basic Syntax Highlighter for VS Code
This simple syntax highlighter uses Jacob Bennett's sublime TextMate pick highlighting and packages it for visual studio code

`Recommended VSCode Theme Monokai` 

Version 1.0
* Imported TextMate highlighting and packaged for VS Code
* Updated comment and bracket matching in package.json
* updated README

Version 1.1
* Added EQ, LT, GT operators
* Added bracket matching

Version 1.1.1
* Added support for ! comments
* Updated comment matching to not include * and ! used in strings
* Added support for Code Folding via !REGION and !ENDREGION (can also use *REGION and *ENDREGION)
* Added auto closing pairs for region declarations

Version 1.1.2
* Added support for SUBROUTINE and CALL SURBOUTINE
* Highlight lines where control-break logic starts
* Improve quoted string identification

## Installation
Inside VSCode from the command pallet Install Extension -> PickBasic

### Manual Install
 `git clone` this repository into your `.vscode/Extensions` folder
 If you do not have git installed you can download the zip of this repository and unzip it to the same location.

* **Windows** %USERPROFILE%\.vscode\extensions
* **Mac** ~/.vscode/extensions
* **Linux** ~/.vscode/extensions

## Credit

 Thanks for the original work done by Jacob Bennett to get this working for sublime.  This would not be possible without his work.

https://github.com/JacobBennett/sublime-pickbasic

**Enjoy!**
