# sdr-tutorial

1. Download/Install [Ubuntu 20.04](https://ubuntu.com/download/desktop/thank-you?version=20.04.2.0)<br>
2. In the Terminal, Install Dependencies (including HackRF, Jupyter Notebooks)<br>
```
sudo apt-get update
sudo apt install git cmake g++ libboost-all-dev libgmp-dev swig python3-numpy python3-mako python3-sphinx python3-lxml doxygen libfftw3-dev libsdl1.2-dev libgsl-dev libqwt-qt5-dev libqt5opengl5-dev python3-pyqt5 liblog4cpp5-dev libzmq3-dev python3-yaml python3-click python3-click-plugins python3-zmq python3-scipy python3-gi python3-gi-cairo gobject-introspection gir1.2-gtk-3.0
sudo apt-get install hackrf, gr-osmosdr
sudo apt-get install jupyter-notebook
```
3. Plug in HackRF before starting the tutorial!<br>
4. In the Terminal, Start Jupyter Notebook for lesson 1<br>
```
jupyter-notebook lesson1.ipynb
```
5. Follow the instructions in the tutorial.
