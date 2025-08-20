# School Selection with Java

A Java-based school selection application built using Apache NetBeans. This project assists users in evaluating and selecting potential schools based on various criteria.

 Table of Contents

- Project Overview
- Features 
- Technologies Used  
- Getting Started  
  - Prerequisites 
  - Installation
  - Running the Application
- Project Structure
- Contributing
- License

Project Overview

This application was developed in Java using Apache NetBeans. It allows users to select schools based on defined factors such as location, academic performance, tuition fees, and admission requirements.

 Features

- Evaluate schools by customizable criteria  
- Sort and filter school options  
- [Optional] Display detailed school profiles or analytic reports




 Technologies Used

- Language: Java  
- IDE: Apache NetBeans  
- Build System: Apache Ant *(build.xml is present)*  
- Project Files:  
  - `nbproject/` — NetBeans project metadata  
  - `src/` — Java source files  
  -Other: `manifest.mf`, `schoolselection.iml`, and the distribution files in `dist/`



Getting Started

Prerequisites

- Java JDK 8 or higher  
- Apache NetBeans IDE (version X or above) *(depends on what you used)*  
- Apache Ant (optional—NetBeans typically handles build tasks internally)

 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iambillcaspar101/schoolselectionwithjava.git
   cd schoolselectionwithjava
2. Open in NetBeans
    File → Open Project… and select the cloned folder.
    Wait for NetBeans to index sources.
3. Run (NetBeans)
   Right–click the project → Run.
   If NetBeans asks for a main class, choose your main entry point (e.g., com.example.Main).
   You can also set it via Project Properties → Run → Main Class.
4. Run (Ant / CLI)
   You have two options, depending on whether the JAR’s Main-Class is set in the manifest.mf:
   A) Runnable JAR present (dist/<name>.jar has Main-Class):
       ant clean jar
       java -jar dist/schoolselectionwithjava.jar
   B) No Main-Class in manifest:
     ant clean jar
     java -cp dist/schoolselectionwithjava.jar your.package.Main
5.schoolselectionwithjava/
    ├─ build/ # Ant build output (generated)
    ├─ dist/ # Packaged artifacts (e.g., runnable JAR)
    ├─ nbproject/ # NetBeans metadata
    ├─ src/ # Java source code
    ├─ build.xml # Ant build script
    ├─ manifest.mf # JAR manifest (optionally sets Main-Class)
    ├─ schoolselection.iml # IDE module file (optional)
    ├─ README.md # This file
    ├─ Gidi_Mary_0007785.pdf # Example document (present in repo root)
    └─ Sento_Benson_82749893.pdf # Example document (present in repo root)
6. Contributing
    Fork this repo
    Create a feature branch: git checkout -b feat/my-change
    Commit: git commit -m "Add my change"
    Push: git push origin feat/my-change
    Open a Pull Request
7. No license has been added yet. If you intend the project to be open-source, consider adding an MIT or Apache 2.0 license.
