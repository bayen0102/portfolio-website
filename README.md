# Personal Portfolio Website

A personal portfolio website built with Flask to showcase my background, education, technical skills, professional experience, and software engineering projects.

Live Website: [View My Portfolio](https://mywebsite-lac-three.vercel.app)

## About the Project

This portfolio provides a centralized place to learn more about my background in Computer Science and Informatics and explore the projects and technical experience I have developed throughout my academic journey.

The website uses Flask for backend routing and HTML, CSS, and JavaScript for the frontend. It is deployed on Vercel and includes dedicated pages for my education, experience, skills, background, projects, and resume.

## Features

- Personal introduction and background
- Education history
- Professional experience
- Technical skills
- Software engineering project showcase
- Downloadable resume
- Multi-page Flask routing
- Responsive frontend interface
- Live deployment with Vercel

## Tech Stack

**Backend**
- Python
- Flask

**Frontend**
- HTML
- CSS
- JavaScript

**Deployment & Tools**
- Vercel
- Git
- GitHub

## Project Structure

```text
mywebsite/
├── static/
│   ├── icons/
│   ├── images/
│   ├── script.js
│   ├── style.css
│   └── Bay_En_Wang_Resume_CS-2.pdf
│
├── templates/
│   ├── background.html
│   ├── base.html
│   ├── education.html
│   ├── experience.html
│   ├── index.html
│   ├── login.html
│   ├── profile.html
│   ├── projects.html
│   └── skills.html
│
├── app.py
├── requirements.txt
├── users.json
├── .gitignore
└── README.md
```

## Application Routes

| Route | Description |
|---|---|
| `/` | Home page |
| `/experience` | Professional experience |
| `/education` | Education background |
| `/skills` | Technical skills |
| `/background` | Personal and academic background |
| `/projects` | Software engineering projects |
| `/resume` | Downloadable resume |

## Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/bayen0102/mywebsite.git
cd mywebsite
```

### 2. Create a virtual environment

```bash
python3 -m venv venv
```

### 3. Activate the virtual environment

macOS/Linux:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask application

```bash
python app.py
```

Then open the local address displayed in the terminal.

## What I Learned

Building this portfolio gave me practical experience with:

- Developing a web application with Flask
- Creating and managing backend routes
- Connecting Flask routes with HTML templates
- Structuring reusable HTML templates
- Building frontend interfaces with HTML, CSS, and JavaScript
- Managing static assets and project resources
- Using Git and GitHub for version control
- Deploying a Python web application online

## Future Improvements

- Improve mobile responsiveness
- Expand individual project case studies
- Improve accessibility
- Optimize frontend performance
- Add more interactive project demonstrations
- Continue updating the portfolio with new projects and experience

## Author

**Bay Wang**

B.S. Computer Science  
University of California, Santa Cruz

M.S. Informatics  
San José State University

GitHub: [bayen0102](https://github.com/bayen0102)

