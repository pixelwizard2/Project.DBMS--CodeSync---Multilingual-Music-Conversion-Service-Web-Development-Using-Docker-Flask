# Project.DBMS--CodeSync---Multilingual-Music-Conversion-Service-Web-Development-Using-Docker-Flask
Docker &amp; Flask를 활용한 다국어 음악 변환 서비스 웹 개발




**※ Development Period: January 3, 2024, to January 4, 2024**


## 1. Project Overview (프로젝트 개요)

"Melody Matrix" is a multilingual music conversion web service, built through containerization on a Docker base. This platform utilizes Visual Studio and a Flask app to enable users to easily convert songs produced in any language into their selected target language. This project serves as a bridge in global culture, offering a new dimension in language learning through music.


## 2. Project Goals: Building and Applying a Multimodal AI Language Conversion System (프로젝트 진행 목표)

The primary goal of this project is to combine advanced Python audio processing capabilities with Flask-based web development skills to construct a Docker-based web application and apply multimodal AI technology in a practical setting. Through this process, I aim to achieve the following:

**1. Enhanced Integration and Application Skills:** By integrating advanced audio processing and translation algorithms in Python with Flask-based web development, this project aims to improve the ability to apply multimodal AI technology in a web environment.

**2. Practical Application of Containerization Technology:** Utilizing Docker to containerize Python applications and integrate them with cloud-based web applications, this step will provide practical experience in modern application deployment and management.

**3. Establishing a Foundation for Professional IT Competence:** Implementing a real project using various programming languages, frameworks, and tools will lay the groundwork for becoming an IT professional and enhance competitiveness in this field.


## 3. Anticipated Project Outcomes (프로젝트 진행 예상 기대 효과)

This project respects the universal value and diversity of music and contributes to connecting various languages and cultures. The evaluation criteria include user feedback, service availability, and the accuracy and naturalness of music conversion. "Melody Matrix" is expected to provide a deeper musical experience for users and offer an innovative approach to language learning.


## 4. Technology Stack and Development Phases(기술 스택 및 개발 단계)

**(1) Voice Conversion Algorithm Development** **(Completed / December 30, 2023):**
[링크 첨부]

- Utilizing Python for audio data processing to accurately convert original language audio into target language audio.
- Using Python libraries such as librosa, SpeechRecognition, gTTS for efficient voice recognition and translation processing.
- Analyzing original audio data characteristics (e.g., pitch, intensity) and processing to harmonize with the converted voice.

(Reference files attached as a result of successfully converting a test song.mp3 file into an English.mp3 file, edited to include only the Korean voice parts, using Python on Google Colab.)




**(2) Docker Image Build and Deployment (Completed / December 31, 2023):**

- Writing a Dockerfile to set up the environment required for running the Python application.


- Using Docker Compose to orchestrate and manage multiple containers.
- Deploying the completed Docker image on Docker Hub, with version control and distribution.


**(3) Preparation Phase for Flask Web Application Development (Completed / January 3, 2024):**

- Building the frontend using Flask and HTML/CSS, including file upload forms on the web page and configuring the Flask server to receive files.
- Designing the web interface with HTML and CSS for user-friendly frontend development.
- Designing and implementing a RESTful API for data exchange with the frontend.




## 5. Challenges and Solutions During Development (진행 과정 중 문제 발생 해결 부분)

**(1) Integration of Docker Container and Flask Application:**

- Initially faced a "curl: command not found" error when trying to access localhost with curl command in the Docker container.
- Successfully sent requests to the Flask application using the Python code with the requests library.


**(2) Functionality Check of Web Page in Flask Application:**

- Confirmed the proper functioning of receiving and sending requests in the Flask application.
- Encountered an "ERR_EMPTY_RESPONSE" error in the browser after initially receiving responses like "Hello!" from the web page.


**(3) Firewall Settings and Various Attempts:**

- Adjusted firewall settings and added port 5000, but it did not resolve the issue.
- Attempted to configure the settings for running FFmpeg (an open-source multimedia framework) within the Docker virtual environment, but the web page still did not operate correctly.
- Modified the command to run the Flask web application, but the issue persisted.


Post-Project Evaluation:

The project encountered compatibility issues between the Python code and the Flask application, leading to errors on the web. This was a disappointing aspect as the Python code did not function smoothly on the web.

However, the project successfully achieved one of its main goals by properly integrating the Flask app with the Docker container. Excluding the compatibility issue with the existing code, the integration with the web was successful.

Future projects will prioritize reviewing the compatibility of libraries and frameworks used in the executable code for web integration. By considering these aspects in planning and execution, I aim to achieve better outcomes in future projects.

Future Project Development Plans:

Full-Stack Web Development:

Expanding backend functions using Flask for managing user file uploads and conversion processes.
Implementing an interactive web interface using Flask and Jinja templates for dynamic web page creation, and applying CSS frameworks for responsive design and usability enhancement.
Improving user interface: Applying UX design principles for a responsive web design that is easy to use on both mobile and desktop environments.
Service Expansion and Optimization:

Cloud Hosting: Hosting and managing the web application through cloud services (e.g., AWS, Google Cloud).
Security Protocols: Implementing security protocols like HTTPS to protect user data.
Performance Monitoring: Applying tools to monitor and optimize the performance of the web application.
