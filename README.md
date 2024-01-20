# Editreadme

# Python Package for Bayesian Calibration from Telemac Simulations

***
>***Purpose***: Tell the Telemac, bla bla bla bla 
> ***Motivation***: bla bla bla bla 
> ***Goal***: Create a package which is able to run the multiple simulation of Telemac and along with the Bayesian calibration 

GitHub Repository URL
```
https://github.com
```

## Requirements
* To use this code, make sure you have the following requirements installed:

### Virtual Machine
The Virtual Machine configuration fir this project is as follows:
* Operationg System: Linux Mint Xfce 21.2
* Storage: SATA 64 GB
* Software
  * QGIS
  * Telemac V8p4r0 (MPI distribution and Metis 5.1.0)
  * Python 3
  * PyCharm Community Edition
* Python Library
  * matplotlib
  * mpi4py
  * numpy
  * openpyxl
  * pandas
  * scikit-learn

## Usage Instructions
Install Required Software:
    * Installing an apps using apt:
      ```
      sudo apt install app_name
      ```
  * Uninstalling an app using apt
    ```
    sudo apt remove app_name
    ```
    
* Accessing Course Materials:
* Environment Scripts:
* Calling Shell Files
* Running Telemac
  ```
  python (filename)
  ```

* Mesh file (`casename.slf`)
* Boundary conditions file (`casename.cli`)
* Output file (`case output.slf`)


## Code Diagram
![UML]
### Brief Overview of the Components

## Documentation of Functions and Classes

Documentation of Functions and Classes
Provide documentation for all functions and custom classes in the code. Include details about the actions performed, input arguments, output, and data types.

function_name(arg1, arg2) -> return_type
Description of the function or method.

arg1 (type): Description of the first argument.
arg2 (type): Description of the second argument.
Returns: Description of the return value and its type.
ClassName
Description of the custom class.

Methods
method_name(arg1, arg2) -> return_type
Description of the method.

arg1 (type): Description of the first argument.
arg2 (type): Description of the second argument.
Returns: Description of the return value and its type.
<!-- Repeat for other functions and classes -->
Contributing
If you'd like to contribute to the project, please follow the guidelines in CONTRIBUTING.md.

#### Main.py

#### log.py
The file starts the logger and set up its StreamHandler. Log Configurations are also set up. 

#### config.py
```
# global python libraries used

import mumpy as np
import pandas as pd
 
# necessary basic python libraries

 import logging
 import os
 import math
```

# Author 
* Andres
* Abhishek 

# References



# License
This project is licensed under the GNU - see the LICENSE.md file for details.
