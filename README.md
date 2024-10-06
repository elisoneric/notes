 Collaborative Note-Taking App

## Overview
This project is a collaborative note-taking application built with Laravel and Blade, allowing users to create, edit, and share notes. Users can manage their own notes and also collaborate by editing shared notes.

## Features
- User authentication (registration and login)
- Create, read, update, and delete notes
- Edit shared notes
- Responsive design
- Note tagging for organization
- Note sharing functionality

## Requirements
- PHP >= 7.3
- Composer
- Laravel >= 8.x
- MySQL or any compatible database
- Node.js and NPM (for frontend assets)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/notes-app.git
cd notes-app
```

### 2. Install Dependencies
Run the following command to install the required PHP dependencies using Composer:
```bash
composer install
```

### 3. Set Up Environment File
Copy the `.env.example` file to create your own `.env` file:
```bash
cp .env.example .env
```
Then, update your `.env` file with your database connection details:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

### 4. Create the Database
Create a new database in your MySQL server (e.g., `notes_db`).

### 5. Run Migrations
Run the migrations to create the necessary tables in your database:
```bash
php artisan migrate
```

### 6. Seed the Database (Optional)
If you have seed data, you can run the following command to populate your database:
```bash
php artisan db:seed
```

### 7. Install Frontend Dependencies
If your project includes frontend assets, install them using NPM:
```bash
npm install
```

### 8. Build Frontend Assets
Build the frontend assets:
```bash
npm run dev
```

### 9. Start the Development Server
Run the following command to start the Laravel development server:
```bash
php artisan serve
```
You can now access the application at `http://localhost:8000`.

## Usage
- **Register an Account**: Users must create an account to start using the application.
- **Create Notes**: After logging in, users can create and manage their notes.
- **Share Notes**: Users can share notes with others, allowing collaborative editing.

## Contributing
If you wish to contribute to this project, please fork the repository and create a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- Laravel Framework
- Bootstrap for styling
- Icons8 for icons
