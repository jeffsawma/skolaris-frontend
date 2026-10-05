# Skolaris — Frontend

Skolaris is a school management platform developed as the final team project of my AEC in Web Technologies Programming (Programmation en technologies Web) at Cégep Gérald-Godin.

This repository is an independent portfolio copy of the frontend project and preserves the original team Git history and contributors.

**Project type:** AEC final team project  
**Frontend:** Blazor / C# / .NET 9  
**Backend:** ASP.NET Core Web API / Entity Framework Core / SQL Server  
**Original team repository:** https://github.com/bouchelaghemmohammed/skolarisfront

---

## Project Overview

Skolaris was designed as a centralized school management system for administrative staff, teachers, and students.

The frontend provides role-oriented interfaces for areas including:

- Authentication and password recovery
- Administrative, teacher, and student dashboards
- User management
- Programs and academic levels
- Groups
- Courses and offered courses
- Registrations
- Grades and evaluation grids
- Report cards
- Absences
- Academic records
- Academic sessions
- Class schedules
- Messaging
- Notifications
- Audit logs

---

## Technology Stack

- C#
- .NET 9
- Blazor Web App
- Interactive Server rendering
- Razor Components
- ASP.NET Core
- HttpClient
- HTML
- CSS
- Bootstrap

---

## My Contributions

This was a collaborative team project. My frontend contributions included:

- Building the groups management interface
- Fixing group editing state logic
- Displaying associated groups in offered courses
- Building the academic levels management interface
- Improving the offered-courses management interface
- Building registration management features
- Adding CSV and PDF export functionality for registrations

The preserved Git history includes my development branch and the original team commits, allowing the collaboration and contribution history to remain visible.

---

## Portfolio Copy

The original application was developed collaboratively in another team member's GitHub repository.

This repository was created as an independent portfolio copy after completion of the project. The original commit history, authorship, merges, and development branches have been preserved.

Unrelated local files, generated build output, and user-specific development files were removed before this portfolio copy was published.

---

## Local Development

### Prerequisites

- .NET 9 SDK
- The Skolaris backend running locally

The frontend currently expects the backend API at:

http://localhost:5043/

### Build

dotnet build

### Run

dotnet run

The application uses Blazor interactive server rendering.

---

## Related Repository

Backend portfolio repository:

https://github.com/jeffsawma/skolaris-backend

---

## Academic Context

Skolaris was developed as the final project of the AEC in Web Technologies Programming at Cégep Gérald-Godin.

The project provided practical experience with collaborative full-stack development, Git/GitHub workflows, feature branches, pull requests, Blazor, Razor Components, REST API integration, role-based interfaces, and export functionality.
