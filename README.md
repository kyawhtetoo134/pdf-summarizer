Mahij Gosai

# PDF Summarizer

A Java-based web application for summarizing content from PDF documents using Spring Boot.

## Features

- Upload a PDF file
- Automatically extract and summarize the content
- View the summarized text via a clean web interface

## Technologies Used

- Java 11+
- Spring Boot
- Maven
- Thymeleaf (for HTML templates)

## Project Structure

```
pdf-summarizer/
├── src/
│   ├── main/
│   │   ├── java/com/
│   │   │   ├── controller/         # Handles web requests
│   │   │   ├── model/              # PDF request data model
│   │   │   ├── service/            # Summarization logic
│   │   │   └── pdfsummarizer/      # Spring Boot application entry
│   │   └── resources/
│   │       ├── templates/          # HTML templates (index, result)
│   │       └── application.properties
├── pom.xml                         # Maven configuration
```

## How to Run

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd pdf-summarizer
   ```

2. **Build the project**

   ```bash
   mvn clean install
   ```

3. **Run the application**

   ```bash
   mvn spring-boot:run
   ```

4. **Access the web interface**

   Open your browser and navigate to `http://localhost:8080`

## Notes

- Ensure you have Java and Maven installed on your system.
- PDF processing and summarization logic is handled in `PdfService.java`.

## License

This project is licensed under the MIT License.

## Screenshot of Project Demonstration
<img width="1440" alt="Screenshot 2025-04-21 at 10 11 15 AM" src="https://github.com/user-attachments/assets/52aaa491-08c5-4350-ad02-1a0c8f5837f1" />

<img width="1440" alt="Screenshot 2025-04-21 at 10 11 06 AM" src="https://github.com/user-attachments/assets/97629be5-2841-442c-bb00-9e59d4660032" />







