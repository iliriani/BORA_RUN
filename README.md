# BORA_RUN
This is a Maven-based Spring Boot project that integrates various libraries for processing and managing data with RDF, NLP, and EMF Ecore models. Below are the instructions to clone, set up, and run the project, along with the requirements.

## Requirements
To run this project, ensure you have the following installed:

1. **Java Development Kit (JDK)**:
   - Version: 11 or higher
   - Installation:
     - Download and install from [Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or [OpenJDK](https://adoptium.net/).
     - Verify installation: `java -version`

2. **Maven**:
   - Version: 3.6.0 or higher
   - Installation:
     - Download from [Apache Maven](https://maven.apache.org/download.cgi).
     - Follow the [installation instructions](https://maven.apache.org/install.html).
     - Verify installation: `mvn -version`

3. **Git**:
   - Required to clone the repository.
   - Installation:
     - Download from [Git](https://git-scm.com/downloads).
     - Verify installation: `git --version`

4. **IDE (Optional)**:
   - Recommended: IntelliJ IDEA, Eclipse, or VS Code with Java extensions for easier development.
   - Ensure the IDE supports Maven projects.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/iliriani/BORA_Ecore.git
   cd BORA_Ecore
   ```

2. **Install Dependencies**:
   ```bash
   mvn clean install
   ```
   - Maven will automatically download dependencies listed in the pom.xml file.
   - Run the following command in the project root directory

3. **Running the Project**:
   - Run as a Spring Boot Application:
   ```bash
   mvn spring-boot:run
   ```
   - The application will start on the default port (usually 8080) unless configured otherwise.

4. **Access the Application**:
   - Open a browser and navigate to http://localhost:8080 (or the configured port).
   - If Swagger is enabled, API documentation may be available at [http://localhost:8080/swagger-ui.html](http://localhost:8080/v2/api-docs)

For more detailed information (source, documentation, etc.) check the [BORA repository](https://github.com/iliriani/BORA_Ecore)
