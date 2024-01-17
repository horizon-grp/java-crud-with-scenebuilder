---

# JavaFX CRUD Application with MySQL Database and Scene Builder

This JavaFX application allows users to perform CRUD operations on student records, storing the data in a MySQL database. The application is built using Scene Builder for the graphical user interface.

## Prerequisites

- Java Development Kit (JDK) installed
- MySQL database server installed and running
- MySQL Connector/J library in the project (can be obtained from [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/))
- JavaFX library included in the project (can be obtained from [OpenJFX](https://openjfx.io/))
- [Scene Builder](https://gluonhq.com/products/scene-builder/) installed

## Getting Started

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/LeloKarma/java-crud-with-scenebuilder.git
    ```

2. Open the project in your favorite Java IDE (e.g., IntelliJ, Eclipse).

3. Configure the MySQL Connector/J library in your project.

4. Open the `FXMLDocument.fxml` file in Scene Builder.

5. Use Scene Builder to modify the UI or update the layout if needed.

6. Save the changes in Scene Builder.

7. Run the `Main` class to launch the JavaFX application.

## Project Structure

```
|-- src
|   |-- main
|       |-- java
|           |-- javjdbcPac
|               |-- Main.java
|               |-- FXMLDocumentController.java
|               |-- Student.java
|       |-- resources
|           |-- FXMLDocument.fxml
|-- // Other project files and directories
```

## Database Configuration

- Database Name: `registration`
- Database User: `root`
- Database Password: `lelolelo`


Update the database connection details in the `Connect` method of `FXMLDocumentController.java` if needed.

## Features

- Add new student records
- View existing student records in a TableView
- Update information of existing student records
- Delete/remove student records

## Usage

1. Launch the application.

2. Use the graphical interface, designed with Scene Builder, to perform CRUD operations on student records.

3. The application will interact with the MySQL database to store and retrieve data.

## Known Issues

- ...

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
