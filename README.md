# roboclaw_node


## INSTALACIÓN DE LA LIBRERÍA. 

La librería que se usará para el controlador de los motores usando el hardware roboclaw y que sea compatible con ROS Melodic se llama: roboclaw_ros. 

Abrimos la carpeta “src” de nuestro espacio de trabajo: 

```
sudo git clone https://github.com/julianchaux/roboclaw_node.git
```
Una vez descargada una copia del proyecto, nos devolvemos a la raiz de nuestro espacio de trabajo:
```
cd ..
```
Procedemos a "Instalar dependencias" del espacio de trabajo.
```
rosdep install --from-paths src --ignore-src -r -y 
```
Por último, procedemos a compilar:
```
catkin_make 
```

