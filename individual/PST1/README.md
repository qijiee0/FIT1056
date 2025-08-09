Parts:

  Fragment 1 (Data Models) 
    - Creating data for two classes, student and teacher.
    - Student is assign to 2 parameters (student id, name)
    - Teacher is assign to 3 parameters (teacher id, name, speciality)

  Fragment 2 (Core Helper Functions)
    - Creates a teacher object and adds it to the database
    - Prints all student in the databases
    - Prints all teacher in the databases
    - Find student by name
    - Find teacher by name and speciality
    
  Fragment 3 (Front Desk Functions)
    - Finding student by their exact id
    - Registering new student and enrol them
    - Enroling an existing student in a course
    - High-level function to search every student and teacher

  Fragment 4 (Main Application)
    -Runs the main interactive menu for the receptionist


How to use?

1. To register a new student, enter '1'. Enter your name, and the instrument to enrol in.
2. To enrol existing student, enter '2'. Enter your ID, and the instrument you want to enrol in.
3. To look up a student or a teacher, enter '3'. Enter thier name, or specialize instrument (teacher only).
4. To look for a list of students (Admin Only), enter '4'.
5. To look for a list of teachers (Admin Only), enter '5'.
6. To exit the program press 'q'


Design

An easy to use program which allow the school to store data or students and teachers. This program also allow new or existing students to enrol in the course.


Issues

This design has a few logical errors. For instance, it allow users to input anything in their instrument erolment.
E.g. Front Desk: Successfully registered 'qi' and enrolled them in 'HI'.

