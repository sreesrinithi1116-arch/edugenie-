# 3. Project Design Phase

## Project Title

EduGenie: Google Gemini Powered Learning Assistant

## System Architecture

The EduGenie system consists of a frontend, backend, AI service, and optional database.

```text
+----------------------+
|        User          |
+----------+-----------+
           |
           v
+----------------------+
|    Web Interface     |
|     HTML + CSS       |
+----------+-----------+
           |
           v
+----------------------+
|    FastAPI Backend   |
+----------+-----------+
           |
           v
+----------------------+
|   Google Gemini AI   |
+----------+-----------+
           |
           v
+----------------------+
|   Response Processing|
+----------+-----------+
           |
           v
+----------------------+
|        User          |
+----------------------+
