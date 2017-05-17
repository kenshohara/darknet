This is a fork of [darknet](https://github.com/pjreddie/darknet), which adds a function for multiple inputs.  
To use the function, execute the following command.
```
./darknet detect-multi cfg/yolo.cfg yolo.weights inputs_list -out results/
```
```inputs_list``` is the file that includes file paths of inputs.  
```-out results/``` indicates the path of directory that stores the detection results.

---

![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).
