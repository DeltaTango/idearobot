# Robot framework testing environment setup

This sample boilerplate project is based on Robot Framework Web demo https://github.com/robotframework/WebDemo

## Requirements for system:

* Python - version 3.6 should be OK, 2.7 fully supported

* PIP installed:
```console
$ sudo apt install python3-pip    
```

* Robot framework:
```console
$ python3 -m pip install robotframework
$ python3 -m pip install robotframework-seleniumlibrary
$ robot –version # Should show something reasonable
```
## In IDEA:

* Install plugins:
  * "Python Community Edition"
  * "IntelliBot @SeleniumLibrary Patched"
     * Check configuration at https://github.com/millennialmedia/intellibot/wiki/Python-Interpreter
  * "Run Robot framework file"
     * Check configuration at Launcher Configuration Window


### "Run Robot framework file" configuration

Check configuration at Launcher Configuration Window and add new launcher "Robot Framework"

PATH: venv/bin  
Binary: robot  
Options: --outputdir reports

### Content of venv

in bin geckodriver is located.

Read more at https://github.com/mozilla/geckodriver
