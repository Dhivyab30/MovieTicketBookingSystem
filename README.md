# MovieTicketBookingSystem

🎬 Movie Ticket Booking System 

📘 Description:

This project is a Java-based console application for booking movie tickets.
It demonstrates core Java concepts (OOP, collections, and exception handling) and JDBC integration for interacting with a database.

Users can:

View a list of movies

Check available showtimes for a movie

View and book available seats for a selected show


It follows a DAO (Data Access Object) design pattern for clean database interaction.


---

🚀 Getting Started

This project can be run directly on any Java environment with database connectivity configured.

Steps Overview:

1. Clone or download the project source files.


2. Configure your database (tables: Movies, Shows, Seats, Bookings).


3. Update database connection details in your DAO classes.


4. Compile and run the Main.java file.




---

🧱 Prerequisites

Before running the project, ensure the following are installed:

Requirement	Version/Tool

.Java JDK	8 or above
.Database	MySQL / Oracle / PostgreSQL
.JDBC Driver	Corresponding to your database
.IDE (Optional)	Eclipse / IntelliJ IDEA / VS Code
.Maven (Optional)	For managing dependencies


Database Tables Required:

.movies

.showtimes

.seats

.bookings



---

⚙️ Installation Steps

1. Clone or Download the repository:

git clone https://github.com/Dhivyab30/movie-ticket-booking.git


2. Import Project into your IDE (Eclipse or IntelliJ).


3. Configure Database Connection inside DAO classes:

Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/moviedb", "root", "password");


4. Compile and Run:

javac org/anudip/main/Main.java
java org.anudip.main.Main




---

🧑‍💻 Usage / Running the Application

Once you run the program, you’ll see:

Welcome to Movie Ticket Booking (Console Demo)
1) List Movies
2) View Shows for Movie
3) Exit
Choose:

Example Flow:

1. Select 1 → Lists all movies.


2. Select a movie ID → Lists showtimes.


3. Select a showtime → Displays available seats.


4. Choose a seat and enter your name → Confirms booking.




---

🧪 Running Tests

You can manually test by:

Booking the same seat twice (should show “Booking failed”).

Checking different show IDs and seat IDs.

Verifying data in the database (bookings table updates correctly).


(Optional: Add JUnit tests for DAO classes if you want automated testing.)


---

🌐 Deployment

This is a console-based project, so no web deployment is needed.
However, it can later be:

Extended into a web app using JSP/Servlets or Spring Boot.

Deployed on a Tomcat server with a web interface.



---

🛠️ Build With

*Java SE 8+

*JDBC (Java Database Connectivity)

*MySQL / PostgreSQL

*DAO Design Pattern

*Scanner (for console input)



---

🏁 Conclusion:

The Movie Ticket Booking System demonstrates a simple but powerful use of Java and JDBC for real-world database-driven applications.
It helps beginners understand:

Data access layers using DAO pattern

CRUD operations via JDBC

Command-line interaction with database-backed logic.



