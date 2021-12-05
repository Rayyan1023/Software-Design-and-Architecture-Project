# Iteration 2: Identifying Structures to Support Primary Functionality
## Step 2: Establish Iteration Goal by Selecting Drivers
In this second iteration, the architect considers the system's primary use cases:
- UC-1: Website
- UC-2: Account System
- UC-5: Payment Method

## Step 3: Choose One or More Elements of the System to Refine
The elements we will be focusing on to refine during this iteration are included in different layers of the architecture. So for our system we will be focusing on the business logic layer with the user side and server side. In particular we will be refeinning the security modules as it pertains to the payment module and transaction module. Our main goal for our system is to ensure security for all our users. We will need to make sure our system is secure because the users deal with transactions involving their money, so we need to address any technical issues. There needs to be a safe exchange from the users credit card provider and storings the money in our database.  Refining the security’s functionality will help our system not have any leaks, hackers, and will help our system stay up and running.

## Step 4: Choose One or More Design Concepts That Satisfy the Selected Drivers
![image](https://user-images.githubusercontent.com/80918937/144764980-63e1f80b-dc6d-438b-9dc3-83f57641b91e.png)

## Step 5: Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces 
![image](https://user-images.githubusercontent.com/80918937/144765000-9ce8d7c1-16b4-4da2-9e5a-c55177ff0a5d.png)

## Step 6: Sketch Views and Record Design Decisions
![image](https://user-images.githubusercontent.com/80918937/144765095-0f0a9086-d6f3-4086-915a-1525590e3cec.png)

Modules that support the primary use cases (Key: UML)

### UC-2: Account System:
![image](https://user-images.githubusercontent.com/80918937/144765219-3038980c-3cea-4636-aa03-b7d49deed62a.png)

Sequence diagram for UC-2 (Key: UML)

### UC-5: Payment Method:
![image](https://user-images.githubusercontent.com/80918937/144765404-3c0b7126-67a8-4b5e-a67d-54d6a8103b80.png)

Sequence diagram for UC-5 (Key: UML)

## Step 7: Perform analysis of current design and review iteration goal and achievement of design purpose 
The selections taken in this iteration offered a basic grasp of how the system's functionality is supported. The architect defined the modules connected with the core use cases, while the team members identified the modules linked with the remaining functionality.

![image](https://user-images.githubusercontent.com/80918937/144767755-fe6261f0-a6c2-42c6-8110-3ebda9cc2d8b.png)




