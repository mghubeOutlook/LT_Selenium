# LT_Selenium

This project demonstrates running Selenium tests with TestNG on different browser and OS combinations using LambdaTest.

## Prerequisites

- Maven
- Git
- Java 8 or later

## Setup

1. Clone the repository
    ```sh
    git clone https://github.com/yourusername/LT_Selenium.git
    ```
2. Navigate to the project directory
    ```sh
    cd LT_Selenium
    ```
3. Open in Gitpod (if using Gitpod)
    ```sh
    gp open .
    ```

## Running Tests

1. Use the following command to run the tests
    ```sh
    ./mvnw test
    ```

## Configuration

- Update the `testng.xml` file to configure the browsers, versions, and platforms.
- Update the `pom.xml` to add or update dependencies.

## Files

- **seleniumPKG**: Contains all the test classes.
- **pom.xml**: Project Object Model file for managing dependencies.
- **.gitpod.yml**: Configuration file for Gitpod environment.
- **testng.xml**: TestNG suite configuration.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
