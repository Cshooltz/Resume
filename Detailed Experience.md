# DETAILED PROFESSIONAL EXPERIENCE

### PERSONAL INFO
**Name:** Collin Shooltz  
**Location:** Michigan  
**Contact:** For unsolicited contact, please message me through GitHub or Indeed 

### PREFACE
This document contains a more or less exhaustive list of my skills and experience along with explanations. This is supplemental information for you to peruse at your convenience if you would like additional details on any of my experience.

----------------------------------------------------------------
### TABLE OF CONTENTS
- [Education and Training](#education-and-training)
  - [Undergraduate College (Chemical Engineering)](#undergraduate-college)
  - [*Our Community Listens* Communication Training](#our-community-listens-communication-training-provided-by-phillipslistens-inc-november-2016)
  - [Continuous Improvement Training, DTE](#continuous-improvement-program-training-dte-energy-2018-2019)
- [Work Experience](#work-experience)
  - [Natural Gas Pipeline and Facilities Engineer, DTE Energy](#natural-gas-transmission-pipeline-and-facilities-engineer-dte-energy-detroit-mi-2017-2020)
    - [Overview](#overview)
    - [Responsibilities](#responsibilities)
    - [Accomplishments](#accomplishments)
- [Software Development Experience](#software-development-experience)
  - [Overview](#overview-1)
  - [Practice Database Editor Project](#practice-database-editor-application)
  - [Complete C# Masterclass, Udemy](#complete-c-masterclass-udemy-course)
- [Art, 3D Modeling, and CAD experience](#art-3d-modeling-and-cad-experience)
  - [2D and 3D CAD](#2d-and-3d-cad)
  - [Artistic 3D Modeling and Rendering](#artistic-3d-modeling-and-rendering)
  - [2D Techniques and Design](#2d-techniques-and-design)
- [Additional Skills](#2d-techniques-and-design)

## EDUCATION AND TRAINING
#### Undergraduate College
Michigan Technological University, Houghton, MI  
BS Chemical Engineering, 3.62 GPA (Cum Laude), April 2016  
Passed FE Exam, April 2016

#### Misc
- Continuous Improvement Program Training, DTE Energy, 2018-2019
- Our Community Listens communication training, provided by PhillipsLISTENS, INC, November 2016

## SOFTWARE DEVELOPMENT EXPERIENCE

### Overview
I have always had a passion for software and computer science and have dabbled in programming on and off most of my life. It wasn’t until I left my last job, however, that I realized software development is more interesting to me now than traditional engineering. So, over the last year I have been working hard at filling in my experience gaps for software development.

**General Skills and Capabilities:**  
  - Generally competent with programming environments and comfortable using most languages
  - Comfortable using/making Linux shell scripts and Powershell scripts
  - Comfortable on any operating system (most experienced with Linux and Windows)
  - High level understanding of the underlying operations and architectures of computers, and comfortable going as low level as programming in assembly language
  - Currently specialized in C# programming for cross platform .Net applications
  - Functional with multi-threaded programming. Comfortable using Tasks, ThreadPool threads, and manual Threads in C#. Comfortable using multi-threaded control structures and data structures, such as locks, mutexes, and event handles. I implemented 3 basic threading strategies in my own application over 3 days at the end of January.
  - Comfortable with UI programming. I know the basics of WPF and HTML/CSS/JS. My preference for developing personal applications is to use a game engine like Godot or Unity
  - Comfortable using game engines. Most experienced with Godot, but comfortable with Unity and Unreal Engine 4 
  - Comfortable working with digital assets, i.e. images, SVG, audio, 3D data, etc. I am not yet very experienced working with these data formats from the code side of things, but I am learning more every day

**Todo Learning and Projects:**  
  - Complete my database editor I am making in Godot.
  - Make a similar practice project in Unity to compare their workflows and architecture.
  - Port one or more of my practice projects to mobile
  - Learn ASP.Net Core for building web apps and services
  - Learn and use advanced data modeling, processing, and storage
  - Learn how to implement real-time network communications, i.e. multiple users editing the same document in real-time over the internet
  - Experiment with procedural generation and simulation (i.e. physics and graphics)

### Practice Database Editor Application
For a detailed description and the source code for this project, please visit my GitHub repository: [Data Editor App](https://github.com/Cshooltz/Data-Editor-App)

To summarize, this is my first graphical application that I am building on my own from scratch. The purpose of this app is for me to gain practical experience building a real application and serve as a testing ground for me to learn and experiment with code. 

The goal is to have a generalized, but simple, database editor that can work with data stored in multiple ways: in text files, in a local embedded database (i.e. SQLite), and in a database server such as MySQL. The project is still fairly early on, and at this time you can use the app to write a static test data set to a JSON file, load test data into the table UI element, and browse the local filesystem in the embedded file browser I made. 

the following is a brief list of my accomplishments so far in this project:
- Built basic UI structure for user interaction with the program
- Created a custom table UI element for viewing and editing data
- Created a custom embedded file browser (working towards making it a full file manager) complete with delegation of blocking code to worker threads
- Implemented 3 reusable threading strategies over 3 days (dedicated worker thread that is fed a queue of functions, a work queue structure using Tasks and ContinueWith, and simple Tasks with mutexes protecting mutually exclusive code)
- Integrated the Newtonsoft Json.Net library for serialization of data structures to/from JSON
- Implemented saving of data structures to JSON text files

### Complete C# Masterclass, Udemy Course
For a detailed description and the source code I wrote following this course, please visit my GitHub repository: [C# Masterclass](https://github.com/Cshooltz/CSharp-Masterclass)

To jumpstart my career change into software development, I decided to look for an extensive course on C#. I chose the Complete C# Masterclass course because the curriculum is one of the most diverse and complete I have seen. Starting from the most basic concepts, the course moved on to broach advanced topics like multithreaded programming, LINQ, utilizing a SQL database in a project, and building GUI apps using Windows Presentation Foundation. I completed almost the entirety of the course within one month's time.

My favorite parts of this course were the small projects that resulted in more or less complete small applications. The first one was a console based tic-tac-toe game, which I designed from scratch before watching the instructor's solution. The second was a complete WPF app that allowed the user to view and edit data stored in a local Microsoft SQL server (the Zoo Manager app).

The following is a brief list of topics covered in this course:
- Detailed usage of Visual Studio Community IDE
- Basic programming concepts (i.e. functions, data types, loops, etc, etc)
- Somewhat advanced use of the command line environment
- Advanced object oriented programming
- Debugging
- Intro to .Net APIs
- Multithreaded programming with Threads, ThreadPool, Tasks, and async/await
- Use of LINQ and SQL databases
- Nullables, events, and delegates
- GUI programming using the Windows Presentation Foundation

## WORK EXPERIENCE
### Natural Gas Transmission Pipeline and Facilities Engineer, DTE Energy, Detroit, MI 2017-2020
### Overview
My primary function within this position was to own, manage, and execute capital projects to install and modify natural gas transmission systems. The position covered a very broad array of auxiliary responsibilities, including support of other departments, records auditing, and coordinating with outside companies who are performing construction in the vicinity of DTE Gas facilities (facility requests). I also had many opportunities to contribute to my department's work processes and improve the overall function of the team.

### Responsibilities
**Capital Project Execution**  
Execution of capital projects was my main responsibility at DTE. In my time there, I completed 10's of capital projects per year. Most were small scale ($10,000 - $250,000), but regularly worked on mid scale ($250 - $500,000) projects and periodically worked on large scale ($500,000 - $1MM+) as well. The following list describes the main high level components of executing those projects.

- **Engineering and Design:** 
Responsible for end to end design of the new natural gas facilities for each project. Design process started with conceptual design, which captured the scope of the project, intended modifications, and equipment sizing. Ended with detailed design, which resulted in a complete set of engineer signed construction drawings, project documentation, and procurement of all materials and services required for the project.

- **Record Keeping and Documentation:**
Per federal regulatory requirements, assembled complete documentation of each project's scope and construction records. Also personally co-led my department's response to a records audit requested by the Michigan Public Safety Commission (MPSC), which involved finding, understanding, and presenting project construction records for projects executed over the last 40 years.

- **Financial Analysis:**
Created detailed cost estimates for every assigned project. Performed financial forecasting for each project at regular intervals during the annual project cycle. Measured cost variance between cost estimates and actual project costs and used the data to improve future cost estimating.

- **Project Coordination:**
The execution of every project required collaboration between 5-10 internal departments, and as the engineer it was my responsibility to inform and coordinate activities between all of the departments. Inter-department collaboration was required for everything from initial planning and design to implementation and construction of each project. 

  I was also responsible for coordinating with external vendors and contractors to provide the required materials and services to complete the project within the project's timeframe.

  While the project engineer does not directly oversee construction on any project, the engineer was also responsible for coordinating construction activities between the required groups (i.e. internal/external mechanical, electrical, and civil construction crews).

- **Procurement of Materials and services:**
As the project engineer, I was responsible for developing material specifications and service scope of work documents, and reaching out to vendors and contractors (either directly or through Procurement) to request quotes and bids. Also performed bid analysis and selection on received bids. 

  I developed and maintained business relationships between myself and vendors/contractors, and worked closely with many throughout my time at DTE. I and my team also received a variety of training on specialized topics from our vendors and contractors.

**Facility Requests**  
One of the important auxiliary functions of the engineers at DTE was to respond to facility requests. A facility request is when an outside organization is planning to build over or around a DTE gas line and notifies DTE (normally) through the MISS DIG system. This triggers a process where DTE must review the client's construction plans and provide guidance to the client regarding how to safely build around the pipeline. During the review process, the engineer becomes the primary point of contact for the engineer, and it is the engineer's responsibility to reach out to them and collect all the necessary information on the project.

After my initial successes with facility requests, I quickly became one of the go-to people for handling facility requests within my team. This was actually one of the most interesting parts of my job, since each client's scenario was unique and usually required a custom solution developed in collaboration between myself and the client. Naturally, these jobs required a large amount of relationship building and conflict resolution, since the interests of the client often conflicted hard with the interests of DTE (which are grounded in public safety, pipeline maintenance, and cost effectiveness).

**Continuous Improvement**  
At DTE, continuous improvement is a significant part of company culture. As well, there was no lack of opportunities for improvement at the company during my time there. This became an area ripe for my involvement, and I made significant contributions to the effort during my time at DTE, and even started some initiatives that persist even after my departure.

My most noteworthy contributions were: creating new process maps, creating a comprehensive set of standard material and equipment specifications, updating and standardizing my department's engineering scope of work templates, and adding new standardized engineering calculation spreadsheets to our library as well as improving old ones. Please see the *Accomplishments* section for more details on these contributions.

**Safety and Procedure Development**  
Safety is paramount in the natural gas industry, and it was no less so at DTE. Many of my job functions included safety procedures surrounding the construction and operation of natural gas facilities. One of the most important and intensive responsibilities of my position was the development and overseeing of Pressure Control Procedures (PCPs), which are required for any non-standard operation of pipeline facilities (i.e. taking a pipeline down for construction then bringing it back online). 

PCPs are absolutely critical, as something as simple as turning the wrong valve at the wrong time or without appropriate preparations could cause an actual disaster; potentially harming human life and disrupting gas flow to customers. Not to mention the monetary cost. Being that they were required for almost every project big or small, developing and executing PCPs was a very regular occurrence that I and my team got very good at.

**Drawing Review and Drafting Exposure**  
As an engineer at DTE, I could not directly create engineering drawings myself, but instead had to rely on a dedicated department of drafters who also managed all drawing records for all DTE Gas facilities. The typical process was to request drawings of a station (since most projects were on existing facilities), markup the drawings to show the changes to be made, submit the markups to Drafting, then Drafting will create iterative designs (normally following the 30/60/90% milestone method) that the engineer will subsequently review and return to Drafting until the drawings meet all the requirements of the project.

This experience gave me an intimate knowledge of DTE drawing standards, CAD drawing comprehension, and skill for communicating revisions to drawings between departments. I also had the opportunity to initiate brand new drawings for brand new stations, where I created detailed conceptual sketches of the facilities to be installed, which Drafting used as the foundation for their CAD drawings.

**Document Authoring**  
Writing detailed specifications for materials and services was a frequent task in this position, so I gained detailed experience working with Microsoft Office, particularly Word and Excel, to make exhaustive documents that define the complete scope of a material or service purchase. These documents served as the main legally binding document for all purchases made by my department, so they had to be thorough and carefully worded to ensure that the materials and services rendered exactly met the requirements of the job, and could be referenced in the event any conflicts arose in the process of the vendor or contractor fulfilling the purchase order. My team and I spent considerable time and effort working together to perfect how we write material specification and service scope of work documents.

### Accomplishments
The following subsections are a list of contributions I made to improve the operation of my department and business unit at DTE as well as personal accomplishments I would like to highlight.

**Central Department Documentation Website**  
When I arrived, my department had no internal documentation on any of the engineers' job functions. This made it enormously difficult to learn how to do my job, especially since there was a deficit of people who could adequately teach me. To mitigate this problem for future hires and help standardize operations of the department, I developed a Sharepoint website to house documentation in an accessible way. Any of the engineers could contribute to the documentation on the website, and collectively we began to document our various job components. This is a very large task that is still a work in progress even after I left the company. 

**Calculation Spreadsheets**  
The department was also lacking a number of standard calculations. In order to facilitate my own job, I had to do deep research and my own mathematical modeling to develop the calculations I needed. I turned these calculations into spreadsheets, which I then shared with the department so everyone could benefit from them. My most notable calculation sheets were:
  - Gas pressure regulator sizing and set point calculator
  - Gas velocity and volumetric flow calculator
  - Time estimate calculator for the duration of venting a pipeline to atmosphere (was also adapted to calculating lost gas volume through a pipeline leak)

**Improved Group Project Management System**  
I drove the creation and implementation of a new, comprehensive, high-level project management system for the group. The main purpose of the system was to track the progress of each engineer’s projects and help engineers provide estimates for how many working hours they will need to spend on each project. Having a structured system facilitated smarter workload balancing between engineers as well as better collaboration, allowing everybody on the team to benefit from their peers' expertise on different projects. The development and implementation of this system was the result of collaborating with my entire team.

**Developed Group Project Management Strategies**  
As a part of the new project management system, I collaborated with my team to develop new work strategies to make project execution more efficient and robust. Some of the strategies are as follows:
  - Create a standardized list of project types. We could then group well defined projects by type so we can complete similar projects together and gain efficiency through batching similar tasks.
  - We developed a method for engineers to report progress blocking issues on their projects. This facilitated getting help from the entire team to resolve problems as fast as possible with minimal downtime.
  - The initial version of my department's capital project process had the conceptual design phase relatively late in the process. I worked with my team to revise the process and move the conceptual design phase to earlier in the process. This allowed us to review all of our projects as a team early in the project cycle, which allowed us to better collaborate between projects and balance our workloads in a smarter way; among many other benefits.
  - To better facilitate the design process, I worked with my team to develop a new deliverable package specification for conceptual designs. The specification included a template and form to provide a standard for engineers to follow when developing conceptual designs, and created a complete package that documents the scope and intent of the project. The package could then be used to communicate the project details to other members of the project team and facilitate easy transitioning of engineers between projects if needed. 

**Conflict Resolution**  
Externally, I had the opportunity to resolve several conflicts between DTE and outside customers. I was able to take a tense situation with customers and work with them to create mutually beneficial solutions for challenging problems. In the end, we took what looked like an impossible situation and turned it into a giant success. 

Internally, navigating competing interests between departments and business units within DTE was a regular occurrence. I was able to regularly resolve these conflicts with open discussion and careful negotiation to ensure everybody's needs were met prior to continuing any project. 

**Improvement of Inter-department Relationships**  
My success and the success of the company depended heavily on teamwork and collaboration between departments. I spent a lot of effort building up the relationships between my department and the co-dependent departments we worked with. I succeeded through proactive collaboration and open, regular, discussion. The result was better communications between groups, reduced work errors, and faster turn around times on requests, among a variety of other small improvements that increased overall efficiency and ease of work.

## ART, 3D MODELING, AND CAD EXPERIENCE

#### 2D and 3D CAD
In college, I was trained in blueprint reading, use of AutoCAD for producing 2D drawings/prints, and use of Solidworks for producing 3D models, 2D prints, and 3D printed prototypes. I actually developed a little action figure for my final project that I 3D printed and assembled. My joint designs needed work, but it otherwise turned out great!

Beyond that, I had a lot of exposure to 2D CAD at DTE. While I didn't construct the drawings myself, I became intimately familiar with the drafting standards and process. I also produced detailed hand sketches of designs to provide to the drafting department.

#### Artistic 3D Modeling and Rendering
As a hobby for most of my life I've practiced 3D modeling and rendering. My tool of choice is the open source software, Blender. I am familiar with most production steps and can create textured 3D objects and scenes complete and ready for animation and rendering.

#### 2D Techniques and Design
This last year I have taken a break from focusing on 3D in my spare time and have decided to focus on digital drawing and painting skills. While I would still consider myself a hobbyist and a novice in this space, I do have significant training in art theory and am competent enough to be able to sit and make a drawing of whatever I want (i.e. diagrams, perspective drawings, figure drawings, etc), even if it is low quality compared to what a professional can turn out. My experience here gives me additional tools to use for communication and problem visualization and solving.

## ADDITIONAL SKILLS
- Proven communication, diplomacy, and teamwork skills
- Excels at process engineering and process design
- Very high competence using computers and software
- Excellent office software skills (i.e. Microsoft Office, Libre Office)
- Self-starter: Very self motivated and requires little supervision. Will proactively learn new job functions and will ask for help when needed
- Comfortable building my own desktop PCs and familiar with most PC components
