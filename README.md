Eslint Configuration Editor
=============================

Overview
--------
This is a standalone tool developed using JavaFX in java. It can be used for editing .eslintrc.json configuration file.
This tool provides following functionality.

- Support for setting all rules available in eslint to error, warning or off flag. 
- Search particular rule by it's name
- Documentation on double click 
- Generate project level configuration file
- Import existing rule file and create another eslint configuration file on top of existing file


License
-------
Apache License, Version 2.0


Dependencies
-------
Java : version >= 1.8.x <br />
Note : Make sure java is available in the path


Usage
------
- Clone the repo. and download jar file from here : [EslintEditor.jar]      (https://github.com/EslintSublimePlugin/EslintConfigEditor/blob/master/out/artifacts/EslintEditor_jar/EslintEditor.jar?raw=true)
- Copy folder named JSON from cloned repo. and place it in the same direcory as jar file.<br />
- Open the terminal, navigate to jar directory<br />
- Execute the jar file and give eslint configuration file path as an argument<br />

```Java
    Java -jar EslintEditor.jar PATH_TO_ESLINTRC.JSON

```

