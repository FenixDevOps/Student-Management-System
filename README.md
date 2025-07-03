# Student Management System

## Overview

The **Student Management System** is a simple console-based Python application designed to manage a list of students. It allows users to view, add, search, and remove student names from a database stored in memory. This project demonstrates basic Python programming concepts, including list manipulation, user input handling, and exception handling, making it a great addition to my portfolio showcasing my Python skills.

Developed by **Bathini Manikanta**, a Software Engineering student at Malla Reddy Engineering College, this project is part of my portfolio website hosted at fenixdevops.github.io/portfolio.

## Features

- **View Students**: Display the current list of students.
- **Add New Student**: Append a new student name to the list, with validation to prevent duplicates.
- **Search Student**: Check if a student exists in the list.
- **Remove Student**: Delete a student from the list if they exist.
- **Run Again Option**: Allows users to rerun the program or exit with a goodbye message.
- **Cross-Platform Support**: Clears the console screen based on the operating system (Windows or others).

## Technologies Used

- **Python**: Core programming language for the application.
- **Modules**: `os` (for clearing the console), `platform` (for detecting the operating system).

## Prerequisites

- **Python 3.x**: Ensure Python is installed on your system. Download from python.org if needed.
- **Windows** (or another OS): The script includes console-clearing logic for Windows (`cls`) and other systems (`clear`).

## Setup Instructions

1. **Clone the Repository**:

   - Clone the portfolio repository to your local machine:

     ```bash
     git clone https://github.com/FenixDevOps/Student-Management-System
     ```
   - Navigate to the repository folder:

     ```bash
     cd Student-Management-System
     ```

2. **Add the Student Management System Script**:

   - Save the Python script as `student_management.py` in a subfolder (e.g., `projects/student_management/`).
   - Suggested directory structure:

   
    student_management/
      └── student_management.py
    

3. **Verify Python Installation**:

   - Open Command Prompt (Windows) and check Python version:

     ```bash
     python --version
     ```
   - If Python is not installed, download and install it from python.org.

## Usage

1. **Run the Script**:

   - Navigate to the script’s folder:

     ```bash
     cd projects/student_management
     ```
   - Execute the script:

     ```bash
     python student_management.py
     ```

2. **Interact with the Program**:

   - The program displays a menu:

     ```
     ------------------------------------------------------
     |======================================================|
     |======== Welcome To Student Management System ========|
     |======================================================|
     ------------------------------------------------------
     Enter 1 : To View Student's List
     Enter 2 : To Add New Student
     Enter 3 : To Search Student
     Enter 4 : To Remove Student
     ```
   - Enter a number (1–4) to select an option:
     - **1**: View the list of students (e.g., `yugesh`, `kishor`, `gajen`, `Gopi`).
     - **2**: Add a new student name (duplicates are prevented).
     - **3**: Search for a student by name.
     - **4**: Remove a student by name.
   - After each action, the program asks if you want to run again (`Y/n`).
   - To exit, enter `n` to see the goodbye message:

     ```
     ##############################
     # =========================== #
     # ===> Brought To You By <===  #
     # ===> code-projects.org <===  #
     # =========================== #
     ##############################
     ```

## Adding to GitHub

To include this project in your portfolio repository (`https://github.com/FenixDevOps/portfolio.git`):

1. **Ensure Correct Repository**:

   - Verify you’re in the `portfolio` folder, not `real_time_project_II-II` (used for Copy Catcher):

     ```bash
     cd C:\Users\manikanta\OneDrive\Desktop\portfolio
     ```
   - Check the remote URL:

     ```bash
     git remote -v
     ```
     - Should show:

       ```
       origin  https://github.com/FenixDevOps/portfolio.git (fetch)
       origin  https://github.com/FenixDevOps/portfolio.git (push)
       ```
     - If incorrect, update it:

       ```bash
       git remote set-url origin https://github.com/FenixDevOps/portfolio.git
       ```

2. **Add the Script**:

   - Create the `projects/student_management/` folder:

     ```bash
     mkdir projects\student_management
     ```
   - Save the script as `projects/student_management/student_management.py`.
   - Add a `.gitignore` to exclude unnecessary files:

     ```bash
     echo "node_modules/\n*.log\n*.tmp\n.env" > .gitignore
     ```

3. **Commit and Push**:

   - Add all files:

     ```bash
     git add .
     ```
   - Commit changes:

     ```bash
     git commit -m "Add Student Management System to portfolio"
     ```
   - Pull remote changes to avoid conflicts (addressing your previous error):

     ```bash
     git pull origin main
     ```
     - If conflicts occur, resolve them in `index.html` or other files (e.g., keep your updated `index.html` from artifact ID `284fffe6-d47d-4c08-a567-181466c3ed6d`), then:

       ```bash
       git add .
       git commit -m "Resolve conflicts for Student Management System"
       ```
   - Push to GitHub:

     ```bash
     git push -u origin main
     ```
   - Use your GitHub username (`FenixDevOps`) and a Personal Access Token (PAT) from `https://github.com/settings/tokens` (with `repo` scope) for authentication.

4. **Update Portfolio Website**:

   - Add the Student Management System to the Projects section in `index.html`. Example update:

     ```html
     <div class="project-card p-6 rounded-xl animate-project">
       <img src="https://images.unsplash.com/photo-1516321497487-e288fb19713f?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Student Management System" class="w-full h-48 object-cover rounded-lg mb-4 animate-project-img">
       <h3 class="text-xl font-semibold mb-2 text-cyan-400 animate-project-title">Student Management System</h3>
       <p class="text-sm animate-project-text">A console-based Python application for managing student records with view, add, search, and remove functionalities. Built with Python, os, and platform modules.</p>
       <a href="https://github.com/FenixDevOps/portfolio/tree/main/projects/student_management" class="text-blue-400 hover:underline animate-project-link">View Project</a>
     </div>
     ```
   - Add this to the `<div class="grid grid-cols-1 md:grid-cols-3 gap-6">` in the Projects section, replacing one of the existing cards or expanding the grid.
   - Commit and push the updated `index.html`:

     ```bash
     git add index.html
     git commit -m "Add Student Management System to portfolio website"
     git push -u origin main
     ```

5. **Verify on GitHub Pages**:

   - Ensure GitHub Pages is enabled for the `main` branch (`/ (root)` folder) at `https://github.com/FenixDevOps/portfolio/settings/pages`.
   - Visit `https://fenixdevops.github.io/portfolio/` to confirm the portfolio displays correctly, including the new project (if added to `index.html`).

## About the Developer

I’m **Bathini Manikanta**, a Software Engineering student at Malla Reddy Engineering College, passionate about AI, web development, and innovative solutions. My portfolio includes projects like SimpleCalculator, Copy Catcher, and this Student Management System, showcasing my skills in Python, HTML, CSS, JavaScript, Java, and SQL. Connect with me on:

- LinkedIn
- GitHub
- Instagram

Visit my portfolio: fenixdevops.github.io/portfolio

## Acknowledgments

- Inspired by code-projects.org, as noted in the script’s goodbye message.
- Built as part of my portfolio to demonstrate Python programming proficiency.
