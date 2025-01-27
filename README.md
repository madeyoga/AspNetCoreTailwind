# Tailwind CSS in ASP.NET Core

This repository demonstrates how to use **TailwindCSS 4** in an ASP.NET Core project.

### Requirements

Before you begin, ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [.NET SDK](https://dotnet.microsoft.com/download)

### Steps to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/madeyoga/AspNetCoreTailwind.git
```

2. **Navigate to the `Theme` directory**
Change into the directory where the Tailwind CSS project is located:
```bash
cd Theme
```

3. **Install Tailwind**
```bash
npm install
```

4. **Run Tailwind CSS in development mode**
Use the following command to start the Tailwind CLI build process in watch mode. This will build the CSS dynamically as you edit your files:
```bash
npm run dev
```

5. **Run the ASP.NET Core application**
Open a new terminal and navigate to the root of the ASP.NET Core project (if not already there). Then, use the following command to start the application:
```bash
dotnet watch --no-hot-reload
```

### Access the Application

Once both the Tailwind CSS and the ASP.NET Core application are running:
- Open your browser and navigate to `http://localhost:5000` (or the port specified in your terminal output).


