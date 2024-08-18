# ePortfolio

---

## SNHU CS-499 Computer Science Capstone C-4<br>August, 2024

---

### Professional Self-Assessment - Overview

This ePortfolio serves as an introduction and professional self-assessment and will showcase my final project capstone, all the skills learned and strengths built from the computer science program at SNHU, as well as my own professional goals.

# Strengths
I believe this ePortfolio will help to showcase my strengths by allowing me to draw from all that I have learned in SNHU’s Computer Science program and apply it to my capstone project. Previous courses such as CS-260 Data Structures and Algorithms taught me to apply the complex algorithms needed for my enhancements. Courses such as MAT-240 Applied Statistics and IT-460 Machine Learning taught me how to analyze and visualize data. CS-360 Computer Graphics and Visualization taught me how to work with 3D environments. And courses like CS-250 Software Development Lifecycle and CS-320 Software Testing, Automation, and Quality Assurance taught me the skills needed to take what at first seemed like an impossible project plan and break it down into manageable pieces that I was able to complete in time. All of these culminated in my Final Capstone Project – a simulated 3D drone that locates, classifies, and catalogs randomly generated objects and displays their locations in a heatmap.
# Skills
It's worth noting that while all of my studies for this program were online, there was nonetheless a great need for team collaboration and communication with stakeholders. More than anything, every professor I ever had was both stakeholder as the person each project was submitted to, and team member as the person who provided code framework and understanding needed to complete projects. Each classmate was also a team member in that we constantly exchanged ideas in discussion posts and helped each when needed. Furthermore, because of the fact that I completed this program while working full-time, every co-worker and supervisor I have had in the last few years has been an ancillary team member due to the cooperation and collaboration needed for me to complete both work and academic tasks. Just as important as these soft skills are the hard skills I have learned throughout the program. The ability to understand data structures and all the ways that data can be cataloged and characterized, as well as the ability to understand the algorithms used to manipulate that data for some purpose. Software engineering skills taught me an understanding of architecture and process flow needed to design a program from the ground up, while databases and security allowed me to apply the software in a meaningful and secure way. All of these were foundational in applying my skills to my capstone project.
# Goals
My interest in pursuing computer science has always been to work with drones and autonomous systems. This has been my goal since day 1 and all my decisions and elective coursework have been informed by that goal. Furthermore, I have applications pending for graduate work that will hopefully get me closer to working with those systems, so I decided that the best measure of my readiness was to complete a capstone project that encompasses these goals. This is why the project I selected for all of my enhancements was originally from CS-360 Computer Graphics and Visualization, which is known as one of the most difficult courses in the computer science program. While this increased the level of difficulty for my final capstone project, I felt that it was important for me to show that I have some basic proficiency with simple autonomous systems.

## Journal: Self-Reflections

[Journal: Self-Introduction](CS499/CS499-M1-1_Paper.pdf "Journal: Self-Introduction")

TBD

[Journal: Career Choice](CS499/CS499-M4-1_Paper.pdf "Journal: Career Choice")

TBD

[Journal: Capstone Reflection](CS499/CS499-M7-1_Paper.pdf "Journal: Capstone Reflection")

TBD

### Original Artifact Selection

The original project was from CS-330, Computer Graphics and Visualization. In this project, we were asked to create a 3D environment based on an image we selected at the beginning of the course using OpenGL and C++. For my project, I selected a table setting of a meal.

### Original Enhancement Plan

My original planned enhancements were to remove the original 3D objects and replace them with randomly generated objects. These objects would be placed randomly and would have color or texture randomly applied. I would then create an autonomous object or drone that would travel over the environment looking for objects below, and upon finding them, determine if they were of a certain color and flag them if they were. Finally, my original enhancement plan was to create a database of flagged objects and do something with the data. While I was originally unclear on what to do with flagged object data, I eventually settled on generating a heatmap of where random objects spawned over time as this might be a common use for such data in a real-world scenario. It’s worth noting that one of the most common uses for autonomous drones is for surveillance and mapping, and this is one of the primary reasons for my enhancement plans.

### Original Code Review

[Code Review and Enhancement Plan Video](https://youtu.be/i5q9_nD8WMU)

## Enhancement 1 – Software Design and Engineering 

The basic overview of this enhancement is as follows. I removed most of the original objects but retained the surface table mesh to hold the randomly generated objects. Random location and color data was generated using the Mersenne Twister algorithm, then the one-by-one rendering of objects was replaced by a loop that generated objects based on an editable number. The size of the surface mesh would grow based on the number of generated objects. For a more detailed overview of this enhancement, please see the Narrative PDF and Enhancement Demonstration video below.

[Enhancement 1 Narrative](Enhancement-1-Narrative.joel garcia.pdf "Enhancement 1 Narrative")
[List of Enhancements 1](List-of-Enhancements-1.pdf "List of Enhancements 1")
[Enhancement 1 Demonstration Video](https://youtu.be/1YqnTj6-R4A)

## Enhancement 2 – Algorithms and Data Structures 

The basic overview of this enhancement is as follows. I modified one of the lighting objects from the original project to serve as a drone object, then created the logic for it to traverse the environment based on possible spawn points for the random objects. I implemented a “drone view” function that would provide a top-down view of the surface and used a built-in OpenGL pixel reader function to serve as a simulated camera for object detection. Finally, I created an algorithm that upon finding red-flagged objects, would output the object location to the console. For a more detailed overview of this enhancement, please see the Narrative PDF and Enhancement Demonstration video below.

[Enhancement 2 Narrative](Enhancement-2-Narrative.joel garcia.pdf)
[List of Enhancements 2](List-of-Enhancements-2.pdf)
[Enhancement 2 Demonstration Video](https://youtu.be/Z8REHoi924g)

## Enhancement 3 – Databases 

The basic overview of this enhancement is as follows. For this enhancement, I had to incorporate Python for its data visualization tools. Most of the work for this enhancement was in setting up the libraries and modules needed for C++ and Python to talk to each other, then more work in testing that Python code written in C++ was executing correctly. After all that, I set up a function to write flagged objects to a CSV file, then passed that file to Python so it could create a data frame. Finally, I used Python’s data visualization tools to create a heatmap of random object locations. For a more detailed overview of this enhancement, please see the Narrative PDF and Enhancement Demonstration video below.

[Enhancement 3 Narrative](Enhancement-3-Narrative.joel garcia.pdf)
[List of Enhancements 3](List-of-Enhancements-3.pdf)
[Enhancement 3 Demonstration Video](https://youtu.be/nTZIv0KVYhw)

### Capstone Project File

As my capstone project file size exceeds the upload limit on Github I must host a zipped file on Google Drive. To run the program, download and install Visual Studio, then download and unzip the file. Click on the sln file in the project folder, then click run program.

[Capstone Project - Google Drive](https://drive.google.com/file/d/1h6vJA_GIiURUCkxcHVs2OxETu_1P3ysO/view?usp=drive_link)

---
