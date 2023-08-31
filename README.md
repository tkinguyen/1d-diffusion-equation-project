# 1d-diffusion-equation-project

Hello, welcome to my final project about 1D Diffusion Equation!

Here's how to work the program:
1. Open terminal
2. Arrive to the directory my folder for this project is in (example: cd tnguyen_final)
3. Type into terminal /bin/bash jobsfile
4. The program will ask for some parameters. Plesae follow the instructions displayed.
5. Afterwards, jobsfile will run through my project.


What is the order of my project?
1. Run jobsfile
2. Run the python script that will make plots for the analytical solutions for steady and unsteady states of heat. It will produce .pngs and .dat files.
3. Afterwards, it will run through the relaxation method script and display a grid of what the steady state numerically looks like in the terminal. It will produce a .txt file from relaxation.
4. From the relaxation method, a 3D scatter graph will show to display how the temperature is like in 3D. 
* Even though it is 1D in this situation, I assumed y would go to infinity throughout we can still observe the results when I use the y-axis the same as x-axis.
5. It will then run the numerical script for the unsteady states and produce .dat files.
6. Once that is done, my program will use the python script that compares analytical and numerical. 4 plots will be shown with the comparison and will be saved.
7. All done! I made the plots saved as .pngs for later use.

What is the example folder for?
I had plotted the analytical steady state solution going over a bigger time and with more plots. I made it into a .gif and if you click on it, it will display the overall decay of my analytical solution because it goes to infinity, it will eventually go to zero.
In this .gif, the params I used was the temperature at the left = 0 (always in this porject), temperature at the right = 100, and L to be 10m.
