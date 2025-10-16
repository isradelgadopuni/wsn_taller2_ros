## 📁 Estructura del proyecto

```bash
Reto/
├── Dockerfile
├── README.md
├── sensor_program
│   ├── package.xml
│   ├── resource/
│   │   └── sensor_program
│   ├── sensor_program/
│   │   ├── __init__.py
│   │   ├── plotter_node.py
│   │   ├── __pycache__/
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── plotter_node.cpython-312.pyc
│   │   │   ├── reader_node.cpython-312.pyc
│   │   │   └── sensor_node.cpython-312.pyc
│   │   ├── reader_node.py
│   │   └── sensor_node.py
│   ├── setup.cfg
│   ├── setup.py
│   └── test/
└── shared/
    └── sensor_plot.png
```

## 🧩 Descripción del proyecto

El archivo **`Taller_2_INTRO_ROS.zip`** contiene la estructura completa utilizada para el desarrollo del **Taller 2 de ROS**.  
Incluye el **Dockerfile** para construir la imagen del entorno, el paquete `sensor_program` con los nodos de **ROS 2** (`sensor_node`, `reader_node` y `plotter_node`), y la carpeta `shared/`, donde se almacena la figura generada por el nodo de graficado (`sensor_plot.png`).
