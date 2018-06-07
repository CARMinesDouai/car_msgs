# car_msgs

ROS types defined and used by various packages of the CAR team 

```console
$ rosmsg show Vertex
[car_msgs/Vertex]:
float32 x
float32 y
int32 type
int32 flags
```

```console
$ rosmsg show Vmap
[car_msgs/Vmap]:
std_msgs/Header header
  uint32 seq
  time stamp
  string frame_id
car_msgs/Vertex[] vertices
  float32 x
  float32 y
  int32 type
  int32 flags
```
# How-to install

```console
$ cd <catkin_ws>/src
$ git clone https://github.com/CARMinesDouai/car_msgs.git
$ cd ..
$ catkin_make
```
