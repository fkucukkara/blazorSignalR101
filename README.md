# BlazorSignalR101 - Real-time Chat Application

A simple yet educational Blazor WebAssembly application demonstrating the implementation of real-time communication using SignalR. This project serves as a practical example of how to integrate SignalR with Blazor for building interactive web applications.

## 🚀 Features

- Real-time chat functionality
- Blazor WebAssembly for client-side interactivity
- SignalR for real-time message broadcasting
- Clean and simple user interface
- Interactive counter demo
- Server-side and WebAssembly render modes

## 🛠️ Technology Stack

- .NET 9.0
- Blazor WebAssembly
- ASP.NET Core SignalR
- Bootstrap for styling

## 🏗️ Architecture

The solution consists of two main projects:
1. **BlazorSignalR101** (Server)
   - Hosts the SignalR hub
   - Serves the Blazor WebAssembly application
   - Handles real-time message broadcasting

2. **BlazorSignalR101.Client** (WebAssembly)
   - Contains the interactive UI components
   - Implements SignalR client connection
   - Manages real-time message display

## 💡 Key Components

- `ChatHub.cs`: SignalR hub implementation for message broadcasting
- `Chat.razor`: Blazor component implementing the chat interface
- `Program.cs`: Application configuration and SignalR setup

## 🚦 Getting Started

1. **Prerequisites**
   - .NET 9.0 SDK or later
   - A modern web browser
   - Visual Studio 2022 or VS Code

2. **Clone the Repository**
   ```bash
   git clone https://github.com/fkucukkara/blazorSignalR101.git
   cd BlazorSignalR101
   ```

3. **Run the Application**
   ```bash
   dotnet restore
   dotnet run --project BlazorSignalR101
   ```

4. Open your browser and navigate to `https://localhost:xxxx` (port number will be displayed in the console)

## 📝 Usage

1. Navigate to the Chat page using the navigation menu
2. Enter your username
3. Type a message and click Send
4. See real-time updates as other users send messages

## 🎯 Learning Points

This project demonstrates several important concepts:

- SignalR hub implementation and configuration
- Real-time client-server communication
- Blazor WebAssembly component lifecycle
- Dependency injection in Blazor
- State management in real-time applications

## License
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)