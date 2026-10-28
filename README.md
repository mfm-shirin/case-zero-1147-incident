# CASE ZERO: The 11:47 Incident

**An Interactive Digital Forensics Investigation Prototype**

CASE ZERO: The 11:47 Incident is a web-based educational prototype that introduces the fundamentals of digital forensics through a fictional cybersecurity investigation. Players explore a case, examine digital clues, reconstruct events, and use available evidence to work towards solving the incident.

The project was developed as part of an academic practical to explore interactive web application development, investigative workflows, and the presentation of digital forensic concepts.

## Overview

Digital forensics involves identifying, collecting, examining, and interpreting digital evidence to understand events related to a cyber incident. Learning these concepts can be more engaging when presented through a scenario-based experience.

CASE ZERO presents a fictional incident centred around the time **11:47**, inviting users to approach the case as an investigator and evaluate the available information.

## Objectives

- Understand the basic concepts of digital forensics.
- Explore evidence analysis and timeline reconstruction.
- Practise correlating digital clues with a fictional incident.
- Introduce investigative reasoning through an interactive interface.
- Apply web development concepts to a cybersecurity-themed academic project.

## Key Features

- **Case-based investigation:** Explore a fictional cybersecurity incident.
- **Digital evidence exploration:** Examine clues presented within the investigation.
- **Timeline reconstruction:** Understand the sequence of events using available information.
- **Suspect investigation:** Explore suspect-related information as part of the case.
- **Clue correlation:** Connect relevant details to develop a possible explanation of the incident.
- **Forensics-inspired interface:** A web interface designed around a digital investigation theme.

*Note: The available features depend on the current implementation. This project is an educational prototype and should not be considered a complete digital forensics investigation platform.*

## Technology Stack

The project uses the following technologies:

- **Next.js** – Web application framework.
- **React** – Component-based user interface development.
- **TypeScript** – Type-safe JavaScript development.
- **Tailwind CSS** – Interface styling.
- **shadcn/ui** – UI component tooling.
- **Lucide React** – Icons and interface elements.

## Getting Started

### Prerequisites

Ensure that the following tools are installed:

- Node.js
- pnpm
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/mfm-shirin/case-zero-1147-incident.git
```

**2. Navigate to the project directory**

```bash
cd case-zero-1147-incident
```

**3. Install dependencies**

```bash
pnpm install
```

**4. Start the development server**

```bash
pnpm dev
```

**5. Open the application**

Visit the following address in your browser:

```text
http://localhost:3000
```

### Production Build

To create a production build, run:

```bash
pnpm build
```

To start the production server after a successful build:

```bash
pnpm start
```

## Project Structure

The repository follows a Next.js application structure.

```text
case-zero-1147-incident/
├── app/              # Application routes and pages
├── components/
│   └── ui/           # Reusable UI components
├── lib/              # Shared utilities
├── public/            # Static assets
├── package.json       # Project dependencies and scripts
├── pnpm-lock.yaml     # Dependency lockfile
├── next.config.mjs    # Next.js configuration
└── README.md          # Project documentation
```

## Academic Context

**Project Type:** Academic Practical / Prototype

**Domain:** Cybersecurity and Digital Forensics

**Project Name:** CASE ZERO: The 11:47 Incident

The project demonstrates the application of web development concepts to an educational digital forensics scenario. It is intended for learning, demonstration, and further development.

## Limitations

- The investigation is based on a fictional scenario.
- The current project is a prototype and may not implement every feature of a complete forensic investigation system.
- It is not intended to collect or analyse evidence from real devices.
- Any investigative conclusions depend on the information provided within the scenario.

## Future Scope

Potential improvements include:

- Adding more investigation scenarios and case files.
- Implementing interactive evidence examination.
- Developing a more detailed event timeline and clue correlation system.
- Introducing evidence scoring and investigation progress tracking.
- Adding case summaries and investigation reports.
- Improving usability, accessibility, and the overall interface.

These enhancements represent possible future development and are not necessarily implemented in the current version.

## Disclaimer

CASE ZERO: The 11:47 Incident is an educational project developed for academic purposes. All incidents, characters, suspects, and evidence depicted within the fictional scenario are intended for learning and demonstration. The project is not a substitute for professional digital forensic tools or established forensic procedures.

## Author

**mfm-shirin**

GitHub: [@mfm-shirin](https://github.com/mfm-shirin)

---

*Built as an academic exploration of interactive web development and digital forensics.*
