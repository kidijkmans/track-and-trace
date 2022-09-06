# COVID-19 track and trace system

This project is a COVID-19 track and trace system with a command line interface. The program enables the recording and management of data about Events, Establishments and Users. The data is recorded for the purpose of tracing and alerting people who have been in close contact with a person who tested positive for COVID-19 [^1].

It was created as part of the *Introduction to Software Development* module of the MSc Computer Science course at Newcastle University in November 2020 but has been revised and updated in September 2022.

## Preview

<iframe width="560" height="315" src="https://www.youtube.com/embed/hBZEWHxWpEQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Tools and technologies used

- Programming language: **Java 17**
- Build tool: **Maven**
- Unit testing framework: **JUnit 4.11**

## Java library packages and classes used

- `File` (io package) -> to retrieve the CSV file containing establishments to import
- `Scanner` (util package) -> for recording user input via the command line interface and reading a CSV file
- `ArrayList` (util package) -> to store Events and Establishments
- `DateTimeFormatter`, `LocalDate`, `LocalTime`, and `Period` (time package) -> for creating date and time objects and calculating a user’s age

The code has been commented to further explain the purpose of the classes and methods.

## Getting started

1. Install [Java](https://www.oracle.com/java/technologies/downloads/#java17) and [Maven](https://www.baeldung.com/install-maven-on-windows-linux-mac)

2. Download the code in a ZIP file or clone the repository

``` $ git clone https://github.com/kidijkmans/track-and-trace.git ```

3. Open `IO.java` (located in *src/main/java/kd*) in an IDE

4. Scroll all the way down and run the `main` method

[^1]: Disclaimer: All user data is fictional, no personal information is used in the program.
