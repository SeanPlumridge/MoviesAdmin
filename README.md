# MoviesAdmin

MoviesAdmin is an ASP.NET Core MVC administration application for managing movie data for the **FoulBananas** movie review platform.

The project is being developed as part of my Web Applications coursework at NSCC. Sprint 1 focuses on building the administrative foundation of the system, including database persistence and CRUD functionality for movie records.

## Project Purpose

MoviesAdmin will provide administrators with the ability to manage the movies available within the FoulBananas platform.

Administrators will be able to:

- Add new movies
- View all movies
- View individual movie details
- Edit existing movie information
- Delete movies
- Store movie data in a SQL Server database

Movie records will include:

- Title
- Synopsis
- Genre
- Rating
- Runtime
- Release date

## Technology Stack

### Application
- ASP.NET Core MVC
- C#
- Entity Framework Core
- SQL Server

### Front End
- Razor Views
- HTML
- CSS
- Bootstrap

### Development & Source Control
- Visual Studio
- Git
- GitHub

## Sprint 1 Requirements

Sprint 1 focuses on the administration portion of the movie review system.

The completed application will:

- Support full CRUD functionality for movies
- Persist movie data in a SQL Server database
- Display a summary list of all movies
- Sort movies by release date
- Provide controls to add, view, edit, and delete movies
- Include validation for movie data
- Incorporate the FoulBananas brand and consistent design

## Project Structure

The application follows the ASP.NET Core MVC architecture:

- **Models** — Represent application and movie data
- **Views** — Provide the user interface
- **Controllers** — Handle application requests and coordinate between models and views
- **wwwroot** — Contains static assets such as CSS, JavaScript, and images

## Current Status

**Sprint 1 — In Progress**

Initial project setup and source control configuration are complete.

Upcoming work includes:

1. Create the Movie model
2. Configure SQL Server and Entity Framework Core
3. Create the database schema
4. Implement movie CRUD functionality
5. Add validation
6. Implement movie sorting
7. Apply FoulBananas branding and UI improvements
8. Test and prepare the application for submission

## Future Development

Later project sprints will expand the overall FoulBananas system beyond administration to include critic movie reviews and a public-facing movie review experience.

## Author

**Sean Plumridge**  
IT Programming — NSCC
