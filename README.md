Hugo School Task Project
This is a Hugo-based static website project designed to manage and display information about students and teachers. The site uses Hugo templates and YAML data files to render dynamic pages for student and teacher details.
Overview

Purpose: A simple web application to list and view student and teacher profiles.
Technology: Built with Hugo, a fast and flexible static site generator.
Data Source: Student and teacher data is stored in data/students.yaml and data/teachers.yaml.
Hosted on: GitHub at https://github.com/dhengareharry/hugo_school_task.

Prerequisites

Git installed.
Hugo installed (version 0.148.2 or later recommended).
A code editor (e.g., VS Code).

Installation

Clone the repository:
git clone https://github.com/dhengareharry/hugo_school_task.git
cd hugo_school_task


Install Hugo (if not already installed):

Follow Hugo’s installation guide for your operating system.



Usage

Start the Hugo development server:
hugo server -D


The -D flag includes draft content if any.
Visit http://localhost:1313/ in your browser to see the site.


Explore the site:

Navigate to /students/ to view the student list.
Click a student (e.g., /students/student-1/) to see individual details.
Navigate to /teachers/ for the teacher list and individual pages.


Build the site (optional):
hugo


This generates static files in the public/ directory, which can be deployed to a web server.



Project Structure

content/: Markdown files for pages (e.g., students/student-1.md).
data/: YAML files (students.yaml, teachers.yaml) containing data.
layouts/: Hugo templates for rendering pages.
hugo.toml: Configuration file.
.gitignore: Excludes build artifacts like public/.

Contributing

Fork the repository.
Create a feature branch (git checkout -b feature-branch).
Commit changes (git commit -m "Add new feature").
Push to the branch (git push origin feature-branch).
Open a Pull Request on GitHub.

License
This project is open-source. Feel free to use and modify it under the MIT License (add a LICENSE file if desired).
Acknowledgments

Built with Hugo.
Thanks to the Hugo community for documentation and support.
