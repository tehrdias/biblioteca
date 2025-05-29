# Biblioteca Project

## Overview
The Biblioteca project is a simple library management system that allows users to manage books in a library. It provides functionalities to add, remove, and search for books.

## Project Structure
```
biblioteca
├── src
│   └── main
│       └── java
│           └── Biblioteca.java
├── pom.xml
└── README.md
```

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Maven

### Building the Project
To build the project, navigate to the project root directory and run the following command:
```
mvn clean install
```

### Running the Application
After building the project, you can run the application using the following command:
```
mvn exec:java -Dexec.mainClass="Biblioteca"
```

## Features
- Add books to the library
- Remove books from the library
- Search for books by title or author

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License.