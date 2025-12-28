## ENSE 370 - Software System Design - Laboratory

# Lab 1: Java Refresher
### University of Regina
### Faculty of Engineering and Applied Science - Software Systems Engineering

This laboratory exercise is divided into parts that together introduce students to Java programming, Docker , and GitHub Classroom submission workflow.

-   **Phase 1** serves as a short verification task that ensures students
    can accept a GitHub Classroom assignment, create a simple Java program, and successfully submit it for automated grading.
-   **Phase 2** builds on this foundation and requires students to implement a complete interactive Java application.
  

## Procedure
- Open the GitHub Classroom assignment link on URCourses and accept the assignment.  A private repository will be created automatically for you.
- Clone the repository and use the docker image as a template.
- Complete the two phases

### Phase 1 - Hello World
In this task, students are required to write a simple Java program that displays a message on the screen. The goal of this task is to verify that the Java development environment is correctly installed and that students understand the basic structure of a Java program. This task also introduces the GitHub Classroom workflow that will be used for all subsequent labs.

The program must consist of a single Java class containing a `main` method. When the program is executed, it must print the message:

    Hello, ENSE 370!

exactly as shown.


### Phase 2 - Hangman game.
In this task, students are required to design and implement a complete text-based Hangman game using Java. The purpose of this task is to assess the student's ability to apply fundamental programming concepts such as loops, conditional statements, string handling, and program state management.

The program must simulate a traditional two-player Hangman game. One player enters a secret word, and the second player attempts to guess the word either letter-by-letter or by guessing the entire word.

#### Game Requirements
- Allow the user to enter a secret word.
- Use a loop to repeatedly prompt the guessing player.
- Each round print the secret word with the letters that have been guessed. With the unknown
letters use `*`.   
- If the user guesses a letter that is not part of the word, notify the user. The user is only
allowed 5 bad guesses during the game otherwise it is game over.
- If the user guesses the wrong word then it is game over.

#### Hints for Students
-   Store the secret word as a `String` and normalize case.
-   Track guessed letters using a collection.
-   Use `System.console().readPassword()` when available.
-   Use `System.out.print()` and `System.out.println()` for user
    interaction.

#### Submission
Your submission is through the GitHub classroom repository that is created for you.  Make sure you commit your code and push everything to your repository.