FROM osrf/ros:jazzy-desktop
SHELL ["/bin/bash","-lc"]

# Herramientas + matplotlib + nano
RUN apt-get update && apt-get install -y \
    python3-pip \
    python3-matplotlib \
    python3-colcon-common-extensions \
    python3-colcon-ros \
    nano \
 && rm -rf /var/lib/apt/lists/*

WORKDIR /root/ros2_ws
RUN mkdir -p src
COPY ./sensor_program /root/ros2_ws/src/sensor_program

# Usa el entrypoint oficial de la imagen (viene en la base)
ENTRYPOINT ["/ros_entrypoint.sh"]
CMD ["bash"]

