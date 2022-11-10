# Project areas

## Table of Contents

[User Interface](#user-interface)

- [User Experience Design](#user-experience-design)
- [User Interface: Design](#user-interface-design)
- [User Interface: Event Handling](#user-interface-event-handling)

[Server Side API](#server-side-api)

- [API Implementation](#api-implementation)

[Dev Ops](#dev-ops)

- [Git Maintainer](#git-maintainer)

[Project Management](#project-management)

- [Scrum Master](#scrum-master)

## User Interface

### User Experience Design

- Tasks
  - establish user interaction flow
  - itemize the user pages/screens
  - create wireframes
  - document user stories
- Technologies and Concepts
  - Who are the users?
  - What is an MVP?
  - User flow diagram
  - Data flow Diagram
  - Wireframing tools
    - Figma
    - miro
    - Adobe XD
    - Pen and Paper
- Related Areas
  - [User Interface Design](#user-interface-design)
    - Identify the pages/screens that need to be designed

### User Interface: Design

- Tasks
  - Design the look and feel
  - Colors
  - Fonts
  - Layout
  - Identifying what is static and what is data
- Technologies and Concepts
  - Graphic design
    - Figma
    - Sketch
    - miro
    - Adobe XD
    - Photoshop
  - HTML
  - CSS
  - CSS Framework (e.g., Bootstrap, UI Kit, Foundation)
  - Files: `html`, `css`
- Related Areas
  - [User Experience Design](#user-experience-design)
    - Identify the pages/screens that need to be designed
  - [User Interface: Event Handling](#user-interface-event-handling)
    - Identify the html elements that need to be updated or watched

### User Interface: Event Handling

- Tasks
  - In general, integrates the HTML Design with the Server Side API calls
    - Identifying interactions in the UI
    - Writing event handlers
    - Working with API Implementation team member(s) to establish parameters and JSON objects
- Technologies and Concepts
  - Forms
  - Javscript
  - DOM (document object model) Manipulation
  - Event handling
  - Files: `js`
- Related Areas
  - [User Interface: Design](#user-interface-design)
    - Identify the html elements that need to be updated or watched
  - [API Implementation](#api-implementation)
    - Identify and name request parameters (if any) that need to be sent
    - Describe response object returned from API request
    - Identify relevant properties in the response object

## Server Side API

### API Implementation

- Tasks
  - Identify API's
  - Read API documentation
  - Identify API endpoints
  - Identify API endpoint parameters
  - Understand the response object and its properties
- Technologies and Concepts
  - Javascript
  - `fetch`
  - Asynchronous Javascript (Promises, `.then`)
  - API documentation
  - Files: `js`
- Related Areas
  - [User Interface: Event Handling](#user-interface-event-handling)
    - Identify and name request parameters (if any) that need to be sent
    - Describe response object returned from API request
    - Identify relevant properties in the response object

## Dev Ops

### Git Maintainer

- Tasks
  - establish and maintain a github project
  - share project with team members
  - protect the `main` branch
  - create a `.gitignore` file
  - enforce a git workflow
    - monitor feature branches
    - facilitate merges, pull requests
- Technologies and Concepts
  - `git`
  - `github`
- Related Areas
  - [Scrum Master](#scrum-master)
    - how often should we build?
    - how often should we make pull requests?

## Project Management

### Scrum Master

- Tasks
  - establish a project management system (e.g., a kanban board)
  - establish a Google Doc
  - write issues in the kanban
  - lead standup meetings
  - keep track of assigned issues
  - keep communication open
  - troubleshoot planning
  - schedule meetings
- Technologies and Concepts
  - github issues
  - kanban
  - slack
- Related Areas
  - [Git Maintainer](#git-maintainer)
    - plan and facilitate pull requests
