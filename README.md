# BCRA Credit Portal

## Project Documentation

This project provides a comprehensive solution for handling credit operations in accordance with BCRA standards. It includes a user-friendly interface for managing credit applications and a robust backend for processing and storing data.

## Features

- User authentication and authorization
- Credit application management
- Integration with external APIs for credit scoring
- Data encryption for sensitive information
- Administrative dashboard for monitoring and reporting

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/riesgopais/bcra-credit-portal.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bcra-credit-portal
   ```
3. Install the necessary dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file and set the required environment variables.
5. Start the application:
   ```bash
   npm start
   ```

## API Endpoints

- **POST /api/credit/apply**: Submit a new credit application
- **GET /api/credit/status/:id**: Check the status of a credit application
- **GET /api/credit/scoring/:id**: Retrieve credit scoring data for an applicant

## Security Notes

- Ensure to keep sensitive information in environment variables.
- Use HTTPS for all API requests.
- Regularly update dependencies to patch known vulnerabilities.
- Implement rate limiting to prevent abuse of the API.