## What to build

Dear Nominees,

We appreciate your time and attention. We have prepared a simple challenge to assess your skills and discipline for this opportunity. The task is to develop an application that enables users to visualize the point cloud stored in a dataset file and navigate through the 3D visualization environment using the mouse.

This challenge will be open from Thursday, May 16 at 12:00 PM (Tehran) until Friday, May 17 at 00:00 AM (Tehran). Any further updates will result in disqualification from the nominees.

Good luck.

## What do you need

To complete this assignment you will require the following:

* Programming Language: C++ 14. (or higher)
* GUI Framework: Qt 5.5. (or higher) 
* Private Github account and public Git repository where you will create and manage the project.
* Build System: CMake 3.22. (or higher)
* Graphics Library: OpenGL 4. (or higher)
* Version Control: on your public repository for code submission.

Test Environment:

* CPU: Intel Core i3
* RAM: 8 GB DDR3
* GPU: NVIDIA GeForce GTX 1650 (4 GB)
* Operating System: Ubuntu 20.04

## Functionality

### Point Visualization

* Load and parse point data from a CSV file containing XYZ coordinates for each point.
* Validate the point file format with a minimum of 1000 rows and XYZ values within a range of -500 to 500.
* Render points visually in the 3D scene using OpenGL primitives (e.g., points, spheres).
* Display each point on the screen using appropriate 3D graphics primitives.
* Ensure all points are visible within the user's viewing area.

### User Interaction

* Allow users to choose a points file for visualization.
* Implement camera controls for the user to navigate freely in the 3D space (e.g., WASD keys for movement, mouse drag for rotation).
* Allow users to move in and out between the points using the mouse wheel (Point size must be fixed).

## Points File 

* CSV format with over 1000 rows.
* Each row represents a single point in 3D space (X, Y, Z coordinates).
* Valid range for coordinates: -500 to 500.

You will find a sample dataset file attached to this document.

## At the end 

Create your final release and send the address of your repository to "vahid.t@neonicx.com".

## Evaluation

Your code will be evaluated based on the following criteria:

* Correct functionality as described above.
* Code quality (readability, maintainability, adherence to coding standards, and repository management methods).
* Effective use of C++ and Qt libraries.
* Efficient handling of large point datasets.
* Overall design and user experience.
