# Roadmap for Tools by Michaelninder

## Overview
This roadmap outlines the key features and development stages for `tools.michaelninder.de`. The site provides a modular set of tools for DNS management, server monitoring, and Minecraft utilities, with a focus on scalability, maintainability, and user experience.

---

## Current Structure

### Project Layout

/tools.michaelninder.de/ 
│ ├── index.php # The main homepage of the site 
├── /public/ # Public-facing entry points 
│ ├── index.php # Redirects or loads public tools 

│ ├── /tools/ # Tool categories 

│ ├── dns/.php # DNS tools (e.g., record lookup) 


│ ├── pinger/.php # Server pinger tools 

│ ├── minecraft/*.php # Minecraft utilities 

│ ├── /includes/ # Frontend and UI components 

│ ├── header.php # Header template 

│ ├── footer.php # Footer template 

│ ├── sidebar.php # Sidebar for navigation 

│ ├── navbar.php # Navbar for global navigation 

│ ├── tool-header.php # Page-specific header for tools 

│ ├── head.php # Common <head> elements 

│ ├── /assets/ # Backend and static resources 

│ ├── /css/ # CSS for styling 

│ │ ├── navbar.css 

│ │ ├── cookies.css 

│ │ ├── sidebar.css 

│ ├── /js/ # JavaScript files 

│ │ ├── sidebar_toggle.js 

│ │ ├── cookies_popup.js 

│ ├── /php/ # Backend logic 

│ │ ├── config.php 

│ │ ├── database.php 

│ │ ├── cookies_process.php 

│ │ ├── functions.php 

│ └── /images/ # Icons and other visuals

---

## Features and Tools

### DNS Tools
- **Current Features**:
  - DNS Record Lookup
  - Reverse DNS
- **Planned**:
  - Zone File Parsing
  - Custom TTL Settings

### Server Pinger
- **Current Features**:
  - Server Status Check
  - Latency Analysis
- **Planned**:
  - Scheduled Monitoring
  - Historical Data and Graphs

### Minecraft Tools
- **Current Features**:
  - Title Generator
  - Command Builder
- **Planned**:
  - World Seed Analysis
  - Skin Viewer and Editor

---

## Development Roadmap

### Phase 1: Foundation (Complete)
- Modular structure
- Basic DNS and server tools
- User interface (header, sidebar, navbar)
- Cookie consent and language switcher

### Phase 2: Tool Expansion (In Progress)
- Add more DNS record types
- Advanced server monitoring
- Expanded Minecraft utilities

### Phase 3: User Accounts (Planned)
- **Features**:
  - Registration and Login
  - Saved Configurations
  - Usage History

### Phase 4: Analytics and Reporting
- Real-time analytics for tool usage
- Graphical reports for server monitoring
- Export options (CSV, PDF)

---

## Known Issues
- Broken styles
- Language switcher refreshes page instead of updating dynamically.
- Sidebar animation needs optimization for slower devices.

---

## Contributions
Feel free to contribute by suggesting features, reporting bugs, or submitting pull requests. Contact via the website footer.

---
