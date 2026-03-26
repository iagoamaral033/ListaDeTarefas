# 📝 Todo App - Blazor Server

![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![Blazor](https://img.shields.io/badge/Blazor-Server-purple)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

A simple and interactive **Todo List application** built with **ASP.NET Blazor Server**, designed to demonstrate component-based UI and real-time updates.

---

## 🚀 Features

- ✅ Add new tasks  
- ✏️ Edit tasks in real time  
- ✔️ Mark tasks as completed  
- 🔢 Live counter of pending tasks  
- ⚡ Interactive UI with Blazor Server  

---

## 🛠️ Tech Stack

- .NET 8
- ASP.NET Core
- Blazor Server
- C#
- Razor Components

---

## 📂 Project Structure

/Components  
/Pages  
/wwwroot  
Program.cs  
App.razor  

---

## ▶️ Getting Started

### Prerequisites

- .NET 8 SDK installed  
https://dotnet.microsoft.com/download

---

### Run the project

dotnet restore  
dotnet run  

Then open in your browser:

https://localhost:xxxx/todo

---

## 💡 How it works

This application uses a Razor component (`/todo`) to manage an in-memory list of tasks.

Each task contains:
- Title → task name  
- IsDone → completion status  

Users can:
- Add tasks  
- Edit tasks instantly  
- Mark tasks as done  

---

## ⚠️ Limitations

- No database (data is not persisted)  
- Data resets on page reload  

---

## 🔮 Future Improvements

- Database integration  
- Delete tasks  
- Filter tasks  
- Due dates  
- UI improvements  

---

## 👨‍💻 Author

Developed by Iago Amaral 🚀
