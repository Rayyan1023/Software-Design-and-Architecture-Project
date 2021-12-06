# Iteration 3: Addressing Quality Scenario Driver
## Step 2: Establish Iteration Goal by Selecting Drivers
In this third Iteration, the architect focuses on the security quality scenario:
Malicious attempts to access and purchase through a user account. User account has two-step verification, and the user receives confirmation emails within 10 seconds, if email confirmation is not confirmed, transaction and account access is flagged.

## Step 3: Choose one or more Elements of the System to Refine
In this Security scenario, the Database Server, Application Server, Time Server and User Workstation are the physical node elements being used.

## Step 4: Choose one or more Design Concepts that Satisfy the Selected Drivers
![image](https://user-images.githubusercontent.com/80918937/144765654-d641f782-4018-4930-9b83-2e48a041fe28.png)

## Step 5: Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces
![image](https://user-images.githubusercontent.com/80918937/144765667-d1a543ab-54b1-48a5-a167-660a9500f094.png)

## Step 6: Sketch Views and Record Design Decisions
![image](https://user-images.githubusercontent.com/80918937/144765714-076f74c6-057c-4c29-8481-3e45727afcd2.png)

Sequence Diagram displaying the error messages

## Step 7: Perform analysis of current design and review iteration goal and achievement of design purpose 
The status of the various drivers, as well as the decisions taken throughout the iteration, are summarised in the table below. The table has been cleared of drivers that were fully addressed in the previous edition.

![image](https://user-images.githubusercontent.com/80918937/144768202-3a79a46b-8aba-4782-bc48-36f3991368fa.png)

## Summary
In this report we went through all three iterations of the initial design round of ADD. We 
went through this process for our theatre booking system in order to address functionality, 
general concern, and key quality attribute scenarios. In the first iteration, drivers including
security, usability performance, and testability were selected to establish the goal of this 
iteration. Some of these drivers were then passed down to the next steps to be refined 
and design concepts were also selected to satisfy the refined drivers. In the last steps of the
iteration, an analysis was performed on goals and design purpose to see which decisions were
made during the iteration. Following this process allowed us to address architectural concerns, 
primary use cases, and quality attribute scenarios as part of architectural design. By going
through these iterations, it allowed us to better plan out the process of developing this system.
It also allowed us to clearly see which quality scenario drivers and which design concepts to
focus on and refine. UML was used as it is assumed that there would be an architect using a
CASE tool while designing the system. 


