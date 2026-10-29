# 🎓 University Search App

A responsive web application that helps users discover colleges and universities around the world by searching for a country. The application fetches university information from the **Hipolabs Universities API** and displays university names, state or province details, and the total number of results.

🔗 **GitHub Repository:** https://github.com/ShyamKumarChaurasiya/University-Search-App

## ✨ Features

- 🌍 Search universities by country
- 🎓 Discover colleges and universities worldwide
- 📋 Display university names dynamically
- 📍 Show state or province information when available
- 🔢 Display the total number of universities found
- 🚫 Handle empty search results
- ⌨️ Search using the Enter key
- 📱 Responsive design for mobile and desktop
- 🎨 Modern UI with gradient styling and hover effects
- ⚡ Fetch data asynchronously using Axios

## 🛠️ Technologies Used

- **HTML5** – Application structure
- **CSS3** – Styling, Flexbox, Grid, animations, and responsive design
- **JavaScript** – DOM manipulation and application functionality
- **Axios** – HTTP requests to fetch university data
- **Hipolabs Universities API** – University information
- **Google Fonts** – Poppins typography

## 🌐 API Used

This project uses the Hipolabs Universities API to retrieve university information.

**API Endpoint:**

```text
http://universities.hipolabs.com/search?country=
```

Example:

```text
http://universities.hipolabs.com/search?country=India
```

The API provides university information such as names, countries, state or province details, domains, and website URLs. This application displays the university name and state or province information where available.

API Reference: [Hipolabs University Domains API](https://github.com/Hipo/university-domains-list-api)

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ShyamKumarChaurasiya/University-Search-App.git
```

### 2. Navigate to the Project Folder

```bash
cd University-Search-App
```

### 3. Run the Application

Open the `index.html` file in your browser.

Alternatively, use the **Live Server** extension in Visual Studio Code.

> An internet connection is required to load the Google Fonts, Axios library, and university data from the API.

## 📂 Project Structure

```text
University-Search-App/
│
├── index.html       # Main HTML structure
├── style.css        # Styling and responsive design
├── main.js          # API requests and university search logic
└── README.md        # Project documentation
```

## 💡 How to Use

1. Open the University Search App.
2. Enter a country name, such as `India`, `Nepal`, or `Canada`.
3. Click the **Search** button or press **Enter**.
4. View the universities found for the selected country.
5. Check the total number of universities displayed.

## 🎯 Learning Objectives

This project helped me practice:

- Fetching data from a public REST API
- Making asynchronous HTTP requests using Axios
- Working with `async` and `await`
- Handling API responses and errors
- Dynamically creating and updating HTML elements
- Using JavaScript event listeners
- Displaying API data in a responsive grid layout
- Handling empty search results

## 👨‍💻 Author

**Shyam Kumar Chaurasiya**

- GitHub:https://github.com/ShyamKumarChaurasiya

---

⭐ If you find this project useful, feel free to star the repository!