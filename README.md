# Hi, my name is Kjetil Paulsen
Welcome to my portfolio! 

This collection is supposed to showcase the projects I've developed to demonstrate my skills software development and problem-solving. I mostly program in Python but I have in the past also progrmamed in C and C++. For the moment I am also imrpoving my skills in Javascript and Go.

Below, you'll find a brief overview of each project with links to their respective repositories. As I have gained new skills, and am continously doing so, I have felt a need to refactor and restructure old projects. Many of my projects are years old and as of 2026 I am in the process of migrating them into new repos, with different structures and layouts. This is being done in an effort to keep the code clean and repos organized through similar logging setup, pathing, env setups, entrypoints, dockerization, etc. The updates and migrations are happening as you are reading this, so stay tuned. Hopefully by the end of March 2026 I will have gotten things mostly up to snuff.

My long term project is to create a dashboard-like webpage accessed locally through the browser, with the ability to easily hook up new microservices. 
- A backend in FastAPI, ran in docker that is accessed locally through browser.
- Several modules that can be run independetly, locally or through docker, exposed through CLI or API.
- User sends a command to the API, it is then sent to the relevant app, event is returned and displayed to the user.

- This way we can attach different modules, like a password generator, journaling, stock lookup or analysis, and much more, and access it through a browser frontend.

In other words, creating a framework giving you easy access to tools that you want to use. And if you want a new tool, then build it, and hook it up.

---

## Featured Projects(Not yet updated tot he new layouts and streamlines)

### [**python-project-blueprint**](https://github.com/kjetilpaulsen/python-project-blueprint)
*Project is in the process of getting its README.md updated*

Initially inteded as a privat repo, this is designed to be a cookiecutter starting point for python projects.
- **Features**
  - Logging
  - XDG folder setuo
  - Testing
  - GitHub actions workflow for automatic testing and docker-image creation and push to dockerhub if pushed to release-branch
  - Dockerfile and docker-compose
  - Command/Event architecture
  - CLI/FastAPI entrypoints

- **Skills Demonstrated**
  - Command/Event architecture
  - Pytest
  - GitHub actions
  - Docker
  - CI/CD

---

### [**market-analysis-engine**](https://github.com/kjetilpaulsen/market-analysis-engine) 
*In an effort to modularize and concretesize my apps, this repo is an amalgamation of an earlier project migrated into [**python-project-blueprint**](https://github.com/kjetilpaulsen/python-project-blueprint)*

A Python-based financial analysis tool designed to download, store, analyze, and visualize stock market data.

- **Features**:  
  - Fetch and process financial data using the Yahoo Finance API via `yfinance`, then store data in PostgreSQL.  
  - Tools for analyzing and visualizing trends in stock data.  

- **Skills Demonstrated**:
  - API integration (Yahoo Finance)
  - Basic CRUD in PostgreSQL
  - Data analysis and visualization  
  - Python programming and modular design  

---

### [**password-engine**](https://github.com/kjetilpaulsen/password-engine)
*In an effort to modularize and concretesize my apps, this repo is an amalgamation of an earlier project migrated into [**python-project-blueprint**](https://github.com/kjetilpaulsen/python-project-blueprint)*

A Python-based CLI and API application for secure password generation, encryption, storage, and retrieval.

- **Features**:
  - Generate strong, random passwords with configurable constraints.
  - Authenticate users via hashed credentials to unlock encrypted password storage.
  - Store passwords with encryption at rest, including metadata such as user, email, and tags (e.g. service or URL).
  - Retrieve and list stored passwords through a CLI interface or API.

- **Skills Demonstrated**:
  - Secure password handling (hashing, encryption, key derivation)
  - CLI design and user interaction flows
  - Command/event-based architecture
  - Database design and secure data storage
  - Python backend development (FastAPI + modular structure)

---

### [**log-event-pipeline**](https://github.com/kjetilpaulsen/log-event-pipeline)
*First project using several new languages, this project is heavily backed by AI-assisted programming.*

A lightweight multi-language system demonstrating real-time log ingestion, filtering, and streaming using a decoupled pipeline architecture. A distributed log processing pipeline combining Python, Go, and a minimal frontend to generate, transport, filter, and visualize log events in real time.

- **Features**:
  - Python-based log generator that produces structured JSON events and streams them over TCP.
  - Go backend that ingests log events, filters high-severity logs (ERROR/CRITICAL), and broadcasts them to connected clients.
  - Real-time streaming to frontend clients using Server-Sent Events (SSE).
  - Minimal web interface for visualizing incoming error events live in the browser.

- **Skills Demonstrated**:
  - Network programming (TCP sockets, HTTP, SSE)
  - Concurrent systems in Go (goroutines, channels, synchronization)
  - Structured logging and event-driven design
  - Cross-language system integration (Python → Go → Web)
  - Real-time data streaming and frontend integration
 
---

### [**Terminal Journal**](https://github.com/kjetilpaulsen/journal)  
*This project is very old, has been through several iterations and migrations, and while currently functional, it lacks in abstraction, Command/Event architecture, separation of responsibilit/ownership etc. I include it here because it is a program that is dear to me and is one of the programs I use on a near daily basis.*

A Python-based journaling application built with the `curses` library, providing a minimalist, keyboard-driven interface for writing, browsing, and managing personal entries directly in the terminal. The project focuses on low-level UI control, efficient text handling, and a distraction-free writing environment.

- **Features**:  
  - Full-screen terminal interface powered by `curses`.  
  - Create, edit, and navigate journal entries using keyboard shortcuts.  
  - Structured storage and retrieval of entries for long-term use.   

- **Skills Demonstrated**:  
  - Terminal UI programming with `curses`  
  - File I/O and text processing  
  - State management and user interaction design   

---

### [**Psychology Practice Website**](https://gbpsicoterapia.it/en) 
*This project is more of a sideproject to help a relative, and is not meant to demonstrate anything other than very basic knowledge of webdesign*

A WordPress-based website designed for a private psychology practice, featuring custom content and an approachable design.

- **Skills Demonstrated**:
  - Website planning and design
  - Content management with WordPress
  - Client communication and project iteration

---

## Contact

Feel free to reach out if you'd like to collaborate or discuss my work:
- **Email**: kjetil_paulsen@hotmail.com
- **GitHub**: [kjetilpaulsen](https://github.com/kjetilpaulsen)
- **LinkedIn**: [Kjetil Paulsen](https://www.linkedin.com/in/kjetil-paulsen-631110b5/)

---

## Future Updates

This portfolio will continue to grow as I complete more projects and refine my skills. Stay tuned for additional showcases and updates!
