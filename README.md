# F1-101

A comprehensive and interactive web application designed to introduce new and existing fans to the exciting world of Formula 1. This project aims to simplify complex F1 concepts, showcase key elements like teams, drivers, and circuits, and provide accessible race data in a user-friendly interface.

✨ Features
Dynamic Content Loading: Data for Teams, Drivers, and Circuits is fetched from JSON files and dynamically rendered into interactive cards.

F1 Basics Explained: A dedicated section breaking down fundamental F1 concepts, race weekend formats, and strategic elements.

Key Terminology Glossary: An easy-to-understand list of essential F1 terms.

Interactive Team & Driver Cards: Hover effects reveal detailed information for each team and driver.

Interactive Circuit Details: Clickable circuit cards display an enlarged map and key statistics in a pop-up overlay.

F1 Car Hotspots: Hover over different parts of an F1 car image to reveal tooltips with information about various components.

Example Race Events Data: A simplified section displaying a static table of sample race events.

Custom F1 Theming: A dark, sleek design with F1-inspired typography and color accents.

🛠️ Setup and Installation
This project is designed for easy access and demonstration.

🌐 Live Demo (Recommended)
The application is hosted on GitHub Pages and can be accessed directly via this link:
https://muzkageno.github.io/F1-101/

🖥️ Local Setup
If you wish to run the project locally or contribute to its development:

Clone the repository:

git clone https://github.com/muzkageno/F1-101.git
cd F1-101

Open index.html:
Simply open the index.html file in your preferred web browser (e.g., Chrome, Firefox, Edge).

# Example for Linux/macOS
open index.html
# Example for Windows
start index.html

Alternatively, for a better development experience, you can use a local web server like the "Live Server" extension in VS Code.

⚙️Technologies Used
HTML5: For structuring the web content.

CSS3: Custom styling and responsive design.

Tailwind CSS: A utility-first CSS framework for rapid UI development.

JavaScript (ES6+): For dynamic content loading and interactivity.

Google Fonts: Orbitron for F1-style headings and Inter for body text.


🗂️ Project Structure
F1-101/
├── index.html           # main SPA
├── teams.json           # team data
├── drivers.json         # driver data
├── circuits.json        # circuit data
├── race_events.json     # sample session data
├── images/              # all static images
│   ├── max-verstappen.jpg
│   ├── red-bull-logo.png
│   ├── monaco-circuit.png
│   └── ...
└── README.md

Note: All images live flat inside /images.  Paths in JSON/HTML follow images/<filename>

💡 Usage
Teams & Drivers: Hover over the cards to reveal detailed information.

Circuits: Click on a circuit card to open a detailed overlay with map and statistics.

F1 Car: Hover over the red circles on the F1 car image to see tooltips explaining different parts.

Race Data: The "Example Race Events" section will automatically display sample race data in a table.


📊 Data Sources
All data for teams, drivers, circuits, and race events is currently stored in static JSON files (teams.json, drivers.json, circuits.json, race_events.json) within the project directory.

DEMO (Screen Shots)
<img width="1894" height="955" alt="image" src="https://github.com/user-attachments/assets/2aface48-487b-4350-b672-e6ea1149da8e" />
<img width="1893" height="942" alt="image" src="https://github.com/user-attachments/assets/a4cfedd7-6677-40fe-a9a4-9c87d81e01e0" />
<img width="1883" height="949" alt="image" src="https://github.com/user-attachments/assets/125cbe1a-26fe-4765-bc81-081d70942195" />
<img width="1884" height="951" alt="image" src="https://github.com/user-attachments/assets/517f27b9-104f-4521-8823-fc95a99a4a71" />
<img width="1372" height="951" alt="image" src="https://github.com/user-attachments/assets/b94dc07d-f0a8-4126-87cf-d95fff7d7cb3" />
<img width="1349" height="945" alt="image" src="https://github.com/user-attachments/assets/7da0eb0a-4f32-46af-a6df-d83a117fc692" />
<img width="1274" height="947" alt="image" src="https://github.com/user-attachments/assets/420adc5d-6834-4b6f-8ebe-5a22dacf048c" />
<img width="1290" height="953" alt="image" src="https://github.com/user-attachments/assets/01c417fa-0bfd-4484-b1b0-221f488a40d6" />
<img width="1332" height="944" alt="image" src="https://github.com/user-attachments/assets/f0a064ea-ca69-4c78-b7bd-9c8bbceaa046" />
<img width="1332" height="946" alt="image" src="https://github.com/user-attachments/assets/81c8102b-b2d9-4401-9192-19321a8563a2" />
<img width="1313" height="948" alt="image" src="https://github.com/user-attachments/assets/89cfe46f-722b-42e2-9407-82c58493d881" />



Copyright 2025 Muhammad Muzaffar Shaik

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

