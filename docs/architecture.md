# Project Architecture

## 1. Overview

The UIDAI Accessibility Audit project follows a monorepo-style structure. It separates frontend, backend, documentation and testing resources into individual directories.

## 2. Repository Components

### Client
The client directory represents the frontend of the application. It is responsible for displaying information and providing the user interface.

### Server
The server directory represents the backend. It is responsible for processing requests and handling application logic.

### Docs
The docs directory contains project documentation, accessibility audit reports and supporting screenshots.

### Tests
The tests directory contains test cases and testing resources used to verify application functionality and accessibility.

## 3. Architecture Flow

User
↓
Client (Frontend)
↓
Server (Backend)
↓
Response to Client
↓
Information displayed to User

## 4. Technology and Tools

- HTML and CSS – Frontend structure and styling
- Python – Potential backend implementation
- GitHub – Version control and repository management
- Google Lighthouse – Accessibility testing
- Chrome DevTools – Manual inspection and testing

## 5. Design Considerations

- Maintain a clear separation between frontend and backend.
- Keep documentation organised.
- Include accessibility testing throughout development.
- Design interfaces that support keyboard navigation and assistive technologies.

## 6. Current Status

The repository structure and initial accessibility audit documentation have been created. Application implementation is not yet started.
