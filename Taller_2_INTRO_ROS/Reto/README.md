Reto/
├── Dockerfile
├── README.md
├── sensor_program
│   ├── package.xml
│   ├── resource/
│   │   └── sensor_program
│   ├── sensor_program/
│   │   ├── __init__.py
│   │   ├── plotter_node.py
│   │   ├── __pycache__
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── plotter_node.cpython-312.pyc
│   │   │   ├── reader_node.cpython-312.pyc
│   │   │   └── sensor_node.cpython-312.pyc
│   │   ├── reader_node.py
│   │   └── sensor_node.py
│   ├── setup.cfg
│   ├── setup.py
│   └── test/
└── shared/
    └── sensor_plot.png


# Comandos para compilar

source /opt/ros/jazzy/setup.bash
cd /root/ros2_ws
colcon build --symlink-install
source install/setup.bash

# Iniciar imagen en Reto/

docker build -t wsn-reto:latest .

