# Flask Web Development Project: Create and Test a Resume API Endpoint

Welcome to this Flask web development project. We'll be utilizing Python, Flask, Pytest, and JSON to create a simple Flask application that serves your resume as a JSON response.
## Required Educational Videos

* [Instructor Video](https://youtu.be/wb_Oa6VEOnI)

To help understand the fundamental concepts involved, watch these hand-picked videos:

1. [JSON in 1 minute](https://www.youtube.com/watch?v=7mj-p1Os6QA)
2. [Flask Quick App with Network Chuck](https://www.youtube.com/watch?v=5aYpkLfkgRE)
3. [Introduction to REST API](https://www.youtube.com/watch?v=lsMQRaeKNDk)
4. [Understanding PyTest and Unit Testing Overall](https://www.youtube.com/watch?v=UMgxJvozR5A)
5. [GitHub Action with CI/CD](https://www.youtube.com/watch?v=mFFXuXjVgkU)

## Readings
- [Python, Virtual Enviroments, Flask, Pip, and PyTest](python.md)
- [ChatGPT Prompts](chatgpt.md)

### General Help
* VSCode - [here](https://youtu.be/B-s71n0dHUk)
* VSCode /w Git & GitHub - [here](https://www.youtube.com/watch?v=i_23KUAEtUM)* Node.JS Introduction - [here](https://www.youtube.com/watch?v=JZXQ455OT3A)
* SETTING UP SSH KEYS SO YOU CAN CONNECT VSCode to GitHub - [here - Windows ONLY](https://www.youtube.com/watch?v=a-zX_qc2S-M)
* SETTIG UP SSH KEYS SO YOU CAN CONNECT VSCode to GitHub - [here - MacOS Only](https://www.youtube.com/watch?v=cGcpVQlhbuI)
* GIT &  GitHub Playlist - [here](https://www.youtube.com/watch?v=6KoBsJfYBPM&list=PL0Zuz27SZ-6PkWWk_mA2vkimUTJf81mNz)
#### Optional YouTube - At least watch these if you know all the stuff above.
* VS Code Top Extensions - [here](https://youtu.be/xQcpQfEumQw)
* Browser Dev Tools Tips and Tricks - [here](https://www.youtube.com/watch?v=TcTSqhpm80Y)



## Learning Objectives

By the end of this project, you should be able to:

1. **Understand Web Frameworks**: Learn how Flask, a lightweight web framework for Python, handles routing and responses.
2. **Work with JSON**: Learn to write and format JSON, a key data interchange format in web development. You'll encode your resume into a JSON file.
3. **Improve Python Development Practices**: Enhance your Python skills in web development context, using virtual environments and pip, Python's package installer.
4. **Use Test Frameworks**: Understand the importance of testing in software development and learn to write and run tests using Pytest, a popular Python testing framework.
5. **Understand Web Server Operation**: Learn how a web server works, from serving static files to handling routes.
6. **Practice Version Control with Git**: Use Git for version control, from cloning a repository to making and pushing changes.
7. **Understand Continuous Integration/Continuous Deployment (CI/CD)**: Get an introduction to CI/CD concepts through GitHub Actions.
8. **Organize and Execute a Project**: Practice project organization, manage dependencies, and follow instructions to meet project objectives.


## Project Steps

### Step 0: Setup the Application

1. **Clone the repository**: After accepting the assignment, clone the repository to your local machine.  **MAKE SURE YOU HAVE SSH KEYS SETUP SEE THE VIDEOS BELOW**
2. **Create a virtual environment**: Use `python3 -m venv venv` to create a virtual environment in the project directory.
3. **Activate the virtual environment**: Use `source venv/bin/activate` (Unix/macOS) or `venv\Scripts\activate` (Windows).
4. **Install necessary packages**: Use `pip install -r requirements.txt`.
5. **Run the application**: Use `flask run` and visit `http://localhost:5000/` on your browser.

### Step 1: Creating Your Resume

1. Navigate to `application/static/` and open `resume.json`.
2. Fill in your details in the respective fields, ensuring to maintain correct JSON format.
3. Refer to the [example.json](example.json) for guidance, but remember JSON does not support comments.

### Step 2: Understand the Flask Application

The application serves two routes:

- The root URL ("/"): Returns a "Hello, World!" message.
- The "/static/resume.json" URL: Serves your `resume.json` file from the `static` directory.  (IT WON't SHOW ANYTHING TILL YOU CODE YOUR RESUME INTO JSON IN THE FILE)

### Step 3: Test Your Application with Pytest

Testing is crucial in web development. For this project, we will use Pytest to ensure your `resume.json` is being served correctly. Run the predefined tests in the `tests` directory by using `pytest` in your terminal.
