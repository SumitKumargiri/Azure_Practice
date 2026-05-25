# Azure Function Practice 🚀

This project is built using Azure Functions with .NET.

It demonstrates how to create and run HTTP Trigger Azure Functions locally and on Azure.

---

## 📌 Features

- HTTP Trigger Azure Function
- GET and POST API support
- Logging support
- Local development setup
- Azure deployment ready

---

## 🛠 Technologies Used

- C#
- .NET
- Azure Functions
- Visual Studio 2022

---

## 📂 Project Structure

```bash
Azure_Practice/
│
├── Function1.cs
├── host.json
├── local.settings.json
└── Azure_Practice.csproj
```

---

## ⚙️ Prerequisites

Before running this project install:

- .NET SDK
- Azure Functions Core Tools
- Visual Studio 2022

---

## ▶️ Run Locally

Clone the project:

```bash
git clone https://github.com/YOUR_USERNAME/Azure_Practice.git
```

Go to project folder:

```bash
cd Azure_Practice
```

Run the function:

```bash
func start
```

---

## 🌐 API Endpoint

```http
GET http://localhost:7071/api/Function1
```

Example:

```http
GET http://localhost:7071/api/Function1?name=Sumit
```

Response:

```json
{
  "message": "Hello, Sumit"
}
```

---

## ☁️ Deploy to Azure

Publish using Visual Studio:

1. Right click project
2. Publish
3. Select Azure Function App
4. Deploy

---

## 📸 Screenshot

Add your screenshots here.

---

## 👨‍💻 Author

- Sumit Giri

---

## 📄 License

This project is licensed under the MIT License.
