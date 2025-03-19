# roboclaw_node


## 1. INSTALACIÓN DE LA LIBRERÍA. 

La librería que se usará para el controlador de los motores usando el hardware roboclaw y que sea compatible con ROS Melodic se llama: roboclaw_ros. 

Abrimos la carpeta “src” de nuestro espacio de trabajo: 

```
sudo git clone https://github.com/julianchaux/roboclaw_node.git

cd .. 

rosdep install --from-paths src --ignore-src -r -y 

catkin_make 
```

