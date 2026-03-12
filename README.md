# Drishyamitra-AI-Powered-Photo-Management-System

Request Team Lead to Add Demo and GitHub links!

Please request your team lead to update the demo and GitHub links so that your mentor can review and evaluate your project.

Entertainment
group
Drishyamitra is an AI-powered photo management system designed to bring intelligence and automation to how users organize, search, and share their memories. Unlike traditional photo galleries that rely on manual sorting, Drishyamitra uses deep learning–based facial recognition and natural language understanding to create an intuitive and efficient photo experience. Whether it’s identifying people in images, organizing them into smart folders, or delivering them across platforms, the system ensures seamless photo handling with minimal human effort.

At its core, Drishyamitra integrates advanced computer vision models such as DeepFace (Facenet512, RetinaFace, and MTCNN) to achieve highly accurate face detection and recognition. Once photos are uploaded, the system automatically detects and labels familiar faces while prompting users to name new ones. This automation leads to intelligent organization grouping photos into person-specific folders, maintaining a clean hierarchy, and enabling quick retrieval through tags or voice-like queries. The combination of AI-driven recognition and structured folder management makes Drishyamitra both powerful and user-friendly. Beyond recognition, Drishyamitra incorporates a conversational AI chatbot assistant that enables natural interaction with your photo collection. Users can simply ask, “Show me photos of Priya from last month,” or “Send John’s pictures to WhatsApp,” and the system interprets and executes the task using Groq-powered natural language processing. This multimodal interaction turns photo management into an intelligent dialogue, extending functionality beyond search into smart actions like automated sharing, batch delivery, and history tracking. Built with a modern full-stack architecture, Drishyamitra uses Flask for its backend, React.js for its frontend, and APIs for seamless integration with email and WhatsApp. Its secure, scalable design ensures private data handling, token-based authentication, and encrypted face data storage. Drishyamitra is more than a gallery it’s a personalized photo companion that combines AI, automation, and communication to redefine how users manage and interact with their digital memories.

Scenario 1: Family Photo Organization & Memory Management

Riya, a working professional, has over 15,000 photos collected from years of vacations, family events, and celebrations. Her photo collection is spread across her phone, Google Drive, and an old laptop, making it nearly impossible to find specific pictures quickly. After setting up Drishyamitra, she uploads her entire photo library through the web interface. The system automatically scans every image, detects faces, and recognizes family members she’s labeled before like “Mom,” “Dad,” “Ananya,” and “Grandma.” New faces are flagged for labeling, allowing Riya to tag relatives or friends once, after which Drishyamitra learns and remembers them for future uploads. The system then organizes all photos into neatly labeled folders, like “Family Trips,” “Weddings,” or “Festivals.” Later, when Riya wants to reminisce, she simply types or says, “Show me photos of Grandma from Diwali 2022,” and within seconds, the AI retrieves exactly those photos. She can even ask, “Email Mom her birthday photos from last year,” and the chatbot automatically attaches and sends them via Gmail. What once took hours now happens effortlessly transforming Riya’s digital chaos into an intelligent, organized memory archive.

Scenario 2: Event Photographer Workflow Automation

Aarav, a wedding and event photographer, deals with thousands of photos after every event. Sorting, tagging, and delivering photos to clients often takes days. By integrating Drishyamitra into his post-production workflow, Aarav automates most of this process. Once the event photos are uploaded, Drishyamitra detects all faces and identifies recurring individuals (like the couple, families, and guests). It groups photos automatically for example, “Bride & Groom,” “Family Group,” “Candid Moments,” and more. Aarav can label key people once, and the system remembers them for all future shoots, improving with each upload. Through the built-in chatbot, he can simply command, “Show me all photos of the couple during the ceremony,” or “Send family group photos to client@example.com.” The system fetches and delivers them instantly via email or WhatsApp. Delivery confirmations and history are stored automatically, ensuring a professional workflow with zero manual sorting. This saves Aarav hours of effort and allows him to focus on editing and creativity instead of logistics.

Scenario 3: Corporate Media Management & Collaboration

At a digital marketing agency, the creative team handles thousands of images for different campaigns and clients. These include event photos, product launches, and press coverage. Over time, managing and retrieving these visuals becomes a challenge, especially when multiple teams are involved. The company deploys Drishyamitra as its central AI-powered media management platform. Whenever team members upload campaign photos, the system automatically detects people, identifies employees, clients, and public figures, and organizes them into structured folders like “Client A Launch 2024,” “Team Events,” or “Brand Photoshoots.” When the marketing lead, Neha, needs visuals for a quarterly report, she doesn’t dig through shared drives. Instead, she asks the chatbot, “Find all photos of Rohan and Priya from the Client A launch event,” and Drishyamitra instantly retrieves them. She can then say, “Email them to our PR team,” and the AI handles it seamlessly. The delivery is logged automatically for compliance and tracking. This automation not only saves time but also enhances collaboration, security, and brand consistency across projects making Drishyamitra an indispensable tool for modern media teams.

Skills Required
Python
Node.js
SQLite
PostgreSQL
Artificial Intelligence
Agentic AI Architecture & Design
Mentor
No mentor assigned yet

Team Members
H
Harshit Jain

member

O
Ojasvi Rastogi

teamLead

P
Prashant Kumar

member

H
Himanshi Verma

member

Project Stats
 Epics
Total Epics: 8

 Stories & Subtasks
Total Tasks: 28

Total Subtasks: 0

Technical Architecture
Technical Architecture
Instructions
Environment Setup: Create a Python 3.8+ virtual environment for the Flask backend and install Node.js 16+ for the React frontend.

Dependency Management: Install backend requirements using pip install -r requirements.txt and frontend packages via npm install.

Configuration: Create .env files in both directories to securely store API keys for Groq, Gmail, and database URLs.

Database Initialization: Configure SQLite or PostgreSQL and initialize the schema using SQLAlchemy’s Base.metadata.create_all().

AI Integration: Integrate DeepFace models (Facenet512, RetinaFace) for recognition and Groq API for the conversational chatbot.

Service Setup: Authenticate Gmail via OAuth 2.0 or App Passwords and connect the WhatsApp Web API for photo delivery.

Backend Launch: Start the Flask server using python start_server.py to enable RESTful API endpoints at port 5000.

Frontend Launch: Run the React development server using npm start to access the user interface at port 3000.

Testing: Conduct unit and integration tests for face labeling, chat flow validation, and secure delivery tracking.

Production Deployment: Containerize the application using Docker Compose, configure a reverse proxy using Nginx, and deploy on a cloud provider like AWS or DigitalOcean.
