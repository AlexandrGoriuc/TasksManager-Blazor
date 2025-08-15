# Blazor Task Manager

A simple task management application built with **Blazor Server**.  
This project demonstrates basic CRUD (Create, Read, Update, Delete) operations in Blazor, state management, and component interaction.

## Features

- ✅ View a list of tasks
- ➕ Add new tasks
- ✏️ Edit existing tasks
- 🗑 Delete tasks
- 📌 Mark tasks as completed

## Technologies Used

- **.NET 5 / .NET 6** (Blazor Server)
- **C#**
- **Razor Components**
- **Entity Framework Core** (optional, depending on the data source)
- **Bootstrap** for styling

## Getting Started

### Prerequisites

- [.NET SDK 5.0+](https://dotnet.microsoft.com/download)
- Visual Studio 2019/2022 with Blazor development workload installed

### Installation & Run

1. Clone the repository:
```   git clone https://github.com/yourusername/blazor-task-manager.git ```

2. Navigate to the project folder:
```   cd blazor-task-manager ```

3. Run the application:
```   dotnet run ```

4. Open your browser and go to:
```   https://localhost:5001 ```


## Project Structure

**Pages/ – Blazor pages for displaying and managing tasks**
**Shared/ – Shared components like navigation menu and layout**
**Data/ – Data models and services**
**wwwroot/ – Static files (CSS, JS, images)**

## How It Works

The app uses two-way data binding to synchronize UI elements with backend data.
For task data loading, the logic runs in OnAfterRenderAsync to ensure the UI renders before state changes.

## Future Improvements

**Add persistent storage (database)**
**Implement filtering and search**
**Add user authentication**

## License

This project is licensed under the MIT License.