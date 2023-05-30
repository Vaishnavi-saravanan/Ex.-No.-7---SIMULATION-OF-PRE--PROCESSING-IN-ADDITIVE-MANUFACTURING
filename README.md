# Ex. No. 7 - SIMULATION OF PRE PROCESSING IN ADDITIVE MANUFACTURING
### DATE: 
## AIM:
### To simulate the Pre Processing for 3D printing.

## REQUIREMENTS:
### System - Windows 7 or higher, 1 GB RAM.

## PROCEDURE:
### Pre-processing encompasses the steps between design and printing. Process of 3D printing starts with designing in CAD. Then printer software slices 3D CAD file into layers. For each slice, the software converts the data into machine code that determines tool paths for the machine to follow. The various steps in pre-processing from design to printing are as follows:

### 1)	CAD File
### 2)	Conversion to STL a. Orientation b. Support Structure c. Slicing d. Path Planning

### 1. CAD File
### Every manufacturing process starts with the process of designing and as in any type of manufacturing, there are certain limitations to the materials and manufacturing processes that dictate how the product should be designed, 3D printing is no different. In 3d printing, characteristics of hardware, software, temperature, filament and many other factors play an important role in how a digital model translates into a printed object. Some of them are designed with a strong base, grain direction, overhung, wall thickness, round corners and tolerances.

### 2. Conversion to STL
### In order to check the interface of the object and make it reliable to 3d printers, conversion to STL file is required. It also facilitates other features like quick error check, bridging the gap between CAD platforms, exhibition purposes and 3D digitizer extension.

### a. Orientation:
### Orientation plays a vital role in the final product of 3d printing as it affects the part accuracy, manufacturing time, strength and surface finish. There are various orientations by which we can print the object such as vertically upward, vertically downward and in horizontal plane.

### b. Support Structure:
### Support structures are required where the objects are unable to get printed directly. Support structures help to guarantee the printability of a section during the 3D printing measure and also it can assist with forestalling part twisting, secure a section to the printing bed and guarantee that parts are joined to the fundamental body of the printed part.

### c. Slicing:
### The motive behind slicing a 3D model is to transform the model into guidelines for the 3D printer. To play out this errand, the slicing software isolates the item into numerous layers. It's classified "slicing" since it "slices" the 3D model to make numerous layers. After the layers have been made, the slicing software applies different qualities to every one of them.

### d. Path Planning:
### Path planning helps to improve the printed surface quality, shape accuracy and infill distribution quality. There are various ways for path planning which can be used to print the objects which may affect the following factors in objects like raster path, grid path, spiral path and zigzag path.

![image](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/baef8515-67d7-4c96-accc-4ee88035c9e7)

### ●	All the processes related to pre-processing will be shown on the screen.
### ●	Select CAD file preparation from the visible list.
### ●	When the first process is selected then it will open in the blank space in the left side of the screen.
### ●	Select the options of process of pre-processing in the sequence in which they are shown.
### ●	If the user follows an incorrect sequence then a pop-up will appear on the screen showing the name of the process to be selected.

## OUTPUT:
CAD file preparation
The first step in rapid prototyping is to prepare a computer-aided design (CAD) model of the object to be fabricated using layer based manufacturing processes.Once this process complete,the model is either converted or exported as STL file.
![image](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/611b98dd-2f98-4318-b85e-90c15e3817bd)

Conversion to STL
STL file is also known standard tesstellation language in which model is represented as triangular patterns.It covers only the information about surface structure of the model not the internal features.on CAD software itself ,it process and convert CAD file into STL file.
![image](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/0c3df073-ca6c-4419-b39e-f2f287dd7e03)

Orientation
In slicer software STL file is loaded .The object orientation is need to be check.without proper orientation ,time and excess material can be consumed.A proper orientation increase strength of the model .The model should be printed along the direction of force that going to withstand.
![image](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/22ab7088-3c04-4ef1-b109-093fe231be74)

Support structure
As we see before proper orientation need lesser support material .But at some places there might be need of support material which supports overhanging parts(ie.,angle above 45).However they need to be removed after printing.
![image](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/01de0f5e-9e6b-4a62-8fbb-982bac75afe4)

Slicing
slicing is converting digital 3D models into printing instructions for a given 3D printer to build an object. In addition to the model itself, the instructions contain user-entered 3D printing parameters, such as layer height, speed, and support structure settings.
![image](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/97d9b592-a4f4-4154-b378-6876518d8183)

Path planning
The infill pattern determines the arrangement of the internal structure within the 3D printed object. Common infill patterns include rectilinear, honeycomb, grid, and concentric. Each pattern has its own characteristics in terms of strength, material usage, print time, and surface finish. The choice of infill pattern depends on the specific requirements of the printed object

![Screenshot 2023-05-30 172734](https://github.com/Vaishnavi-saravanan/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118541897/5888b587-5294-4493-9c00-1b00b6c1c07f)

### Name:VAISHNAVI S
### Register Number:212222230165

## Result: 
### Thus the simulation on the Preprocessing in additive manufacturing is completed.
