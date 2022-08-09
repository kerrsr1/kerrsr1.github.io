## Code Review Video Walk-Through

<iframe width="560" height="315" src="https://www.youtube.com/embed/7a2_fYmdmN8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Artifact One
## Left Right Center Dice Game

<iframe width="560" height="315" src="https://www.youtube.com/embed/6jw0K0i3e68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

| ![C++ Badge](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white) | ![Python badge](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) |
| [Link to C++ code](https://github.com/kerrsr1/CPlusPlusLRCDiceGame) | [Link to Python code](https://github.com/kerrsr1/PythonLeftRightCenterDiceGame) |

This simple dice game, called Left Right Center, was written in C++ as the final project for IT 312. I chose this as one of my artifacts because it demonstrates my skills related to software engineering and design. It takes an object-oriented programming approach by using a Dice and Player class and making use of encapsulation. I enhanced it by rewriting it in Python while also making some improvements on the modularization of it. Specifically, the main() method was simplified to include a game loop (game_loop()), magic numbers were removed by including global variables, and a class called CenterPot was created to hold the chips passed into the center pot. More notably, Python stringdoc comments were added to explain the code and easily allow other programmers to work on the code.

A computer scientist is able to use well-founded and innovative tools for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals, and my ability to write two programs in separate languages that accomplish the same task demonstrate my ability to be flexible in choosing tools to accomplish goals. It also shows a fundamental understanding of overall programming concepts on my part. Having this understanding provides value because it reduces the amount of time necessary to begin using a new language or tool. New tools and techniques come along often, and I value the importance of being familiar with these advancements and open to implementing them. Additonally, I included stringdoc comments in the Python program to further provide industry value because it makes it very clear to other programmers how it works. This not only makes the code more maintainable (even to myself in the future) but demonstrates my ability to work with a team mindset.

# Artifact #2
## Contact Service

<iframe width="560" height="315" src="https://www.youtube.com/embed/jC50iVC-uW8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

| ![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white) | 
| [Link to Java Code](https://github.com/kerrsr1/JavaContactService) |

This artifact is a Contact Service program written in Java and was the final project for CS 320 – Software Testing and Automation. The program takes a Contact, Appointment, or Task service and can either add, modify, or delete each service. The purpose of this program was to practice writing Junit tests. I chose this as one of my artifacts because it demonstrates my skills related to algorithms and data structures since the Junit tests are used to ensure the algorithms I wrote give the correct output while any errors are caught by exception handlers. The Contact, Appointment, and Task objects all need to be stored in a data structure, and I enhanced this program by switching from an arraylist data structure to a hashmap. By doing this, I could use the unique ID for each Contact, Appointment, and Task as the key for the hashmap and the corresponding class object as the value. I also enhanced it by removing the now-deprecated Java Date class and using LocalDate class.

My coursework at SNHU prepared me for designing and evaluating computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing trade-offs involved in design choices. This artifact exemplifies that outcome because a hashmap is a more appropriate solution to this problem. Unlike an arraylist, we do not have to iterate over a hashmap each time we want to find an element. It also reduced the amount of lines in my code which makes it more readable, and has potential to increase performance if a large dataset is being worked with. My coursework also helped me develop a security mindset that anticipates adversarial exploits in software architecture and design to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources. This is demonstrated within this program because the classes are private and all user input is validated prior to being accepted. Also, enhancing programs to remove deprecated classes and methods (as demonstrated with the enhancement from the now-deprecated Java Date class to LocalDate) demonstrates a security mindset as many of these are deprecated for security reasons.

The Contact Service program could be improved upon by doing more to validate user input. One solution that follows the security mindset of the principle of least privilege would be to white list valid input and throw an exception for everything else rather than checking for invalid input and throwing exceptions when those are encountered.


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kerrsr1/kerrsr1.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kerrsr1/kerrsr1.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
