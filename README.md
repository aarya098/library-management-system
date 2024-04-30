# LibraNet-Interactive

LibraNet-Interactive is a comprehensive library management system designed for modern libraries to manage their book collections efficiently. Built with a web-based interface, it allows users to interact with the system to perform various library management tasks. It also integrates a machine learning-based recommendation system to suggest books to users based on their interests.

## Features

### Backend

- **User Authentication**: Secure login and signup functionalities to manage user access.
- **Authorization Levels**: Different levels of access control for users based on roles.
- **Book Management**: Users can add, edit, and remove their book entries.
- **Book Recommendation System**: A machine learning model to suggest books to users.

### Frontend

- **Interactive Pages**: User-friendly pages to add, edit, and delete book entries.
- **Book Browsing**: A dedicated page for users to browse all books with applied filters.
- **Recommendation Requests**: Users can request book recommendations based on their preferences.

## Technology Stack

- **Backend**: Python with FastAPI
- **ORM**: SQLModel or SQLAlchemy
- **Database**: PostgreSQL
- **Version Control**: Git
- **Frontend**: JavaScript with Next.js or React.js
- **Styling**: MUI (Material-UI) or Bootstrap

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software:

- Python 3.8+
- pip/pipenv or Poetry for Python package management
- Node.js and npm/pnpm for JavaScript package management
- PostgreSQL database

### Installing

A step by step series of examples that tell you how to get a development environment running.

#### Setting up the backend
![image](https://github.com/aarya098/library-management-system/assets/135094271/9c2887ce-d67d-4468-90a0-11cce8d40751)
![image](https://github.com/aarya098/library-management-system/assets/135094271/6aa979ab-ccb7-42fe-a2b2-19920b29db50)
![image](https://github.com/aarya098/library-management-system/assets/135094271/cb4ba930-1cc6-4e97-8555-0f5f4940ec3c)




```bash
# Clone the repository
git clone https://github.com/yourusername/LibraNet-Interactive.git
cd LibraNet-Interactive

# Install dependencies
poetry install

# Run the application
poetry run uvicorn app.main:app --reload

# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Run the application
npm run dev

