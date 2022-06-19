# far-planner-with-yolo
# FAR Planner version with yolo to detect object<br>
![image](https://github.com/Leeable/far-planner-with-yolo/blob/Noetic/2022-06-19%20183632.gif)<br>

## Note that the opencv version should higher than 3.3 <br>
download source from https://opencv.org/ <br>
> cd opencv-4.5.4
> mkdir build & cd build
> cd opencv-4.5.4
> cmake -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_INSTALL_PREFIX=/usr/local -DWITH_TBB=ON -DBUILD_NEW_PYTHON_SUPPORT=ON -DWITH_V4L=ON -DINSTALL_C_EXAMPLES=ON -DINSTALL_PYTHON_EXAMPLES=ON -DBUILD_EXAMPLES=ON -DWITH_QT=ON -DWITH_GTK=ON -DWITH_OPENGL=ON ..
> make
> sudo make install


 
make -j12
sudo make install
you need to build newer opencv from source<br>


The original far_planner is here, please check the url below <br>
https://github.com/MichaelFYang/far_planner
