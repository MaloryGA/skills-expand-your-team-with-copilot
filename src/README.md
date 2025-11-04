# Mergington High School Activities

A website application that allows teachers to manage student extracurricular activities at Mergington High School.

## Features

- **Teacher Authentication**: Secure login system for teachers to manage student registrations
- **Activity Viewing**: Browse all available extracurricular activities with detailed information
- **Student Registration Management**: Teachers can sign up students for activities using their school email
- **Student Unregistration**: Teachers can remove students from activities they're registered for
- **Advanced Filtering**: 
  - Filter activities by category (Sports, Arts, Academic, Community, Technology)
  - Filter by day of the week (Monday through Sunday)
  - Filter by time slot (Before School, After School, Weekend)
- **Activity Search**: Search for activities by name
- **Activity Details**: View schedule, description, participant limits, and current participants for each activity
- **MongoDB Database**: Persistent data storage for activities and teacher accounts
- **RESTful API**: FastAPI backend with automatic documentation at `/docs`

## Technology Stack

- **Backend**: Python with FastAPI framework
- **Database**: MongoDB for data persistence
- **Frontend**: HTML, CSS, and JavaScript
- **Authentication**: Teacher login with Argon2 password hashing

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
