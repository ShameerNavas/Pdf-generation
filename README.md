# PDF Generation Web App

## 📖 Overview

This is an ASP.NET Core MVC web application that allows users to generate PDF files dynamically from text input. Users can enter content through a web interface, and the application generates and downloads a PDF file instantly.

---

## 🚀 Features

* Generate PDF files from user input
* Simple and clean web interface
* Instant file download
* Server-side PDF processing
* Responsive layout using CSS

---

## 🧰 Tech Stack

* ASP.NET Core MVC
* C#
* HTML / CSS / JavaScript
* Razor Views

---

## 📁 Project Structure


```
PDF_generation/
├── Controllers/
│   └── HomeController.cs
├── Services/
│   └── PdfService.cs
├── Views/
│   ├── Home/
│   │   └── Index.cshtml
│   └── Shared/
│       └── _Layout.cshtml
├── wwwroot/
│   ├── css/
│   │   └── site.css
│   └── js/
│       └── site.js
├── appsettings.json
└── Properties/
    └── launchSettings.json
```

---

## ⚙️ How It Works

1. User enters text in the web form
2. The form sends a POST request to the server
3. The controller processes the input
4. A PDF is generated using a service
5. The file is returned as a downloadable PDF

---

## ▶️ Getting Started

### Prerequisites

* .NET SDK (6.0 or later recommended)

### Run the Application

dotnet run

Then open your browser at:

http://localhost:5230

or

https://localhost:7247

---

## 📌 Usage

1. Open the application in your browser
2. Enter text content in the input field
3. Submit the form
4. Download the generated PDF file

---

## ⚙️ Configuration

Basic configuration is stored in appsettings.json.

---

## 📄 License

This project is for educational/demo purposes.