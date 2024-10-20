# DSA_Project
What was the problem you were solving in the projects for this course?
The primary problem I tackled in this project was developing a command-line program in C++ to manage course information for a computer science advising program. The program needed to read and parse a CSV file containing course data, store this data in an efficient data structure, and allow users to interact with the data through various menu options such as displaying courses in alphanumeric order and searching for specific courses with their prerequisites. The challenge was to implement this functionality in a way that was both efficient and user-friendly.

How did you approach the problem? Consider why data structures are important to understand.
My approach to solving the problem centered around selecting and implementing the right data structures to handle the requirements efficiently. In this project, I used vectors to store course objects, since vectors allow dynamic resizing and easy sorting. Additionally, I explored other structures like hash tables and binary search trees for potential extensions, each offering unique benefits in terms of lookup speed and data organization.
Understanding data structures is crucial because they impact the program’s performance, maintainability, and scalability. For example, sorting courses using vectors is straightforward, while hash tables provide faster lookups, and binary search trees maintain sorted order. Knowing how and when to use these structures allows for better resource management, faster processing, and code that is adaptable to changes in requirements.

How did you overcome any roadblocks you encountered while going through the activities or project?
I encountered several roadblocks during the project, primarily around file handling and correctly parsing CSV data. The program initially failed to locate and read the CSV file due to issues with the working directory in Visual Studio. To resolve this, I debugged the code by printing the current working directory and tried using both relative and absolute file paths. Additionally, testing the CSV parser separately helped identify and address parsing errors, ensuring the data was correctly extracted and loaded into the chosen data structure.
I also faced challenges in handling user input and ensuring that the menu-driven interface provided clear feedback to users. Implementing error handling for incorrect inputs and file read failures helped create a more robust program.

How has your work on this project expanded your approach to designing software and developing programs?
Working on this project has expanded my approach to software design in several ways. First, it reinforced the importance of planning and testing each component separately before integrating them into the main program. 
I learned to break down the problem into smaller, manageable tasks—such as building a CSV parser, implementing data storage and retrieval, and creating a user interface—before combining them into a cohesive system.

How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
My work on this project has evolved my approach to writing code that is maintainable, readable, and adaptable. I’ve learned to use consistent naming conventions, add in-line comments where needed, and structure code to separate different functionalities into dedicated functions or classes. This modular design not only makes the program easier to understand and modify but also ensures that it can be expanded in the future.
