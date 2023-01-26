### Introduction

1. The data structure course is the most essential and critical course for computing-related majors because it is one of the fundamental courses that needs to be taken by students.
2. However, learning data structures and understanding the performance effects of  distinct data structures on the same problem can be challenging. Mostly, students  change their majors if they are not successful in this course in their first attempt.
3. Our approach combines real-world environment with virtualization by using Augmented Reality (AR), and then we observe the effects of AR by comparing AR-based  visualization approach with the pure lecturing and lecturing with animations. 
4. AR is defined in as “3D virtual objects are integrated into a 3D real environment in real-time”. The objective is to develop AR visualization contents for data structures and analyse the effects of AR-based visualization and animation techniques for teaching data structures course
5. I've developed an AR application that visualizes some operations of data structures such as Array list, Linked list, and Stack. In order to develop an AR application, we have followed AR requirements such as integration of virtual objects or environment into the real environment; and real-time interactivity of the virtual and real objects at the same time
--------
### User Interface 
<img width="405" alt="image" src="https://user-images.githubusercontent.com/77117188/214892682-7b8a21b9-2a57-4870-8fe3-0c78ca907ab0.png">

>  Shows the main menu of the developed AR application. The main menu and sub-menus are kept as simple as possible to decrease user interface complexity. Users can 
select one of the data structures from the main menu to experience the concepts

--------
### Linked List 

<img width="390" alt="image" src="https://user-images.githubusercontent.com/77117188/214893849-b9f89a55-51b9-44bb-af5c-9f0f7a0d356b.png">
<img width="390" alt="image" src="https://user-images.githubusercontent.com/77117188/214894000-b1239aa0-a09e-4804-83a1-5b51ce937862.png">

>  Represents the dragging of chain links next to each other for appending and the C code for addition/appending of linked list is being shown in a scroll view at the right side of the screen

<img width="414" alt="image" src="https://user-images.githubusercontent.com/77117188/214894316-fc2c5e0d-96b2-4f24-a295-d80154316495.png">

>  Shows the addition of chain link between the 2 other chain links, the chain links shift one position right clearing up a position for the chain link to be added in between
 
>  A similar operation can be performed for removal of the linked list too

---------
### Stack

<img width="178" alt="image" src="https://user-images.githubusercontent.com/77117188/214895952-3684eace-33d5-46fe-8fc2-a1ec76461943.png">
<img width="173" alt="image" src="https://user-images.githubusercontent.com/77117188/214896064-41bce537-c57e-4433-945d-63b50d5af670.png">


>  The stack module is being simulated using a shoe rack with shoes inside. On the press of add button the shoes are being added to the rack one by one from bottom to the top.

<img width="156" alt="image" src="https://user-images.githubusercontent.com/77117188/214896234-0fd7fcfb-4ccb-40f1-9d3d-aa8ca86a5c29.png">

>  The stack module is simulating the operation of removing objects from the stack, the shoes are removed one by one from the top to the bottom in the form of “Last 
in First out".

----------
### Queue

<img width="365" alt="image" src="https://user-images.githubusercontent.com/77117188/214896882-e5439751-8943-4a9b-8a8d-d5aaad0ec446.png">

>  shows the 3d model of the rack which is representing the Queue data structure, the C code for getting the front of the queue is shown in a scroll view at the right side of the screen

<img width="378" alt="image" src="https://user-images.githubusercontent.com/77117188/214896952-599f58ca-365e-46c1-88fc-abadad682e15.png">

>  shows the enqueue operation where shoes are being added to the rack from right to left, a pointer/arrow points at the most recently added node. The C code for enqueue operation is shown at the right side of the screen

<img width="370" alt="image" src="https://user-images.githubusercontent.com/77117188/214897040-4cc86551-6efd-4abe-950e-5936824bc49c.png">

>  shows the dequeue operation where shoes are being removed from the right side/front of the queue, when shoe is removed the rest of the shoes in the queue shift  one position forward to occupy the empty spaces in the queue following the “First in First out” pattern.

