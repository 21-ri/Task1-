Resolve Course Dependencies with Python

This Python script provides a simple way to resolve course dependencies using the Depth-First Search (DFS) algorithm.

Features

Checks for circular dependencies.
Supports multiple prerequisites for a course.
Installation

No installation is required as the script has no external dependencies.

Usage

Import the resolve_dependencies function.
Define the prerequisites dictionary with courses and their dependencies.
Define the course_list dictionary with all the courses, including the prerequisites.
Call the resolve_dependencies function with the course_list as an argument.
Disclaimer

This project is for educational purposes only and should not be used in any production environment.

Testing

To test the script, anyone can modify the prerequisites and course_list dictionaries and run the script multiple times to ensure that the dependencies are being resolved correctly.

Additionally, anyone can add a sample prerequisites and course_list dictionaries with circular dependencies to test the functionality of the script in such scenarios.
 
Acknowledgements

The script is based on the DFS algorithm for course dependency resolution.