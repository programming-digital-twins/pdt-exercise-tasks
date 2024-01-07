# Programming Digital Twins - Lab Module Tasks Overview

This project captures the Lab Module exercises and associated requirements designed to be implemented sequentially - in order - from Lab Module 01 to Lab Module 10. Some of the content is derived from my O'Reilly Media book, [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401), which is a useful reference for building the Edge Device Application and message-passing logic between it and the Digital Twin Application.

All Lab Module exercises can be found here:

 - [Programming Digital Twins Kanban Board](https://github.com/orgs/programming-digital-twins/projects/1)

# What You'll Find In This Project

There are dozens of exercises listed, each part of building a basic, end-to-end Digital Twin solution - step by step. This content is based on the course I created for teaching introductory IoT and Digital Twins concepts in a lab-based University course.

There are three primary repositories that provide the core content for this project:
 - Edge Device Application (Python): [pdt-edge-components](https://github.com/programming-digital-twins/pdt-edge-components)
 - Digital Twin Client Framework (C#): [pdt-cfw-components](https://github.com/programming-digital-twins/pdt-cfw-components)
 - Digital Twin Application (specific to Unity 3D - C# and other): [pdt-unity-components](https://github.com/programming-digital-twins/pdt-unity-components)

The combination of these repositories, coupled with the [Programming Digital Twins Kanban Board](https://github.com/orgs/programming-digital-twins/projects/1) I mentioned previously, comprise the lab module exercises and frameworks needed for implementation.

If you're a student in Building Digital Twins, you'll find a fourth repository containing document templates (README files) for each Lab Module in [pdt-exercise-docs](https://github.com/programming-digital-twins/pdt-exercise-docs). These templates will help you document your technical approach for each Lab Module and the Semester Project.
 - Exercise Docs (Markdown): [pdt-exercise-docs](https://github.com/programming-digital-twins/pdt-exercise-docs)

## Links, Exercises, Updates, Errata, and Clarifications

Please see the following links to access exercises for Programming Digital Twins and the Programming the Internet of Things book:
 - [Programming Digital Twins Kanban Board](https://github.com/orgs/programming-digital-twins/projects/1)
 - [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/)

# How Exercises are Organized

The requirements contained within this repository are captured as a simple list of dozens of tasks and activities - some are documentation-specific while most are programming-specific - and labeled according to activity category, chapter, and implementation order.

## About Lab Modules, Milestones and Labels

Lab Modules are organized into 'parts', which are intended to represent categories of exercises that are related, yet are also designed to be implemented in sequence, as each part is intended to be implemented in sequence (e.g., Part 01 first, with each lab module implemented in order, followed by Part 02, etc.) Lab module details are currently under development and will be linked here when available. For now, the structure is as follows: 
  - [Part 01: Foundations](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/4)
  - [Part 02: Core Components](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/5)
  - [Part 03: Use Cases](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/6)
  - [Part 04: Final Project](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/7)
  
Each exercise within a given Lab Module has at least one label, intended to assist with categorizing the work to be done, as follows:
  - [build](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/additional): Build and / or DevOps related task (e.g., checkout a new branch).
  - [configuration](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/configuration): Configuration related task (e.g., install some software).
  - [documentation](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/documentation): Documentation related task (e.g., write-up your approach).
  - [exercise](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/exercise): Required exercise related task (i.e., you should implement this).
  - [additional](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/additional): Additional exercise task (i.e., if you're a student in my class, you should implement this, although it is currently optional).
  - [integration](https://github.com/programming-digital-twins/pdt-exercise-tasks/labels/integration): Test and integration related task (e.g., test connection between apps).
  
## About Naming and Numbering Conventions

Exercises and notes are named according to the following convention:

*{project name}-{category}-{lab module #}-{sequence #}*

This naming convention is designed to help you navigate through the requirements in each Lab Module sequentially, building your solution in a step-by-step manner. The naming breakdown is as follows:
  - project name:
    - PDT: The project name (Programming the Digital Twins).
  - category:
    - DOC: General documentation that provides a summary overview of the section or lab module.
    - INF: An informational note.
    - STU: A student-specific requirement, usually documentation-related (this is relevant if enrolled in the Connected Devices course, for example).
    - CFG: A configuration requirement.
    - EDA: An Edge Device App (EDA)-specific requirement.
    - CFW: A Client Framework (CFW)-specific requirement.
    - DTA: A Digital Twin App (DTA)-specific requirement.
    - INT: An integration requirement that may depend upon other requirements specific to those labeled as CFG, EDA and / or DTA.
  - lab module #:
    - 01 - 10: Depicts the order of implementation for the various lab modules.
  - sequence #:
    - 001 - 099: Depicts the order in which the requirements should be implemented. Note that sequence #'s 000 and 100 are reserved, as indicated in the NOTE below.

The structure of each chapter's notes and requirements are sequenced based on the ordered guidelines listed below:
  - FIRST: Read the information (INF) notes to help guide you through the exercises.
    - Example (INF): PDT-INF-01-001 is the first (001) note in Lab Module 01 associated with Programming Digital Twins (PDT), and is for informational (INF) purposes.
  - SECOND: If you're a student in a PDT-specific course (e.g., Building Digital Twins), read through the STU category requirements to prepare for each exercise. Else, skip to the THIRD guideline.
    - Example (STU): PDT-STU-02-001 is the first (001) student-specific task in Lab Module 02 associated with Programming Digital Twins (PDT).
  - THIRD: Read and implement the configuration (CFG) requirements to prepare for each exercise.
    - Example (CFG): PDT-CFG-02-001 is the first (001) configuration-specific task in Lab Module 02 associated with Programming Digital Twins (PDT).
  - FOURTH: Read and implement each exercise related to the Edge Device App (EDA) and / or the Digital Twin App (DTA).
    - Example (EDA): PDT-EDA-01-001 is the first (001) EDA task in Lab Module 01 associated with Programming Digital Twins (PDT). It only applies to the Edge Device App (EDA).
    - Example (DTA): PDT-DTA-05-002 is the second (002) DTA task in Lab Module 05 associated with Programming Digital Twins (PDT). It only applies to the Digital Twin App (DTA), and should be implemented after PDT-DTA-05-001.
  - FIFTH: Read and implement any integration exercise(s) to verify your functionality is working properly.
    - Example (INT): PDT-INT-05-001 is the first (001) integration task in Lab Module 05 associated with Programming Digital Twins (PDT). Unless otherwise specified, it should be implemented AFTER all CFG, EDA, and DTA related tasks.

NOTE: As alluded to previously, an exception to the numbering sequence scheme is made for build-specific tasks related to the EDA and DTA. The initial build requirement (check out a new branch) is numbered '000' for each component (e.g., PDT-EDA-02-000) and should be implemented before any other component-specific requirement, and '100' for the final build requirement (e.g., PDT-EDA-02-100), which should be implemented after all other component-specific requirements.

# Other Things to Know

## Pull Requests

PR's are currently disabled.

## Updates

Much of the tasks and issues representing requirements within this repository will continue to evolve, so you may want to check back regularly for potential updates. Please note that this repository is still under active development - you'll likely find typos and other errata.

# License

Please see [LICENSE information in PDT-DOC-LIC](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/2) for more information. In summary:

*Documentation - Usage and License*

This project's [written instructions and non-source code documentation](https://github.com/orgs/programming-digital-twins/projects/1) - all Notes, Instructions and Cards contained within this Kanban board - are available under the following license:
 - Documentation: Copyright &copy; 2024 by [Andrew D. King](https://andyking.me). Licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/ " target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0 <img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a>.
 - See [LICENSE](https://github.com/programming-digital-twins/pdt-exercise-tasks/blob/default/LICENSE) for details.

*Source Code Solutions and Examples - Usage and License*

This project contains embedded sample source codes representing examples and solutions. Unless otherwise represented, these embedded source codes (C# and Python) are available under the following license:
 - Source Codes: Copyright &copy; 2024 [Andrew D. King](https://andyking.me). Licensed under [The MIT License](https://opensource.org/licenses/MIT).
 - See [LICENSE-CODE](https://github.com/programming-digital-twins/pdt-exercise-tasks/blob/default/LICENSE-CODE) for details.

# References

## Tools and Specifications (subject to change)

- [DTDLParser](https://github.com/digitaltwinconsortium/DTDLParser)
  - Reference: Digital Twin Consortium and contributors. (2024) [Online]. Available: https://github.com/digitaltwinconsortium/DTDLParser.
- [InfluxDB.Client](https://github.com/influxdata/influxdb-client-csharp)
  - Reference: Influx Data, Inc. Influx DB C# Client. (2024) [Online]. Available: https://github.com/influxdata/influxdb-client-csharp.
- [InfluxDB v2](https://docs.influxdata.com/influxdb/v2/)
  - Reference: Influx Data, Inc. Get started with InfluxDB v2. Available: https://docs.influxdata.com/influxdb/v2/. Accessed 01Jan2024.
- [Mosquitto MQTT Broker](https://mosquitto.org/)
  - Reference: The Eclipse Foundation, Inc. Eclipse Mosquitto - An Open Source MQTT Broker. Available: https://mosquitto.org/. Accessed 15Nov2023.
- [MQTT v 3.1.1](https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html)
  - Reference: A. Banks, R. Gupta. MQTT Version 3.1.1. OASIS Standard, 2014. Available: https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html.
- [MQTTnet](https://github.com/dotnet/MQTTnet)
  - Reference: .NET Foundation and contributors. MQTTnet .NET library for MQTT communications. (2024) [Online]. Available: https://github.com/dotnet/MQTTnet.
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)
  - Reference: James Newton-King. Json.NET JSON framework for .NET. (2024) [Online]. Available: https://github.com/JamesNK/Newtonsoft.Json.
- [NUnit](https://nunit.org/)
  - Reference: Charlie Poole, Rob Prouse. Nunit unit testing framework for .NET languages. (2024) [Online]. Available: https://github.com/nunit.
- [Sense-Emu](https://sense-emu.readthedocs.io/en/v1.1/)
  - Reference: The Raspberry Pi Foundation. Sense HAT Emulator. Available: https://sense-emu.readthedocs.io/en/v1.0/. Accessed 15Nov2023.
- [Unity 3D for Students](https://unity.com/products/unity-student)
  - Reference: Unity Technologies. Unity Student Plan. Available: https://unity.com/products/unity-student. Accessed 15Nov2023.
- [Visual Studio](https://visualstudio.microsoft.com/vs/)
  - Reference: Microsoft. Visual Studio. Available: [https://code.visualstudio.com/](https://visualstudio.microsoft.com/vs/). Accessed 04Jan2024.
- [Visual Studio Code](https://code.visualstudio.com/)
  - Reference: Microsoft. Visual Studio Code. Available: https://code.visualstudio.com/. Accessed 15Nov2023.
- [Wireshark](https://www.wireshark.org/)
  - Reference: G. Combs et al. Wireshark. Available: https://gitlab.com/wireshark/wireshark. Accessed 15Nov2023.
