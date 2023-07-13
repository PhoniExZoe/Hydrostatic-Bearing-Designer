# Hydrostaic Bearing Designer 


## About


_Hydrostaic Bearing Designer_ is an app for hydrostatic bearing parameter calculation, stiffness performance prediction, spindle error motion test, and digital twin demonstration. By providing a truly easy to use app for hydrostatic bearing design, makes _Hydrostatic Bearing Designer_ an ideal tool for students in  Course _Precision Machine Design_ learning Hydrostatic bearing, Spindle error motion, and Digital twin in a simple and convenient way.



## System Requirements


_Hydrostatic Bearing Designer_ is expected to work with MATLAB R2022a or above. 


## MATLAB® Toolbox Installation

Follow the steps below to install _Hydrostatic Bearing Designer_ as a MATLAB® toolbox

1) Download the
   [Hydrostatic Bearing Designer.mlappinstall](https://github.com/precise-simulation/featool-multiphysics/releases/latest/download/FEATool_Multiphysics.mlappinstall)
   toolbox installation file.

2) Then start MATLAB®, press the **APPS** toolbar button,
   and select the **Install App** button.

3) When prompted to choose a toolbox file to install, select the
   **Hydrostatic Bearing Designer.mlappinstall** file and press **OK**.

4) Press the **Install** button if prompted to _"Install to My Apps"_.

![](https://hackmd.io/_uploads/BJCKSpBt2.png)


Once the toolbox has been installed, an app icon will be available in
the _APPS_ toolbar to start the _Hydrostatic Bearing Designer_ GUI. (Note that MATLAB® may
not show or give any indication of the toolbox installation progress
or completion.)


## Tutorials

The app can be divided into two sections: Hydrostatic bearing design and Spindle error motion.

![](https://hackmd.io/_uploads/SJXTdaHYh.png)


### Hydrostatic bearing design

1. Input the oil specification, restrictor size, and bearing size, and the parameters related to the machine will be generated.

![](https://hackmd.io/_uploads/HJe4YpBYh.png)

2. Check bearing performance to decide wheather it meets our need.

![](https://hackmd.io/_uploads/S1dEh6SFh.png)


### Spindle error motion

1. Read the data from dual ball bar experiment.

![](https://hackmd.io/_uploads/ryd5naHK3.png)

2. Check the spindle error motion performance of the real hydrostatic spindle.

![](https://hackmd.io/_uploads/ByIxTpSYn.png)

3. Display the virtual model of the real machine spindle and calculate the suspected oil film thickness.

>**Note**
>The CAD model demonstrates how digital twin will work, however it's not synchornized with the real machine model.

![](https://hackmd.io/_uploads/Hk4U6aSY2.png)



## Built With

* [MATLAB/App Designer](https://www.mathworks.com/products/matlab/app-designer.html) - App designer that contains GUI and app behavior.

## Authors

* WeiChu (Wilson) Chen

## License

(C) Copyright 1994-2023 The MathWorks, Inc.

* This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* The writing format of this README file is based on the reference of FEATool.
* Big thanks to Cindy Hsieh for being my teammate and working together with me to organize experimental data and test software.