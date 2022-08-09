<div align="center>

## Code Review Video Walk-Through

<iframe width="560" height="315" src="https://www.youtube.com/embed/7a2_fYmdmN8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Artifact One - Left Right Center Dice Game

<iframe width="560" height="315" src="https://www.youtube.com/embed/6jw0K0i3e68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

| ![C++ Badge](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white) | ![Python badge](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) |
| [Link to C++ code](https://github.com/kerrsr1/CPlusPlusLRCDiceGame) | [Link to Python code](https://github.com/kerrsr1/PythonLeftRightCenterDiceGame) |

This simple dice game, called Left Right Center, was written in C++ as the final project for IT 312. I chose this as one of my artifacts because it demonstrates my skills related to software engineering and design. It takes an object-oriented programming approach by using a Dice and Player class and making use of encapsulation. I enhanced it by rewriting it in Python while also making some improvements on the modularization of it. Specifically, the main() method was simplified to include a game loop (game_loop()), magic numbers were removed by including global variables, and a class called CenterPot was created to hold the chips passed into the center pot. More notably, Python stringdoc comments were added to explain the code and easily allow other programmers to work on the code.

A computer scientist is able to use well-founded and innovative tools for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals, and my ability to write two programs in separate languages that accomplish the same task demonstrate my ability to be flexible in choosing tools to accomplish goals. It also shows a fundamental understanding of overall programming concepts on my part. Having this understanding provides value because it reduces the amount of time necessary to begin using a new language or tool. New tools and techniques come along often, and I value the importance of being familiar with these advancements and open to implementing them. Additonally, I included stringdoc comments in the Python program to further provide industry value because it makes it very clear to other programmers how it works. This not only makes the code more maintainable (even to myself in the future) but demonstrates my ability to work with a team mindset.

## Artifact 2 - Contact Service

<iframe width="560" height="315" src="https://www.youtube.com/embed/jC50iVC-uW8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

| ![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white) | 
| [Link to Java Code](https://github.com/kerrsr1/JavaContactService) |

This artifact is a Contact Service program written in Java and was the final project for CS 320 – Software Testing and Automation. The program takes a Contact, Appointment, or Task service and can either add, modify, or delete each service. The purpose of this program was to practice writing Junit tests. I chose this as one of my artifacts because it demonstrates my skills related to algorithms and data structures since the Junit tests are used to ensure the algorithms I wrote give the correct output while any errors are caught by exception handlers. The Contact, Appointment, and Task objects all need to be stored in a data structure, and I enhanced this program by switching from an arraylist data structure to a hashmap. By doing this, I could use the unique ID for each Contact, Appointment, and Task as the key for the hashmap and the corresponding class object as the value. I also enhanced it by removing the now-deprecated Java Date class and using LocalDate class.

My coursework at SNHU prepared me for designing and evaluating computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing trade-offs involved in design choices. This artifact exemplifies that outcome because a hashmap is a more appropriate solution to this problem. Unlike an arraylist, we do not have to iterate over a hashmap each time we want to find an element. It also reduced the amount of lines in my code which makes it more readable, and has potential to increase performance if a large dataset is being worked with. My coursework also helped me develop a security mindset that anticipates adversarial exploits in software architecture and design to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources. This is demonstrated within this program because the classes are private and all user input is validated prior to being accepted. Also, enhancing programs to remove deprecated classes and methods (as demonstrated with the enhancement from the now-deprecated Java Date class to LocalDate) demonstrates a security mindset as many of these are deprecated for security reasons.

The Contact Service program could be improved upon by doing more to validate user input. One solution that follows the security mindset of the principle of least privilege would be to white list valid input and throw an exception for everything else rather than checking for invalid input and throwing exceptions when those are encountered.

## Artifact 3 - Data Visualization Program

This artifact is a data visualization dashboard for animal shelter data. This was the final project for CS-340 Client/Server Development, and it demonstrates my skills in databases. MongoDB Atlas is the database and Python is the interface via the PyMongo driver. It is a full-stack application with the user-interface written in HTML and also utilizing Dash and DashLeaflet. I enhanced this artifact by creating indexes specifically for the needs of the customer. The database contains information on different kinds of animals admitted to an animal shelter in Texas and the customer is interested in certain kinds of dogs that would qualify for their rescue work. Indexing the data boosts performance because the entire collection no longer has to be iterated over each time there is a query.

One of the outcomes of the computer science program is the ability to use well-founded and innovated techniques and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry specific goal. The indexing enhancement to this application is a well-founded technique in increasing the speed of querying data and thus delivers value to the customer. Another outcome of the computer science program is to deliver professional-quality written and visual communications that are appropriately adapted to specific audiences and contexts, and this is done by delivering a UI for the animal shelter data using the Dash framework and HTML so the customer can easily see the information translated into charts, graphs, and a map. Visualizing the data in such a way makes it meaningful to the customer.

<details><summary>CLICK TO EXPAND FOR EXAMPLES OF QUERYING WITH AND WITHOUT INDEXING</summary>

<br/>
Querying the database with an example of the type of information the customer was looking for before creating indexes resulted in 10,000 documents being searched through totaling 14ms, while the same query took only 7ms after creating indexes.
<br/>

| Querying the database without indexing took 14ms | Querying the database with indexing took only 7ms |
|:--:|:--:|
| <img src="/ExecutionTimeQueryWithoutIndex.jpg" width="500"> | <img src="/ExecutionTimeQuertyDateWithIndex.jpg" width="500"> |

</details>

Additionally, this artifact was enhanced by creating Python docstrings for all Python classes and methods. I also went through the AnimalShelterVisualization.py file and changed some variable names so their contents were more obvious. Another outcome of the computer science program is to employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making, and creating docstrings make it easy for other developers to see what parameters methods take and what values they return. This helps achieve a collaborative environment because many other developers can easily use and maintain the code.

<details><summary>CLICK TO EXPAND FOR SCREENSHOTS OF DASHBOARD</summary>
<br/>
<br/>

| Dashboard example - chart of unfiltered data |
|:--:|
| <img src="/DashboardUnfilteredData.png" width="700"> |

| Dashboard example - pie graph and map of unfiltered data |
|:--:|
| <img src="/DashboardUnfilteredDataPieChartAndMap.png" width="700"> |

| Dashboard example - chart after a button is selected to query the data |
|:--:|
| <img src="/DashboardExampleQueryChart.png" width="700"> |

| Dashboard example - pie graph and map after a button is selected to query the data |
|:--:|
| <img src="/DashboardExampleQueryPieGraphAndMap.png" width="700"> |

</details>
</div>
