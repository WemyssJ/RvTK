# RvTK-Releases

🚧 **Currently under active development**

> **Help Shape RvTK:**  
> User feedback plays an important role in shaping the future direction of RvTK. If you have suggestions, feature requests, or workflow improvements, please share your feedback through the inbuilt feedback button or GitHub discussions.

# **RvTK**

### BIM Management & Productivity Toolkit for Autodesk Revit

A C# Autodesk Revit add-in focused on BIM management, quality assurance, and productivity. Developed by BIM Managers, for BIM Managers.

> **Note:** RvTK is an independent third-party add-in for Autodesk Revit. It is not affiliated with, endorsed by, or sponsored by Autodesk.
>
> **Project Status:** RvTK is currently the codename for the project and is expected to undergo rebranding prior to commercial release.
>
> **Development Disclaimer:** While extensive testing and stress testing is carried out to improve stability and reliability, unexpected issues may still occur. Users should take appropriate precautions to protect their work, including maintaining regular backups and verifying results before relying on outputs for project delivery. Use RvTK at your own discretion.

---

## Compatibility

RvTK is developed to support:

* Autodesk Revit 2023
* Autodesk Revit 2024
* Autodesk Revit 2025
* Autodesk Revit 2026
* Autodesk Revit 2027 (limited testing completed)

---

## Requirements

RvTK requires:

* Windows 10/11
* Autodesk Revit 2023 or newer
* .NET Framework 4.8 or later
* A valid Autodesk Revit installation

---

## Overview

RvTK brings together the tools and workflows that BIM professionals use every day, helping reduce repetitive tasks, improve consistency, and make working in Revit more efficient.

Built from real project experience, RvTK focuses on practical solutions for:

* Model management
* Quality assurance
* Drawing production
* Structural workflows
* BIM standards and compliance

The goal is to create a single toolkit that helps Revit users spend less time on repetitive processes and more time delivering projects.

---

## Screenshots

![RvTK Command Centre](images/RvTK-Ribbon-Snapshot2.png)

---

![RvTK Dockable Panel](images/RvTK-Command-Centre-Snapshot.png)

---

## RvTK Command Centre

The RvTK Command Centre provides a centralised location for users to access and organise their everyday Revit workflows.

The customisable **Favourites Panel** allows users to create their own personalised workspace by adding:

* RvTK tools
* Native Revit commands
* Commands from other Revit add-ins and plugins

This provides a single access point for the tools users rely on most, reducing the need to navigate through multiple ribbon tabs and interfaces.

---

## BIM Manager Configuration

RvTK includes comprehensive configuration options designed for BIM Managers to manage, customise, and distribute settings across their organisation.

This allows companies to tailor RvTK to suit their own workflows, standards, and project requirements, ensuring teams have consistent access to the tools and settings they need.

Configuration options can be managed centrally and distributed to users, helping improve consistency, support BIM standards, and simplify deployment across project teams.

---

## Installation & Updates

RvTK is designed to be simple to install and update.

### Installation

1. Download the latest RvTK release package.
2. Extract the downloaded ZIP file.
3. Ensure Autodesk Revit is closed.
4. Run the RvTK installer (`.exe`).
5. Open Revit and RvTK will be available.

No additional configuration is required for a standard installation.

Administrator permissions may be required depending on your organisation's security settings.

---

### Updating RvTK

To update to the latest version:

1. Download the latest RvTK release package.
2. Close Autodesk Revit.
3. Extract the new ZIP file.
4. Run the updated RvTK installer (`.exe`).

The latest version will replace the previous installation while maintaining existing configuration settings.

---

### Uninstalling RvTK

RvTK includes a dedicated uninstaller that allows users to remove the add-in and manage stored configuration settings.

> **Note:** The RvTK uninstaller is located at:
>
> ```
> %appdata%\RvTK\RvTK uinstaller\uninstaller.exe
> ```

The uninstaller provides three options:

* **Remove Plugin Only** - Removes RvTK add-in files while keeping user configuration settings.
* **Clear Personal Configuration** - Removes user settings and preferences while keeping the RvTK installation.
* **Complete Clean Uninstall** - Removes RvTK, including add-in files, configuration files, and stored preferences.

After uninstalling, restart Autodesk Revit to ensure all RvTK components are fully removed.

---

## Trial Period & Feedback

Each installation of RvTK includes a **45-day trial period**, allowing users to explore and test the available tools.

During the development phase, the trial period will be renewed with each new patch release, ensuring users testing the latest improvements have continued access.

Feedback, bug reports, and feature suggestions are encouraged and can be submitted directly through the **inbuilt feedback button within RvTK**.

---

## BIM Manager Deployment

RvTK includes built-in tools to support organisation-wide deployment and configuration management.

BIM Managers can customise RvTK Settings to suit their organisation's workflows, standards, and requirements, then export the configuration package for distribution across other machines.

### Deployment Workflow

1. Configure RvTK Settings on the designated BIM Manager machine.
2. Export the RvTK configuration package.
3. Distribute the configuration package to the required users or machines.
4. Import the configuration package on each machine.

This allows organisations to maintain consistent RvTK settings across teams, helping standardise workflows, improve productivity, and support company BIM standards.

Further deployment options and management features will continue to be developed.

---

## Development & Community

RvTK is actively being developed, and feedback from users is an important part of shaping the future direction of the toolkit.

If there is a specific tool, workflow improvement, or feature that would help your team, please submit a request through the inbuilt feedback button. Suggestions will be reviewed and considered for future development.

During the development phase, RvTK will remain free to use.

When RvTK transitions to a paid product in the future, users will receive advance notice. Any future pricing will aim to remain realistic, fair, and accessible for BIM professionals and teams while supporting continued development.
