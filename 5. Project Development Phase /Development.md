# 5. Project Development Phase

## Project Title

EduGenie: Google Gemini Powered Learning Assistant

## Development Overview

The EduGenie application is developed using a lightweight web-based architecture. The backend is designed using FastAPI and the AI functionality is provided through Google Gemini.

## Technology Stack

- Python
- FastAPI
- Google Gemini API
- HTML
- CSS
- MySQL
- Generative AI

## Backend Development

FastAPI is used to create the backend API.

The backend is responsible for:

- Receiving user requests
- Processing user input
- Communicating with Google Gemini
- Returning AI-generated responses
- Handling errors and invalid requests

## Frontend Development

The frontend provides a simple interface for users.

The interface allows users to:

- Enter questions
- Select learning topics
- Request explanations
- Generate quizzes
- Request summaries
- Receive learning recommendations

## Gemini AI Integration

Google Gemini is used as the Generative AI model.

The application sends a suitable prompt to Gemini based on the user's request.

Gemini processes the request and generates an educational response.

## Core Functionalities

### Question Answering

The user enters a question and receives an AI-generated educational answer.

### Concept Explanation

The system explains difficult topics in simple language.

### Quiz Generation

The system generates quiz questions based on a selected topic.

### Summarization

The system converts long educational content into a concise summary.

### Learning Recommendations

The system provides suggestions for further learning.

### Learning Path

The system can create a structured learning path for a selected subject.

## Development Flow

```text
User Input
    ↓
Frontend
    ↓
FastAPI Backend
    ↓
Gemini API
    ↓
AI Processing
    ↓
Generated Response
    ↓
Frontend
    ↓
User
