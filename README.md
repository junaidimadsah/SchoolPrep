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

- [ ] **Day 1: The Raw Structure**
  * **Resource:** [MDN Web Docs - Getting started with the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
  * **Task:** Open Notepad++ or Sublime Text. Write a basic HTML5 boilerplate.  
  * **Practice:** Create an article about a favorite topic using `<h1>` to `<h6>`, `<p>`, `<strong>`, and `<em>`.

- [ ] **Day 2: Media and Links**
  * **Resource:** [W3Schools - HTML Links & Images](https://www.w3schools.com/html/html_links.asp)
  * **Task:** Create a navigation menu using `<ul>` and `<li>`.  
  * **Practice:** Build an index page that links to 3 other HTML pages. Embed an image and a YouTube video.

- [ ] **Day 3: Transition to VS Code & Intro to CSS**
  * **Resource:** [VS Code Official Documentation - Getting Started](https://code.visualstudio.com/docs/introvideos/basics) & [MDN - CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps)
  * **Task:** Install VS Code and the "Live Server" extension.  
  * **Practice:** Write inline, internal, and external CSS. Change text colors, background colors, and font families.

- [ ] **Day 4: The CSS Box Model**
  * **Resource:** [CSS-Tricks - The CSS Box Model](https://css-tricks.com/the-css-box-model-introduction/)
  * **Task:** Understand the difference between margin (outside) and padding (inside).  
  * **Practice:** Create a grid of "Character Cards" (like in a gacha game) with proper spacing and borders.

- [ ] **Day 5: Week 1 Mini-Project**
  * **Resource:** [freeCodeCamp - How to Build a Website Tutorial](https://www.freecodecamp.org/news/html-css-tutorial-build-a-website/)
  * **Task:** Build a static Wiki page for a game like Honkai: Star Rail.  
  * **Requirements:** Include a navigation bar, character images, formatted lore text, and clean CSS styling.

---

## 📅 Week 2: Programming Logic & Algorithms (Python)
**Goal:** Learn how a computer "thinks" using variables, loops, and conditions.  
**Tools:** Anaconda (Jupyter Notebook / Spyder)

- [ ] **Day 6: Python Setup & Basics**
  * **Resource:** [Anaconda Documentation - Getting Started](https://docs.anaconda.com/anaconda/getting-started/) & [Real Python - Variables in Python](https://realpython.com/python-variables/)
  * **Task:** Understand variables, strings, integers, and floats.  
  * **Practice:** Write a script that prints a welcome message and calculates basic math operations.

- [ ] **Day 7: User Input & Conditionals**
  * **Resource:** [W3Schools - Python If...Else](https://www.w3schools.com/python/python_conditions.asp)
  * **Task:** Ask the user for their age and output different messages based on the result.  
  * **Practice:** Build a "Power Level Calculator" that asks for a character's stats and outputs their tier (e.g., Planetary, Star, or Universe level).

- [ ] **Day 8: Loops (Doing things repeatedly)**
  * **Resource:** [Real Python - Python "while" Loops](https://realpython.com/python-while-loop/) & ["for" Loops](https://realpython.com/python-for-loop/)
  * **Task:** Write a loop that counts from 1 to 100.  
  * **Practice:** Create a simulated "gacha pull" loop. Have it loop 10 times and randomly print "3-star", "4-star", or "5-star".

- [ ] **Day 9: Data Structures (Lists & Dictionaries)**
  * **Resource:** [Python Official Tutorial - Data Structures](https://docs.python.org/3/tutorial/datastructures.html)
  * **Task:** Store multiple items in a single variable.  
  * **Practice:** Create a dictionary of 5 characters and their corresponding damage multipliers.

- [ ] **Day 10: Week 2 Mini-Project**
  * **Resource:** [GeeksforGeeks - Building a Console Game in Python](https://www.geeksforgeeks.org/text-based-adventure-game-in-python/)
  * **Task:** Build a Terminal-Based RPG Battle Simulator.  
  * **Requirements:** Use a `while` loop for the battle phase. Use `if` statements to check if HP hits 0. Use `input` to choose "Attack" or "Heal".

---

## 📅 Week 3: Databases & The Classic Backend (XAMPP & PHP)
**Goal:** Learn the standard SMK Telkom web stack (RDBMS and Server-Side Scripting).  
**Tools:** XAMPP (Apache & MySQL), VS Code

- [ ] **Day 11: Introduction to XAMPP & SQL**
  * **Resource:** [XAMPP Official Tutorials](https://www.apachefriends.org/faq_windows.html) & [w3schools - SQL Introduction](https://www.w3schools.com/sql/sql_intro.asp)
  * **Task:** Start Apache and MySQL in the XAMPP Control Panel. Open phpMyAdmin in the browser.  
  * **Practice:** Manually create a database named `inventory_db` and a table named `items`.

- [ ] **Day 12: SQL Queries**
  * **Resource:** [SQL Bolt - Interactive SQL Lessons 1-5](https://sqlbolt.com/)
  * **Task:** Use the SQL tab in phpMyAdmin.  
  * **Practice:** Insert 5 records into your `items` table. Write a query to select items that cost more than 1000 gold.

- [ ] **Day 13: Intro to PHP**
  * **Resource:** [PHP.net - Simple Tutorial](https://www.php.net/manual/en/tutorial.php)
  * **Task:** Create a file named `index.php` inside the `C:\xampp\htdocs` folder.  
  * **Practice:** Write a PHP script that prints dynamic HTML based on variables (e.g., printing the current date and time).

- [ ] **Day 14: Connecting PHP to MySQL**
  * **Resource:** [W3Schools - PHP MySQL Connect & Select](https://www.w3schools.com/php/php_mysql_select.asp)
  * **Task:** Connect your `index.php` file to the `inventory_db` you made on Day 11.  
  * **Practice:** Fetch the data from the `items` table and display it in an HTML `<table>` using a `while` loop.

- [ ] **Day 15: Week 3 Mini-Project**
  * **Resource:** [Traversy Media - PHP CRUD Guide](https://www.freecodecamp.org/news/php-crud-tutorial/)
  * **Task:** Build a functional CRUD Web App.  
  * **Requirements:** Create an HTML form that allows you to add a new item to the database, and a button to delete an item.

---

## 📅 Week 4: Modern JavaScript & APIs (NodeJS & Postman)
**Goal:** Separate the frontend from the backend by building RESTful APIs.  
**Tools:** Node.js, VS Code, Postman

- [ ] **Day 16: NodeJS Setup & NPM**
  * **Resource:** [Node.js Official Introduction Guide](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs)
  * **Task:** Install Node.js. Run `node -v` in the terminal to verify. Initialize a project using `npm init -y`.

- [ ] **Day 17: Introduction to Express.js**
  * **Resource:** [Express.js Official Guide - Hello World](https://expressjs.com/en/starter/hello-world.html)
  * **Task:** Install Express (`npm install express`).  
  * **Practice:** Create a simple server that listens on port 3000 and responds with "Hello World" when you visit `http://localhost:3000`.

- [ ] **Day 18: Building JSON Endpoints**
  * **Resource:** [MDN Web Docs - Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
  * **Task:** Instead of sending HTML, configure your Express server to send a JSON array of users.

- [ ] **Day 19: Testing APIs with Postman**
  * **Resource:** [Postman Learning Center - Sending Your First Request](https://learning.postman.com/docs/sending-requests/requests/)
  * **Task:** Install Postman.  
  * **Practice:** Create a `POST` route in Node.js. Use Postman to send JSON data to your server and log it in the terminal.

- [ ] **Day 20: Week 4 Mini-Project**
  * **Resource:** [LogRocket - Build a REST API with Node and Express](https://blog.logrocket.com/build-basic-api-node-js-express/)
  * **Task:** Build a "Player Stats" REST API.  
  * **Requirements:** Endpoints to get all players (`GET`), get one player by ID (`GET`), and create a new player (`POST`). Test entirely via Postman.

---

## 📅 Week 5: Enterprise Architecture (.NET)
**Goal:** Prepare for high-concurrency, professional-grade system development.  
**Tools:** Visual Studio Community, .NET SDK

- [ ] **Day 21: Visual Studio & C# Basics**
  * **Resource:** [Microsoft Learn - C# for Beginners Video Series](https://learn.microsoft.com/en-us/shows/csharp-fundamentals-for-beginners/)
  * **Task:** Install Visual Studio Community (select the .NET Desktop & Web development workloads).  
  * **Practice:** Create a new C# Console Application. Write a script using C# Classes and Objects.

- [ ] **Day 22: .NET Core Web API**
  * **Resource:** [Microsoft Learn - Create a Web API with ASP.NET Core](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/)
  * **Task:** Create a new ASP.NET Core Web API project.  
  * **Practice:** Explore the default `WeatherForecast` controller to understand how routing works in .NET.

- [ ] **Day 23: Controllers and Routing**
  * **Resource:** [Microsoft Learn - Routing in ASP.NET Core Controllers](https://learn.microsoft.com/en-us/aspnet/core/mvc/controllers/routing)
  * **Task:** Add a new Controller (e.g., `TransactionController`).  
  * **Practice:** Create endpoints that return hardcoded data models (e.g., an Account ID and Balance).

- [ ] **Day 24: High-Performance Concepts**
  * **Resource:** [Microsoft Learn - Asynchronous Programming with async and await](https://learn.microsoft.com/en-us/dotnet/csharp/asynchronous-programming/)
  * **Task:** Update your controller methods to be asynchronous.  
  * **Practice:** Add a simulated delay (`Task.Delay`) to understand how non-blocking requests handle multiple users simultaneously.

- [ ] **Day 25: Week 5 Mini-Project**
  * **Resource:** [Code Maze - ASP.NET Core Web API Tutorial](https://code-maze.com/net-core-series/)
  * **Task:** Build a Bank Transaction API prototype.  
  * **Requirements:** An endpoint to "Check Balance" and an endpoint to "Deposit Funds". Test the speed and responses using Postman.

---

## 📅 Week 6: Version Control, Java, & Deployment
**Goal:** Learn how professionals manage code, collaborate, and push to the live internet.  
**Tools:** Git, Netbeans (Java), FileZilla

- [ ] **Day 26: Introduction to Git**
  * **Resource:** [Git-SCM - Pro Git Book (Chapter 1 & 2 Basics)](https://git-scm.com/book/en/v2)
  * **Task:** Install Git. Run `git init` in one of your project folders.  
  * **Practice:** Use `git add .` and `git commit -m "Initial commit"` to save a snapshot of your code.

- [ ] **Day 27: GitHub & Remote Repositories**
  * **Resource:** [GitHub Docs - Adding Local Code to GitHub](https://docs.github.com/en/get-started/getting-started-with-git/adding-locally-hosted-code-to-github-using-git)
  * **Task:** Create a GitHub account. Create a new empty repository.  
  * **Practice:** Link your local Git repository to GitHub (`git remote add origin`) and push your code (`git push -u origin main`).

- [ ] **Day 28: Java Basics (Netbeans)**
  * **Resource:** [W3Schools - Java Tutorial](https://www.w3schools.com/java/)
  * **Task:** Install Netbeans and the Java JDK. Create a new Java project.  
  * **Practice:** Write a simple Java program that utilizes Classes, mimicking the logic you learned in C# / Python.

- [ ] **Day 29: Web Hosting & FileZilla**
  * **Resource:** [FileZilla Official Documentation - Usage Guide](https://wiki.filezilla-project.org/Using)
  * **Task:** Sign up for a free web host (like InfinityFree).  
  * **Practice:** Use FileZilla to connect to your host and upload the HTML/CSS/PHP files from Week 3 to the live internet.

- [ ] **Day 30: Final Review & Portfolio Setup**
  * **Resource:** [GitHub Guide - Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
  * **Task:** Create a `README.md` for your GitHub profile showcasing what you've learned.  
  * **Practice:** Pin your best projects (The Python Game, the PHP CRUD app, and the .NET API) to your GitHub homepage so your teachers at SMK Telkom can see your skills.
