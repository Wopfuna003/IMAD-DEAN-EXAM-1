# IMAD-DEAN-EXAM-1
1. Project Overview
This project is a Book Review Application developed using Kotlin in Android Studio. The app allows users to input book titles, authors, ratings (1-5), and comments. It displays a list of added books and calculates the average rating of all books entered.
2. Features
•	Add Book Reviews: Users can input book details (title, author, rating, comment).
•	Display Book List: View all added books along with their ratings and comments.
•	Calculate Average Rating: Calculate and display the average rating for all books.
•	Navigation: Navigate between screens (Main and Detailed View).
•	Error Handling: Ensures valid ratings (1-5).
3. Getting Started
1.	Clone the Repository:
Clone the project from GitHub using the link provided.
2.	Setup Android Studio:
Open the project in Android Studio.
3.	Build the Project:
Click on the Build button in Android Studio to compile and run the app.
4.	Run the Application:
Run the app on an emulator or a physical device.
4. Screenshots
•	Main Screen: Shows the button to add a book review.
•	Detailed View Screen: Shows the list of books and the average rating.
5. Features and Functionality
•	Arrays and Loops:
o	Arrays store book details: titles, authors, ratings, and comments.
o	Loops are used to calculate the average rating and display the book list.
•	Navigation:
o	Buttons allow navigation between the Main Screen and Detailed View Screen.
•	Error Handling:
o	Ensures ratings are between 1 and 5 and handles invalid inputs.

   
 
Report for the Book Review Android Application

1. Introduction
This report describes the development of a Book Review Android Application using Kotlin on Android Studio. The application is designed to store book details, including the book title, author, rating (1-5), and a user-provided comment. It allows users to view a list of books, calculate the average rating, and manage basic navigation through the app.
The app utilizes arrays, loops, and error handling, ensuring smooth interaction between the user interface (UI) and back-end logic. The primary focus of this project is on implementing proper UI design, efficient use of arrays and loops, and providing a user-friendly interface.

2. Objectives
The main objectives of the app are as follows:
1.	Correct Implementation of Arrays and Loops:
o	The app uses arrays to store book details and a loop to process the ratings for calculating the average.
2.	Proper Navigation Between Screens:
o	A Main Screen allows the user to navigate to the Detailed View Screen, where book details are displayed.
3.	User Interaction:
o	The user can add books, view the list of books, and calculate the average rating of all entered books.
4.	Error Handling and Data Validation:
o	The app performs basic validation checks, such as ensuring that ratings are within the acceptable range (1-5).
5.	ReadMe File and GitHub Integration:
o	A ReadMe document has been prepared to guide users on how to use the app and access the code.

3. App Design and Implementation
Main Screen (activity_main.xml):
This screen contains:
•	A Button to navigate to the Detailed View screen, where users can enter and view book details.
•	A second Button that allows the user to exit the app.
Detailed View Screen (activity_detailed_view.xml):
This screen contains:
•	A ListView to display the list of books entered by the user.
•	A Button to calculate the average rating of all books.
•	A Button to return to the Main Screen.
Detailed View Activity (DetailedViewActivity3.kt):
In this activity:
•	Arrays store the details of the books: titles, authors, ratings, and comments.
•	A BookListAdapter is used to bind the book details to the ListView.
•	A loop processes the ratings to calculate the average rating.
Main Activity (MainActivity.kt):
This activity allows navigation to the Detailed View screen. It contains buttons to add books and exit the app.
Adapter for ListView (BookListView.kt):
The BookListView is responsible for displaying the book details in the ListView. It retrieves data from the arrays and formats it into a list item view.

4. Code Structure
1.	Arrays:
o	titles: Stores the titles of books.
o	authors: Stores the authors of the books.
o	ratings: Stores the ratings (between 1 and 5).
o	comments: Stores the comments for each book.
2.	Loops:
o	A loop is used to display the list of books in the ListView by iterating over the arrays.
o	Another loop calculates the average rating by iterating over the ratings array.
3.	Calculating Average Rating:
o	The average rating is calculated by summing all the ratings and dividing by the number of books. This is done using a loop that processes the ratings array.
4.	Navigation:
o	A Button is used to navigate between the Main Screen and Detailed View Screen.

5. Error Handling and Validation
•	Rating Validation:
The app ensures that ratings provided by the user are between 1 and 5. If the rating is outside this range, a message is displayed to the user.

6. Screenshots
Screenshots are provided to demonstrate the following functionalities:
1.	Main Screen:
A screenshot showing the main screen where the user can navigate to the Detailed View screen.
 
2.	Detailed View Screen:
A screenshot showing the ListView displaying the books along with the option to calculate the average rating.
 
 
3.	Book View 
The user will get to see the name of the book, author, rating and comments that they have made.
 
 
It’s unfortunate the user interface is not showing for all the screens.
 
7. Conclusion
The Book Review Android App is a functional application designed using Kotlin in Android Studio. It provides a user-friendly interface to add, view, and calculate ratings for books. The implementation makes use of arrays and loops to store and process data efficiently, ensuring the app meets its functional requirements.













