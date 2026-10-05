# AI Email Generator

An AI-powered email generation application built using Spring Boot and Google's Gemini API. The application helps users generate professional, formal, casual, or custom emails based on user prompts.

## Features

- Generate emails using AI
- Multiple email tones and styles
- REST API-based backend
- Gemini API integration
- Clean Spring Boot architecture
- Easy to extend for browser extensions or frontend applications

## Tech Stack

- Java 21
- Spring Boot
- Spring Web
- Maven
- Gemini API
- REST APIs

## Project Structure

- Controller Layer – Handles HTTP requests
- Service Layer – Contains business logic
- API Integration Layer – Communicates with Gemini API
- Configuration Layer – External configuration management

## API Endpoint

### Generate Email

POST /api/email/generate

Request Body:

```json
{
  "emailContent": "Request for leave due to medical reasons",
  "tone": "Professional"
}
```

Response:

```json
{
  "generatedEmail": "Dear Manager..."
}
```

## Setup Instructions

1. Clone the repository
2. Configure Gemini API credentials
3. Run:

```bash
mvn clean install
mvn spring-boot:run
```

4. Access the application locally

## Future Enhancements

- Email templates
- Browser extension integration
- Multi-language support
- Email summarization
- Email reply generation

## Author

Sanskruti Kale
Engineering Student | Java & Spring Boot Developer
