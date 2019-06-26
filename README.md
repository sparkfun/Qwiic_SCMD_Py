# Qwiic_SCMD_Py
Python module for the qwiic serial control motor driver

This python package is a port of the existing [SparkFun Serial Controlled Motor Driver Arduino Library](https://github.com/sparkfun/SparkFun_Serial_Controlled_Motor_Driver_Arduino_Library)

## Installation
To install, make sure the setuptools package is installed on the system.

Direct installation at the command line:
```
  $ python setup.py install
```

To build a package for use with pip:
```
  $ python setup.py sdist
 ```
A package file is built and placed in a subdirectory called dist. This package file can be installed using pip.
```
  cd dist
  pip install sparkfun_qwiic_scmd-0.8.6.tar.gz
