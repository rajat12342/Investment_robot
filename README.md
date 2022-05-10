# Investment_robot
This project was made using UiPath. The robot fetches the necessary data required to do a discounted cash flow analysis from the internet and fills it in the excel sheet where the analysis is done. 
In order to run, Uipath needs to be installed locally. Open project.json in uipath and run it using the application. Alternatively, writing a .bat file to execute the .nupkg project bundle is also an option. The path to the excel file also needs to be updated to the path where the file is stored locally.
The .bat file will contain the following(all in one line): 

C:\Users\username_goes_here\AppData\Local\Programs\UiPath\Studio\UiRobot.exe -file "C:\Users\username_goes_here\Desktop\Investment_robot_project\Investmentproject\Investmentproject.1.0.7.nupkg"

A demo of the robot in action can be found here: https://streamable.com/vvb3bs

