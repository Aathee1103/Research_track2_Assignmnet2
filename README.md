# Second Assignment of the Research Track 2 course (Robotics_5051520 Engineering Unige)

The package contains the nodes and the simulation environment for controlling a mobile robot in the Gazebo simulation environment and jupyter notebook to have a graphical userinterface and control the robot through it.
- To launch the gazebo node, please run:
```
roslaunch rt2_assignment1 sim.launch
```
- To launch the jupyter notebook run the commands below:
``` jupyter notebook --allow-root ``` and open the notebook named as jupyter_5051520.ipynb.

## Sphinx documentation:
Sphinx is a tool that makes it easy to create intelligent and beautiful documentation.it was originally created for the Python documentation, and it has excellent facilities for the documentation of software projects in a range of languages and it can be used to document C++ codes with the help of doxygen and we no need to change anything for the C++ files that has been done for the doxygen documentation.the sphinx will use the same codes from doxygen for C++.But for Python file we have to modify the documentation.index.rst and cnf.py files also need to be modified after the command ```sphinx-quickstart```.And finally run the command ```makehtml``` to document all the files. 
### Outputs od sphinx documentation:
- ***go_to_point.py***:
![go_to_sph](https://user-images.githubusercontent.com/80621864/154961947-1a0c094d-fb1e-4036-8d7f-e4de53f9b91a.jpg)


- ***user_interface.py***:
![usr_sphinx](https://user-images.githubusercontent.com/80621864/154962023-223b1c3c-16a2-4ec6-94ce-00643298bdf8.jpg)


- ***state_machine.cpp***:
![st_sph](https://user-images.githubusercontent.com/80621864/154962098-8eb3d72f-d63a-4e88-b041-dea16760d53e.jpg)


- ***poistion_service.cpp***:
![pos_sph](https://user-images.githubusercontent.com/80621864/154962173-7d3cff22-44ae-49f7-b9c5-cf2fa817fe90.jpg)
