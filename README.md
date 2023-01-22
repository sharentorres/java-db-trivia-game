**QuizQuestionDAO**
This is a Java project that implements a data access object (DAO) for a QuizQuestion model. The project includes a QuizQuestionDao interface, which defines a method for retrieving a list of QuizQuestion objects for a specified quiz name. Additionally, the project includes an implementation of the QuizQuestionDao interface, called JdbcQuizQuestionDao, which uses a JDBC connection to a PostgreSQL database to retrieve the QuizQuestion objects.

The QuizQuestion model includes several fields such as quizName, questionText, numberRight, answers and correctAnswer and also some methods to check if the answer is correct and toString method to print out the question and the answers.

The QuizMaker class uses the QuizQuestionDao to retrieve a list of QuizQuestion objects for a specified quiz name and then prompts the user to answer the questions.

**Authors**


Sharen Torres - sharentorres


Eric Vazquez - v4vazquez
