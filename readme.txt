$ roslaunch rviz_camera_stream_examples_tc rviz_to_webpage.launch
$ python3 -m http.server 8001
$ rosrun image_view extract_images _sec_per_frame:=0.01 image:=/rviz1/camera2/image_compressed _image_transport:=compressed

to run multiple terminal
gnome-terminal -- ./run1.sh
