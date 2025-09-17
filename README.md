# inft6900_uon_itproject
This repo is for the final project of INFT6900 IT project at the University of Newcastle. The backend is carried out by Arnab and Ahsan. 

Project Statement
Overview of idea
This project designs, develops, and deploys a web application that helps the University of
Newcastle students to learn the introductory Mandarin Chinese language. The core idea is to build
a platform that teaches Mandarin vocabulary through an immersive multimedia approach. The
platform presents 25 of the most used and common Mandarin words, with their Chinese characters,
Pinyin (the standard system of Romanized spelling for transliterating Chinese), and a unique short
video of a native speaker from our team using the word in a clear, simple context. (Park, 2014)
The project will also be a functional academic prototype of full stack development, database
management, and storyboarding and will utilize our team management strengths.
The Project
The University of Newcastle has a significant number of Mandarin-speaking students. Also, many
non-Mandarin speakers are interested in learning this widely spoken language (CGTN, 2024). This
project addresses the opportunity for cultural exchange and basic language acquisition by
providing the students and staff with a simple and authentic learning tool. It goes beyond a scale
flashcard by introducing real video from the native Mandarin speakers, which is essential to
learning tone and context in a tonal language like Mandarin.
Some giant platforms like Duolingo and Memrise offer Mandarin courses. But they use generic,
computer-generated audio and imagery (Duolingo, 2025). Our application's key differentiator is
that it uses authentic, peer-created video content, making the learning experience more relatable
and engaging for the UoN community. It is built as a customizable academic project rather than a
commercial product.
The primary audience is UoN students (both domestic and international) and staff with no prior
knowledge of Mandarin who wish to learn basic vocabulary.
Ethical impacts and considerations:
Data Privacy and Security: User data such as email and password (hash function) will be stored.
We commit to make sure of the data minimization and industry standard hashing to ensure the
safety and security.
Data Sensitivity: Since the content includes language and culture, the videos and translations will
be selected and verified by our native Mandarin speakers to avoid any misrepresentation.
Copyright: All our content (videos and audios) will be created originally by our native Mandarin
speakers, making sure we own the copyright and avoid any copyright issues.
INFT6900 Group4 A2 3
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
Age Restrictions: Since this application is designed for the UON students and staff only, there is
no age restriction on using this service.
Project Goal and Objectives
The overall goal of this project is to design, develop, and deploy a fully functional web application
by following a structured software development life cycle. This process includes planning,
analysis, design, implementation, testing, deployment, and maintenance phases resulting in a web
application. This web application teaches Mandarin through videos and audios. The web
application must be user friendly for the UoN students and staff.
Objectives:
1. Planning And Requirement Analysis
• To define and document functional and non-functional requirements conducting a
team meeting and brainstorming sessions and an analysis of similar platforms like
Duolingo, Memrise and finally documenting them in this scoping document.
• To choose and use an Agile-Scrum methodology, using 1week long sprints tracked
using a Trello Kanban board.
• To create a realistic project plan using a Gantt chart with milestones aligned to
university weeks and deadlines.
2. System Design
• To design an Entity Relationship Diagram on lucidchart and a normalized relational
database schema to efficiently store user data, word entries, multimedia links, and
test results.
• To implement a SQL database that contains 25 mandarin words, their English
translations, Pinyin, and links to the videos and audios files.
• To develop an authentication system (login, logout, create an account) to track
users' activity with full stack development.
• To develop a frond-end web application that displays each word with its character,
Pinyin, mp3 audio player, and video player showing our team member pronouncing
the word.
• To implement a search function which allows users to find the words they are
looking for.
• To create an administration panel allowing admins to perform CRUD (CREATE,
READ, UPDATE, DELETE) operations on the database.
• To design a storyboard for the entire UI for all key user interfaces making sure the
overall system is user and admin friendly.
• To implement MFA (Multi Factor Authentication) for the registration process to
protect the system from the scammers by using users email and six-digit OTP (One
time password).
INFT6900 Group4 A2 4
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
3. Implementation (Development)
• To develop an interactive front-end for the application using HTML5, CSS
(Bootstrap), and JavaScript.
• To implement a smooth back-end using Java 8, Spring boot framework.
• To produce multimedia contents (Videos, audios)
• To implement the database using MySQL.
4. Testing
• To perform individual component testing to make sure the correctness of code.
• To perform user acceptance testing (UAT) with a small group of peers and gather
feedback on usability and functionality.
5. Deployment
• To deploy the application initially on a local host by packaging the application in a
JAR file. In future there might be a possibility of deploying the application on
cloud.
6. Maintenance
• To maintain the code clean and well-commented and ensure the proper
documentation (API docs, setup guides) in the GitHub wiki of the project.
Project Scope
Project boundaries
System Scope: This project focuses on a web-based Chinese language learning platform. It
contains user registration and authentication, vocabulary learning, vocabulary search and CRUD
operations. This project also shows team management skills.
Target Users: The primary audience is UoN students (both domestic and international) and staff
with no prior knowledge of Mandarin who wish to learn basic vocabulary.
Data Scope: In the database there are 25 vocabularies, Chinese characters, pinyin, English
translation, audio and video links.
Technical Scope:
Backend: For backend Java 8 is used as the primary programming language on a Spring boot
Framework. Also, Spring Security (authentication), Spring Data JPA (database interaction).
Frontend: HTML5, CSS3 and JavaScript.
Database: MySQL 8.
Development Tools: IDE (Spring Tool Suite/IntelliJ Idea), GitHub (version control), Trello (task
management), Figma (UI layout design), Lucidchart(Flow design).
Testing Tools: Google Chrome DevTools (frontend debugging).
INFT6900 Group4 A2 5
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
What is to be completed
1. Submit the Scoping document, conduct weekly meeting, track Trello progress and issue
logs
2. Storyboarding, design the workflow.
3. The use cases, user stories and acceptance criteria.
4. Selecting 25 common Mandarin vocabulary.
5. Entity Relationship Diagram, Database, Data.
6. Backend: The registration process, login and logout, CRUD operations.
7. Frontend pages: Vocabulary browsing, search, audio or video playback, and admin panel.
8. Video and audio recording.
9. Test plan and bug reports to ensure there are no major defects.
10. User Acceptance Testing (UAT).
Final Deliverables
1. A functional Chinese learning website (demo).
2. Project documentation: User and administrator guide, deployment guide and release notes.
3. Diagrams (ER, Use case)
4. Storyboard, Workflow
5. Trello log
6. Database and Schema
7. Code (both front end and backend)
8. A demonstration video and
9. The final project package.
Project Management:
•Team members and their roles
Name Role Relevant Skills Responsibilities Core Deliverables
Ahsanul
Haqu
Software
Engineer
-- Backend
Developer
Strong in
Java/Python,
database
connectivity,
and unit testing.
1. Design and
implement APIs
(search, CRUD,
authentication);
implement difficulty
level system.
2. integrate with the
database.
1. Authentication and
authorization
module
2. backend test cases
INFT6900 Group4 A2 6
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
3. perform basic unit
and integration
testing.
Arnab Kar Software
Engineer
-- Backend
Developer
Skilled in Java,
Spring Boot,
MySQL
1. Build web UI
(Vocabulary with
Pinyin, audio, video,
Admin panel).
2. Integrate API and
multimedia player.
3. Assist Ahsanul
Haque with the back
end.
1. Homepage and entry
detail page.
2. Admin panel.
3. Vocabulary search
and management
API
Di Hao Project
Manager
Organizational
skills;
experience in
project
planning,
documentation,
and QA
coordination.
1. Project schedule
management.
2. Meeting organization
and communication.
3. Risk and issue
tracking.
4. QA and
Documentation
coordination
1. Team action plan
and Meeting.
2. Project plan and risk
register.
3. test plan and
summary;
deployment guide
4. User and
Administrator User
Guide
5. packaging and
naming conventions
for deliverables
Thi Thu
Trang Pham
Database
Engineer
Background in
SQL;
experience with
normalization
and query.
1. Design an ERR and
SQL database with
25 Mandarin words.
2. Create seed data and
indexing for search.
3. Support the backend
with queries.
1. ER diagram.
2. DDL script.
3. SQL.
4. index and constraint
schema.
5. data access
documentation
Hefei Sun User
Interface,
Storyboard
Knowledge of
UX design;
experience in
Figma,
storyboarding,
frontend
framework
1. Build web UI
(Vocabulary with
Pinyin, audio, video,
Admin panel).
2. Design wireframes,
storyboards, and user
flows (Vocabulary,
Admin pages).
3. Build style guide and
ensure responsive,
accessible UI.
4. frontend workflow
5. Low or medium
fidelity prototypes
(using Figma).
6. user flow diagrams.
style guide.
accessibility
checklist
INFT6900 Group4 A2 7
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
•Timetable (Gantt chart)
Fig: Gantt chart
•Time and Task management
Project milestones
Milestone Due Date Owner Definition of
Done
Deliverables
A2 Scope
Submission
12/09/2025 Everyone Scope document
completed and
submitted
Final PDF/docx
A3 Final
Submission
14/11/2025 Everyone Final
deliverables
submitted
Code,
documentation,
video
Task board:
We will use Trello to maintain a single team dashboard, it contains to do, in progress and done.
The PM is responsible for assigning and tracking the owner (responsible person) for each task.
Dependency management strategy:
The priority to the storyboard, based on the storyboard we make the project happen. The database
must be ready first before we start backend development. Frontend integration can only begin after
the backend.
INFT6900 Group4 A2 8
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
• Team action plan
Working Agreements:
1. 2. Iteration cadence: Weekly iterations (planning on Monday, review on Friday).
Status updates: Daily updates on the task board; Project Manager will deal with issues for
more than 24 hours in Trello.
3. Response time:
 PR review completed within 24 hours.
 MS Teams messages confirmed within 24 hours.
 Quality gate: Code, test, documentation, basic accessibility check.
Tools: Trello (Columns: Backlog: To Do -> In Progress -> Done)
Code: java, html, css, ddl.
Documentation: Teams Shared Folder.
Design: Figma, Lucidchart.
Assessment Evidence:
Use Meeting minutes, risk log, Gantt chart, Figma export and test report, these serve as evidence
of deliverables for A2 and A3 project management.
Meetings
We hold a team Zoom meeting every Friday night at 10 PM, and we use a meeting template to
record the meeting content. It includes in attendance, progress report, agenda and action sheet.
Risk Management
It contains some processes such as identify, assess, mitigate, monitor and escalate. recorded a risk
register in a shared Teams folder, and it will review weekly during regular meetings.
Resources Required
Hardware and software requirements: Personal Laptop, GitHub repository, MS Teams and
Trello for collaboration; Figma for design; SQL server 2020, MS visual studio 2022, IDE.
Data requirements: There is 25 Chinese vocabulary words (including characters, pinyin, and
English definitions), corresponding audio, and video files.
Testing tools: Google Chrome and MS Edge for testing frontend.
Document templates: User and Administrator guide, meeting minutes and pre-action plan temple.
INFT6900 Group4 A2 9
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
• Development Methodology
In this project we apply Agile methodology. This methodology involves:
• Sprints: There is a one-week development cycle.
• Sprint Planning: An online weekly meeting in conducted on every Friday to decide tasks
in the Trello backlog and to track the progress.
• Stand-ups: Short inquiries and updates are made on MS Teams channel daily to
communicate regarding the project.
• Sprint Review A weekly meeting following lab to showcase accomplished functionality
to the team.
Reasons:
Short iteration cycles and rapid delivery, every week have deliverables and Agile ensures rapid
feedback. Agile allows flexible adjustments to the project.
Agile provides greater flexibility, the team need collaborate, such as front-end development, back-
end development, database management, UI design, and project management, frequent
communication is essential.
Conclusion
This project has already through team meetings to determine roles and responsibilities, the
development methodology (Agile), time plan, risk management, resource allocation and
requirements. Based on the current scope and the team progress, we hope to deliver the final
product on time by November 14, 2025.
INFT6900 Group4 A2 10
Ahsanul Haque 3499417; Arnab Kar 3493570; Trang Pham 3487866; Hefei Sun 3314177; Di Hao 3511628
Next Steps
12.09.2025 (A2): Submit the Scope document.
Week3–4: Set up GitHub repository, create a Teams and Trello board, find the vocabulary list.
(Already Completed)
Week4-5: Complete ERD and DDL with data, implement backend authentication and CRUD,
create the basic structure for the vocabulary page.
Week5–6: Create the basic structure for the admin panel, begin frontend-backend integration.
Week6–8: Integration testing and bug fixing, import initial data; complete basic accessibility
checks (keyboard accessibility/contrast).
Week9(Sprint): QA and documentation.
Week10–11: System demo and recording, package deliverables (code, database scripts,
documentation, video).
14/11/2025 (A3 Final Submission): Submit all deliverables as required.
