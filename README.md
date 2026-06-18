# SMK Telkom RPL Prep: Zero to Hero Developer Roadmap

Welcome to your Software Engineering roadmap. This guide is designed to prepare you for the Rekayasa Perangkat Lunak (RPL) major by taking you from writing basic text to building high-performance backend systems.

## How to use this repository:
1. Fork or clone this repository.
2. Check off the boxes (`[x]`) as you complete each day.
3. Keep all your daily code in organized folders (e.g., `/week-1/day-1`).

---

## 🛠️ The Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Text Editors** | Sublime Text, Notepad++, Visual Studio Code (VS Code) |
| **IDEs** | Visual Studio Community, Netbeans |
| **Languages & Environments**| Python (Anaconda), Node.js, PHP, .NET, Java |
| **Databases** | MySQL (via XAMPP) |
| **API & Deployment Tools** | Postman, FileZilla, Git |

---

## 📅 Week 1: The Visual Foundation (HTML & CSS)
**Goal:** Understand how web pages are structured and styled.  
**Tools:** Notepad++ / Sublime Text (Days 1-2), VS Code (Days 3-5)

- [ ] **Day 1: The Raw Structure** **Read:** Intro to HTML (W3Schools).  
  **Task:** Open Notepad++ or Sublime Text. Write a basic HTML5 boilerplate.  
  **Practice:** Create an article about a favorite topic using `<h1>` to `<h6>`, `<p>`, `<strong>`, and `<em>`.

- [ ] **Day 2: Media and Links** **Read:** HTML Images and Links.  
  **Task:** Create a navigation menu using `<ul>` and `<li>`.  
  **Practice:** Build an index page that links to 3 other HTML pages. Embed an image and a YouTube video.

- [ ] **Day 3: Transition to VS Code & Intro to CSS** **Read:** Intro to VS Code (Extensions, Live Server).  
  **Task:** Install VS Code and the "Live Server" extension.  
  **Practice:** Write inline, internal, and external CSS. Change text colors, background colors, and font families.

- [ ] **Day 4: The CSS Box Model** **Read:** CSS Margins, Padding, and Borders.  
  **Task:** Understand the difference between margin (outside) and padding (inside).  
  **Practice:** Create a grid of "Character Cards" (like in a gacha game) with proper spacing and borders.

- [ ] **Day 5: Week 1 Mini-Project** **Task:** Build a static Wiki page for a game like Honkai: Star Rail.  
  **Requirements:** Include a navigation bar, character images, formatted lore text, and clean CSS styling.

---

## 📅 Week 2: Programming Logic & Algorithms (Python)
**Goal:** Learn how a computer "thinks" using variables, loops, and conditions.  
**Tools:** Anaconda (Jupyter Notebook / Spyder)

- [ ] **Day 6: Python Setup & Basics** **Read:** Installing Anaconda and launching Jupyter Notebook.  
  **Task:** Understand variables, strings, integers, and floats.  
  **Practice:** Write a script that prints a welcome message and calculates basic math operations.

- [ ] **Day 7: User Input & Conditionals** **Read:** Python `input()` and `if`/`elif`/`else` statements.  
  **Task:** Ask the user for their age and output different messages based on the result.  
  **Practice:** Build a "Power Level Calculator" that asks for a character's stats and outputs their tier (e.g., Planetary, Star, or Universe level).

- [ ] **Day 8: Loops (Doing things repeatedly)** **Read:** Python `for` and `while` loops.  
  **Task:** Write a loop that counts from 1 to 100.  
  **Practice:** Create a simulated "gacha pull" loop. Have it loop 10 times and randomly print "3-star", "4-star", or "5-star".

- [ ] **Day 9: Data Structures (Lists & Dictionaries)** **Read:** Python Lists and Dictionaries.  
  **Task:** Store multiple items in a single variable.  
  **Practice:** Create a dictionary of 5 characters and their corresponding damage multipliers.

- [ ] **Day 10: Week 2 Mini-Project** **Task:** Build a Terminal-Based RPG Battle Simulator.  
  **Requirements:** Use a `while` loop for the battle phase. Use `if` statements to check if HP hits 0. Use `input` to choose "Attack" or "Heal".

---

## 📅 Week 3: Databases & The Classic Backend (XAMPP & PHP)
**Goal:** Learn the standard SMK Telkom web stack (RDBMS and Server-Side Scripting).  
**Tools:** XAMPP (Apache & MySQL), VS Code

- [ ] **Day 11: Introduction to XAMPP & SQL** **Read:** How relational databases work.  
  **Task:** Start Apache and MySQL in the XAMPP Control Panel. Open phpMyAdmin in the browser.  
  **Practice:** Manually create a database named `inventory_db` and a table named `items`.

- [ ] **Day 12: SQL Queries** **Read:** SQL `SELECT`, `INSERT`, `UPDATE`, `DELETE` (CRUD).  
  **Task:** Use the SQL tab in phpMyAdmin.  
  **Practice:** Insert 5 records into your `items` table. Write a query to select items that cost more than 1000 gold.

- [ ] **Day 13: Intro to PHP** **Read:** PHP syntax and variables.  
  **Task:** Create a file named `index.php` inside the `C:\xampp\htdocs` folder.  
  **Practice:** Write a PHP script that prints dynamic HTML based on variables (e.g., printing the current date and time).

- [ ] **Day 14: Connecting PHP to MySQL** **Read:** PHP mysqli connection.  
  **Task:** Connect your `index.php` file to the `inventory_db` you made on Day 11.  
  **Practice:** Fetch the data from the `items` table and display it in an HTML `<table>` using a `while` loop.

- [ ] **Day 15: Week 3 Mini-Project** **Task:** Build a functional CRUD Web App.  
  **Requirements:** Create an HTML form that allows you to add a new item to the database, and a button to delete an item.

---

## 📅 Week 4: Modern JavaScript & APIs (NodeJS & Postman)
**Goal:** Separate the frontend from the backend by building RESTful APIs.  
**Tools:** Node.js, VS Code, Postman

- [ ] **Day 16: NodeJS Setup & NPM** **Read:** What is Node.js and the Node Package Manager (NPM).  
  **Task:** Install Node.js. Run `node -v` in the terminal to verify. Initialize a project using `npm init -y`.

- [ ] **Day 17: Introduction to Express.js** **Read:** Express.js web framework basics.  
  **Task:** Install Express (`npm install express`).  
  **Practice:** Create a simple server that listens on port 3000 and responds with "Hello World" when you visit `http://localhost:3000`.

- [ ] **Day 18: Building JSON Endpoints** **Read:** What is JSON data format?  
  **Task:** Instead of sending HTML, configure your Express server to send a JSON array of users.

- [ ] **Day 19: Testing APIs with Postman** **Read:** HTTP Methods (`GET`, `POST`, `PUT`, `DELETE`).  
  **Task:** Install Postman.  
  **Practice:** Create a `POST` route in Node.js. Use Postman to send JSON data to your server and log it in the terminal.

- [ ] **Day 20: Week 4 Mini-Project** **Task:** Build a "Player Stats" REST API.  
  **Requirements:** Endpoints to get all players (`GET`), get one player by ID (`GET`), and create a new player (`POST`). Test entirely via Postman.

---

## 📅 Week 5: Enterprise Architecture (.NET)
**Goal:** Prepare for high-concurrency, professional-grade system development.  
**Tools:** Visual Studio Community, .NET SDK

- [ ] **Day 21: Visual Studio & C# Basics** **Read:** C# Syntax and Object-Oriented Programming (OOP) basics.  
  **Task:** Install Visual Studio Community (select the .NET Desktop & Web development workloads).  
  **Practice:** Create a new C# Console Application. Write a script using C# Classes and Objects.

- [ ] **Day 22: .NET Core Web API** **Read:** Introduction to ASP.NET Core.  
  **Task:** Create a new ASP.NET Core Web API project.  
  **Practice:** Explore the default `WeatherForecast` controller to understand how routing works in .NET.

- [ ] **Day 23: Controllers and Routing** **Read:** Creating Controllers in ASP.NET.  
  **Task:** Add a new Controller (e.g., `TransactionController`).  
  **Practice:** Create endpoints that return hardcoded data models (e.g., an Account ID and Balance).

- [ ] **Day 24: High-Performance Concepts** **Read:** Asynchronous programming in C# (`async` / `await`).  
  **Task:** Update your controller methods to be asynchronous.  
  **Practice:** Add a simulated delay (`Task.Delay`) to understand how non-blocking requests handle multiple users simultaneously.

- [ ] **Day 25: Week 5 Mini-Project** **Task:** Build a Bank Transaction API prototype.  
  **Requirements:** An endpoint to "Check Balance" and an endpoint to "Deposit Funds". Test the speed and responses using Postman.

---

## 📅 Week 6: Version Control, Java, & Deployment
**Goal:** Learn how professionals manage code, collaborate, and push to the live internet.  
**Tools:** Git, Netbeans (Java), FileZilla

- [ ] **Day 26: Introduction to Git** **Read:** Version Control basics (What are commits?).  
  **Task:** Install Git. Run `git init` in one of your project folders.  
  **Practice:** Use `git add .` and `git commit -m "Initial commit"` to save a snapshot of your code.

- [ ] **Day 27: GitHub & Remote Repositories** **Read:** Pushing code to GitHub.  
  **Task:** Create a GitHub account. Create a new empty repository.  
  **Practice:** Link your local Git repository to GitHub (`git remote add origin`) and push your code (`git push -u origin main`).

- [ ] **Day 28: Java Basics (Netbeans)** **Read:** Java Syntax and strictly typed languages.  
  **Task:** Install Netbeans and the Java JDK. Create a new Java project.  
  **Practice:** Write a simple Java program that utilizes Classes, mimicking the logic you learned in C# / Python.

- [ ] **Day 29: Web Hosting & FileZilla** **Read:** FTP (File Transfer Protocol) basics.  
  **Task:** Sign up for a free web host (like InfinityFree or 000webhost).  
  **Practice:** Use FileZilla to connect to your host and upload the HTML/CSS/PHP files from Week 3 to the live internet.

- [ ] **Day 30: Final Review & Portfolio Setup** **Task:** Create a `README.md` for your GitHub profile showcasing what you've learned.  
  **Practice:** Pin your best projects (The Python Game, the PHP CRUD app, and the .NET API) to your GitHub homepage so your teachers at SMK Telkom can see your skills.
