# A Few Setbacks; And Even More Successes
# 1/17/2022
- We made some more progress on our drivetrain.
![image12](https://user-images.githubusercontent.com/25676667/150695309-919a6705-3e6f-4137-b8cb-e59b764be09b.jpg)
**Until...**

- Found a critical flaw and reassembled the entire drivetrain (twice)
We realized that our drivetrain was backwards and flipped.
![image12Annotated](https://user-images.githubusercontent.com/25676667/150695590-13e8cf77-88ac-44f6-bad2-b61025a309ed.jpg)
- The gearboxes were upside down. See how the triangular piece (circled in red) is facing up? This is consistent, so we could actually just flip the robot over, but then the ends of the chassis woulb be inverte. In that event, we would lose valuable fastening positions.
- We also noticed that the screen left inside rail (see yellow circle) is turned wrong.
We dertermined that it was best to fix these issues before we got too far in our construction.
So, we began doing just that.
![image20](https://user-images.githubusercontent.com/25676667/150695618-4ad9055b-3af1-4856-a5a7-6eb2dce3cdbe.jpg)
![image19](https://user-images.githubusercontent.com/25676667/150695616-71ef6ddd-3643-4185-a27f-9ca079adf213.jpg)

# 1/20-22/22
- Restocked our food bin thanks to gracious donations from members' parents
![image16](https://user-images.githubusercontent.com/25676667/150695874-4b9cef2b-fd84-4a7c-9da6-3d23b132574f.jpg)
- Got all the wheels on our drivetrain
![image3](https://user-images.githubusercontent.com/25676667/150695669-2e59659f-2d52-4f60-92f3-51b0781361c7.jpg)
- Performed reverse brain surgery on the robot
![image21](https://user-images.githubusercontent.com/25676667/150695748-9f4395bb-823b-4e70-9d06-0c951724ef4a.jpg)
- Had some issues getting the firmware set with the Falcons. Once we got them updated, we worked to ensure that each motor was going in the correct direction before creating a `Drivetrain()` object.
- Used `AutonomousPeriodic()` to set each motor individually asking it to drive in the direction we thought was forward, then we used `WPI_TalonFX.setINverted()` to attempt to get them driving in the correct direction (and definitely the same as one another.
- The left side `MotorControllerGroup()` is still driving backwards, so currently, our robot drives, but with only one motor on the left side. That is our #1 Priority for next meeting.
- This was an incredible opportunity for some members to learn more about Java programming.
![20220122_120609](https://user-images.githubusercontent.com/25676667/150696828-3e6e123a-1f61-4406-a50c-c6b0dde25c1f.jpg)

- Created a new avatar to match our logo! <img src= "https://user-images.githubusercontent.com/25676667/150696418-d0f134dc-667b-445a-affa-5c4995fe7c07.png" alt="pixel logo" height= "40" width="40"/>

![KLogoFinal](https://user-images.githubusercontent.com/25676667/150696575-2fac237f-9242-442a-b729-2d1c8cff3dad.png)

- Conintued making a bit of progress on our climber.
![20220121_164553](https://user-images.githubusercontent.com/25676667/150697095-aebf3b58-12a7-4844-9de1-2debd762f8f2.jpg)

- There was a bit of oversight in the purchase of our climbing mechanisms. We bought the 2 stage Climber in a box and determined that we will not use the second stage at the moment. 
- The Max height while in the hangar is only going to be six inches than the climber's 1 stage max height, so we needed to cut down our 2 inch standoffs. In order to do this small cut safely, we got our new bandsaw -- **Courtesy of Donors's Choose, FIRST, and Disiney**-- operational.
- We purchased a specific-for metal- blade, but it was too wide, so, as a result, a few of us really know the ins and outs of changing bandsaw blades on a WEN bandsaw now.
- Began coming up with next steps for our strategy design as well. We are most interested in climbing and defense, As such, we are going to complete a basic climber and then begin testing designs to make it to the high and traversal rungs.
- Our favorite designs at the moment are similar to the design from [@Maxwelfire](https://www.chiefdelphi.com/t/thoughts-on-simple-multi-stage-climbs/399427/25?u=mr.r_2). Here is the Gif they made. We apologize if reposting is in bad taste. If it is, please let us know, and we will take it down.

<video src="https://user-images.githubusercontent.com/25676667/150697390-a788434d-a822-4b5e-8fb3-3eb0df0cf08a.mp4" controls="controls" style="max-width: 730px;"></video>



- We also have a trolley idea that we are tossing around.
