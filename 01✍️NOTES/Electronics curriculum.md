---
created: 2026-08-31
related-notes: "[[01📌大事]]"
cover: giphy.gif
---



Beginner Tech Curriculum — Electronics → Software / Automation

Target: Become employable in Japan by combining existing electronics/manufacturing experience with software, automation, IoT, and cloud skills.

Estimated timeline: 9–12 months  
Study target: ~10 hours/week  
Strategy: 30% learning / 70% building

  

Why This Path?

With 7 years of experience in an electronics company and no degree, don’t try to compete directly with CS graduates for generic junior frontend jobs.

Instead, combine:

- Electronics experience
- Programming
- Automation
- IoT
- Data
- Backend development
- Cloud

The goal is to become someone who can work across hardware + software + manufacturing/data systems.

Potential career directions:

- Embedded / firmware
- Automation engineering
- IoT engineering
- Manufacturing DX
- Test automation
- Backend development
- Cloud engineering
- Data engineering
- Industrial software

  

Phase 1 — Programming Fundamentals

Weeks 1–6

Language: Python

Learn

- ☐ Variables
- ☐ Data types
- ☐ if / elif / else
- ☐ for loops
- ☐ while loops
- ☐ Functions
- ☐ Lists
- ☐ Dictionaries
- ☐ Sets
- ☐ Tuples
- ☐ Strings
- ☐ File reading/writing
- ☐ Exceptions
- ☐ Modules
- ☐ Packages
- ☐ Basic OOP
- ☐ Debugging
- ☐ Using external libraries
- ☐ Basic Git/GitHub

Small Exercises

Build:

- ☐ Calculator
- ☐ Unit converter
- ☐ Temperature converter
- ☐ Expense tracker
- ☐ CSV data analyzer
- ☐ File-organizing script
- ☐ Simple equipment log program

First Portfolio Project

Production / Test Data Analyzer

Create a Python program that takes test or production data from a CSV file and:

- ☐ Reads the data
- ☐ Calculates averages
- ☐ Identifies out-of-spec values
- ☐ Calculates basic statistics
- ☐ Generates a pass/fail result
- ☐ Creates graphs
- ☐ Generates a report
- ☐ Saves the results

Try to make the project related to your existing electronics/manufacturing experience.

  

Phase 2 — Computer Fundamentals

Weeks 7–10

Linux

Learn:

- ☐ Terminal basics
- ☐ Files and directories
- ☐ File permissions
- ☐ Processes
- ☐ Environment variables
- ☐ Package installation
- ☐ SSH
- ☐ Basic shell commands

  

Git

Learn:

- ☐ git clone
- ☐ git add
- ☐ git commit
- ☐ git push
- ☐ git pull
- ☐ Branches
- ☐ Merging
- ☐ .gitignore
- ☐ GitHub repositories

  

Networking

Understand:

- ☐ IP addresses
- ☐ DNS
- ☐ TCP
- ☐ UDP
- ☐ Ports
- ☐ HTTP
- ☐ Client/server architecture
- ☐ REST APIs
- ☐ JSON
- ☐ MQTT

  

Phase 3 — Electronics + Programming

Weeks 11–16

Use an ESP32 or similar microcontroller.

Learn

- ☐ Digital input/output
- ☐ Analog input
- ☐ PWM
- ☐ Sensors
- ☐ Serial communication
- ☐ I²C
- ☐ SPI
- ☐ UART
- ☐ Microcontroller fundamentals
- ☐ Reading datasheets
- ☐ Hardware/software debugging

Language

Learn enough C/C++ to program microcontrollers.

You do not need advanced C++ yet.

  

Project 2 — IoT Temperature Monitor

Build:

Temperature Sensor

        ↓

      ESP32

        ↓

       Wi-Fi

        ↓

       MQTT

        ↓

      Python

        ↓

    Database

        ↓

    Dashboard

Features

- ☐ Read temperature
- ☐ Connect ESP32 to Wi-Fi
- ☐ Send measurements
- ☐ Receive measurements with MQTT
- ☐ Process data with Python
- ☐ Store measurements
- ☐ Display measurements
- ☐ Detect abnormal values
- ☐ Log errors

  

Phase 4 — SQL + Databases

Weeks 17–20

Use:

- PostgreSQL
- SQLite for simple experiments

Learn

- ☐ Tables
- ☐ Rows and columns
- ☐ Primary keys
- ☐ Foreign keys
- ☐ Relationships
- ☐ SELECT
- ☐ WHERE
- ☐ ORDER BY
- ☐ GROUP BY
- ☐ JOIN
- ☐ INSERT
- ☐ UPDATE
- ☐ DELETE
- ☐ Indexes
- ☐ Basic database design

  

Project — Equipment Monitoring Database

Store information such as:

Equipment ID

Timestamp

Temperature

Voltage

Current

Status

Error Code

Practice answering questions with SQL:

- Which machine had the most errors?
- What was the average temperature per machine?
- Which machines exceeded the temperature threshold?
- Which equipment has the highest failure rate?
- What happened during a particular time period?

  

Phase 5 — Backend Development

Weeks 21–26

Technology

Python + FastAPI

Learn

- ☐ HTTP
- ☐ REST
- ☐ API endpoints
- ☐ GET
- ☐ POST
- ☐ PUT
- ☐ DELETE
- ☐ JSON
- ☐ Authentication basics
- ☐ Database connections
- ☐ Error handling
- ☐ API documentation
- ☐ Environment variables
- ☐ Logging

  

Project — Equipment Monitoring API

Extend the IoT project.

Architecture:

ESP32

  ↓

MQTT

  ↓

Python

  ↓

PostgreSQL

  ↓

FastAPI

  ↓

Dashboard

The API should allow you to:

- ☐ View equipment
- ☐ View sensor data
- ☐ Add equipment
- ☐ Update equipment
- ☐ Search measurements
- ☐ Retrieve statistics
- ☐ View errors
- ☐ Set thresholds
- ☐ Authenticate users

  

Phase 6 — Web Development

Weeks 27–30

The goal is not to become a frontend specialist.

Learn enough frontend development to build interfaces for your systems.

  

HTML

- ☐ Elements
- ☐ Semantic HTML
- ☐ Forms
- ☐ Tables
- ☐ Links
- ☐ Basic accessibility

  

CSS

- ☐ Selectors
- ☐ Box model
- ☐ Flexbox
- ☐ Grid
- ☐ Responsive design
- ☐ Basic layouts

  

JavaScript

- ☐ Variables
- ☐ Functions
- ☐ Arrays
- ☐ Objects
- ☐ DOM
- ☐ Events
- ☐ Fetch
- ☐ APIs
- ☐ Promises
- ☐ async / await

  

Optional: React

After understanding basic JavaScript:

- ☐ Components
- ☐ Props
- ☐ State
- ☐ Events
- ☐ Forms
- ☐ API calls
- ☐ Basic routing

The goal is:

Build an interface for your backend and IoT systems.

Not:

Become a React tutorial expert.

  

Phase 7 — Docker + Cloud

Weeks 31–36

Docker

Learn:

- ☐ Images
- ☐ Containers
- ☐ Dockerfiles
- ☐ Docker Compose
- ☐ Volumes
- ☐ Networks
- ☐ Environment variables

Practice running:

Frontend

Backend

Database

MQTT

as separate containers.

  

AWS

Learn the fundamentals of:

- ☐ EC2
- ☐ S3
- ☐ RDS
- ☐ IAM
- ☐ VPC
- ☐ Basic networking
- ☐ CloudWatch

The goal is not to collect certifications.

The goal is to understand:

How do I take an application I built locally and run it in the cloud?

  

Phase 8 — Choose a Specialization

Months 9–12

Choose based on your existing electronics experience and the jobs you want.

  

Option A — Industrial Automation

Best if you work around factories and production equipment.

Learn:

- ☐ PLC fundamentals
- ☐ Ladder logic
- ☐ Sensors
- ☐ Actuators
- ☐ HMI
- ☐ SCADA concepts
- ☐ Modbus
- ☐ OPC UA
- ☐ Industrial Ethernet
- ☐ Basic robotics

Potential roles:

- Automation Engineer
- Controls Engineer
- Manufacturing DX Engineer
- Industrial IoT Engineer

  

Option B — Test Automation

Best if your experience involves testing or quality.

Learn:

- ☐ Python test automation
- ☐ Serial communication
- ☐ Instrument control
- ☐ Automated measurements
- ☐ Data logging
- ☐ Test report generation
- ☐ Hardware-in-the-loop concepts

Potential roles:

- Test Automation Engineer
- Validation Engineer
- QA Automation Engineer
- Manufacturing Test Engineer

  

Option C — IoT / Edge Computing

Best if you like combining hardware and software.

Learn:

- ☐ ESP32
- ☐ Raspberry Pi
- ☐ MQTT
- ☐ Linux
- ☐ Python
- ☐ Networking
- ☐ Sensors
- ☐ Databases
- ☐ APIs
- ☐ Docker
- ☐ Cloud

Potential roles:

- IoT Engineer
- Edge Engineer
- Embedded IoT Engineer
- Industrial IoT Engineer

  

Option D — Backend / Cloud

Best if you decide you want to move further into software.

Go deeper into:

- ☐ Python
- ☐ FastAPI
- ☐ PostgreSQL
- ☐ Docker
- ☐ AWS
- ☐ Linux
- ☐ CI/CD
- ☐ Testing
- ☐ System design
- ☐ Security fundamentals

Potential roles:

- Backend Engineer
- Full-Stack Engineer
- Cloud Engineer
- Software Engineer
- Platform Engineer

  

Portfolio

Do not build 20 tiny tutorial projects.

Build 3 serious projects.

  

Project 1 — Automated Test/Data Analyzer

CSV / Test Data

       ↓

     Python

       ↓

   Validation

       ↓

  Statistics

       ↓

    Pass/Fail

       ↓

     Report

Include:

- ☐ Clean code
- ☐ Error handling
- ☐ Tests
- ☐ Documentation
- ☐ Graphs
- ☐ Example data
- ☐ Screenshots
- ☐ GitHub repository

  

Project 2 — IoT Equipment Monitor

Sensor

  ↓

ESP32

  ↓

MQTT

  ↓

Python

  ↓

PostgreSQL

  ↓

FastAPI

  ↓

Dashboard

Include:

- ☐ Real sensor data
- ☐ MQTT
- ☐ Database
- ☐ REST API
- ☐ Dashboard
- ☐ Error handling
- ☐ Logging
- ☐ Documentation

  

Project 3 — Production / Maintenance System

Build a realistic system for managing equipment.

Possible features:

- ☐ Equipment database
- ☐ Equipment status
- ☐ Maintenance records
- ☐ Sensor measurements
- ☐ Error codes
- ☐ User authentication
- ☐ Alerts
- ☐ Search/filtering
- ☐ Statistics
- ☐ Dashboard
- ☐ Docker
- ☐ Automated tests
- ☐ Cloud deployment
- ☐ CI/CD

This should become your main portfolio project.

  

Weekly Study Schedule

Target: ~10 hours/week

|   |   |   |
|---|---|---|
|Day|Time|Activity|
|Monday|1h|Learn|
|Tuesday|1h|Exercises|
|Wednesday|1h|Learn|
|Thursday|1h|Exercises|
|Friday|—|Rest|
|Saturday|3h|Project|
|Sunday|3h|Project|

Study ratio

30% Learning

70% Building

Avoid spending months watching tutorials.

The objective is to build things you don’t completely understand yet, then learn what you need to finish them.

  

Technology Roadmap

Follow approximately this order:

Python

   ↓

Git + GitHub

   ↓

Linux

   ↓

Networking

   ↓

ESP32 + C/C++

   ↓

SQL

   ↓

MQTT

   ↓

FastAPI

   ↓

HTML / CSS / JavaScript

   ↓

React

   ↓

Docker

   ↓

AWS

   ↓

PLC / Industrial Automation

You can change the final specialization depending on your career goals.

  

Using AI While Learning

Use AI from the beginning, but don’t let it replace your learning.

Good uses:

- ☐ Explain concepts
- ☐ Generate exercises
- ☐ Review your code
- ☐ Help debug errors
- ☐ Explain error messages
- ☐ Suggest project ideas
- ☐ Review architecture
- ☐ Generate test cases
- ☐ Help write documentation

Bad habit:

Copy AI-generated code without understanding it.

Rule:

If AI writes it, you should be able to explain it.

Your long-term advantage isn’t typing code faster than AI.

It’s understanding systems, hardware, software, data, and the real-world problem you’re solving.

  

First 2 Weeks

Don’t worry about AWS, React, PLCs, or AI yet.

Focus only on Python.

Week 1

- ☐ Install Python
- ☐ Install VS Code
- ☐ Learn variables
- ☐ Learn data types
- ☐ Learn if
- ☐ Learn loops
- ☐ Learn functions
- ☐ Complete 20–30 small exercises

Week 2

- ☐ Lists
- ☐ Dictionaries
- ☐ Strings
- ☐ Files
- ☐ Exceptions
- ☐ Modules
- ☐ Basic classes
- ☐ Git
- ☐ Create first project
- ☐ Upload project to GitHub

  

Career Strategy

Don’t position yourself as:

“A beginner with no degree trying to become a web developer.”

Position yourself as:

“An electronics/manufacturing professional transitioning into software, automation, IoT, and digital transformation.”

Your existing industry experience is part of your technical story.

The objective is to combine:

7 Years Electronics Experience

             +

       Programming

             +

       Automation

             +

          IoT

             +

       Data / Cloud

             ↓

   Specialized Tech Engineer

That combination is the core of this curriculum.

  

Final Goal

By the end of the curriculum, you should be capable of:

- ☐ Writing Python programs independently
- ☐ Using Git/GitHub
- ☐ Working comfortably in Linux
- ☐ Understanding basic networking
- ☐ Programming a microcontroller
- ☐ Reading sensor data
- ☐ Communicating over MQTT
- ☐ Designing a basic SQL database
- ☐ Building a REST API
- ☐ Building a basic web interface
- ☐ Containerizing applications with Docker
- ☐ Deploying an application to AWS
- ☐ Automating repetitive technical tasks
- ☐ Building an end-to-end IoT/automation system
- ☐ Explaining your technical decisions
- ☐ Demonstrating your work through a GitHub portfolio

The end result should not be:

“I learned how to code.”

It should be:

“I can build and troubleshoot software systems that interact with real equipment, data, and business processes.”