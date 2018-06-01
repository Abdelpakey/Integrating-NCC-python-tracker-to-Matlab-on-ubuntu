# Integrating-NCC-python-tracker-to-Matlab-on-ubuntu
+++++++++++++++++++++++++++++++++++++++++++++++++++++++

Install Ubuntu 16 or 18 
Install Matlab 

If you installed as root (which you should have) then your fine. If not uninstall and install as root.

Ok! Lets get to it!

    cd to into where you installed MATLAB For me it was the default that was given but you may have wanted to install it in a different location.

    Default install location: /usr/local/MATLAB/R(year)(a or b)

    Now you can list everything that is in that directory by typing ls into the terminal window.

    Now type cd once more by typing cd bin (this is where the activation client is stored)

    Type in the terminal

    sudo ./activate_matlab.sh



install Gcc4.9 and G++4.9

    sudo add-apt-repository ppa:ubuntu-toolchain-r/test
    sudo apt-get update
    sudo apt-get install gcc-4.9 g++-4.9
    sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 60 --slave /usr/bin/g++ g++ /usr/bin  /g++-4.9

    sudo apt-get install gcc-4.8 g++-4.8
    sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 60 --slave /usr/bin/g++ g++ /usr/bin/g++-4.8

    sudo update-alternatives --config gcc


    download anaconda https://www.anaconda.com/download/#linux
    Setup anaconda sha256sum /path/filename
    In matlab befor generate python command set_global_variable('python', '/home/mohamed/anaconda3/bin/python2.7');
    
 install opencv on python2.7 
 
 pip install opencv-python
    
     
