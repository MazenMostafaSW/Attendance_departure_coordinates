# Location Check-in System

A robust employee attendance and location tracking system built with Node.js, Express, and MongoDB.

## Overview

This application provides a comprehensive solution for tracking employee attendance and location data in real-time. It offers organization management, employee tracking, and location-based check-ins using Google Maps API integration.

## Features

- **Employee Attendance Tracking**: Record and monitor employee check-ins and attendance
- **Location Services**: Leverage Google Maps API for accurate location tracking
- **Organization Management**: Create and manage multiple organizations
- **User Management**: Add, update, and remove employees with role-based permissions
- **RESTful API**: Well-structured API endpoints for organizations, employees, and attendance data

## Technology Stack

- **Backend**: Node.js with Express.js framework
- **Database**: MongoDB with Mongoose ODM
- **Location Services**: Google Maps API
- **Configuration**: Environment-based configuration using dotenv

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Configure environment variables in a `.env` file
4. Start the server:
   ```
   npm start
   ```

## API Documentation

The API provides endpoints for managing:
- Organizations
- Employees
- Attendance records
- Location data

Detailed API documentation is available in the `/docs` directory.

## License

[MIT License](LICENSE)
