This is a Python project hosted in Visual Studio 2015, using "Python Tools for Visual Studio" along with Python 3.5.2 and PyQt5.

This project demonstrates an MVVM pattern (ish) in Python.

* The main window
* A "Configuration" tab page
* A "Calibration" tab page

All 3 user interfaces are created in the same way:

    self.ui = uic.loadUi(<Qt Designer .ui file>, self)
    
This approach is in contrast to running pyuic on the .ui file (which creates a python class for use in the application).

    


