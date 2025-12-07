<h1 align="center"><b>🚦 Traffic Management System </b></h1>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=cyan&size=25&center=true&vCenter=true&width=600&height=100&lines=OOP+Project;Traffic+Management+System;Java+Console+Application;Ain+Shams+University" />
  </a>
</p>

<br>

## <picture><img src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width="50px"></picture> About the Project

<picture>
  <img align="right" src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Right_Side.gif?raw=true" width="250px">
</picture>

<br><br>

- 📚 **Course Project** – Object Oriented Programming.
- 🏫 Implemented at **Faculty of Computer and Information Science – Ain Shams University**.
- 🚗 System to manage **traffic**, **vehicles**, **violations**, **zones**, and **traffic lights**.
- 👮 Supports **Admins**, **Traffic Officers**, and **Vehicle Owners**.
- 📊 Generates **reports** about most violated zones, frequent violation types, and traffic density.
- 💾 Uses **file processing** to save & load accounts, zones, notifications, and violations.

<br>

---

## <picture><img src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Skills.gif?raw=true" width="50px"></picture> Tech Stack

<p align="center">
  &emsp;
  <a href="https://www.java.com" target="_blank">
    <img alt="Java" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40">
  </a>
  &emsp;
  <a href="https://www.jetbrains.com/idea/" target="_blank">
    <img alt="IntelliJ IDEA" src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">
  </a>
  &emsp;
  <a href="https://git-scm.com/" target="_blank">
    <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  </a>
  &emsp;
  <a href="https://github.com" target="_blank">
    <img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

---

## 🧩 Main Features

- 🔐 **Authentication System**
  - Sign Up / Login / Logout for Admins, Officers, and Owners.
- 👨‍💼 **Admin Panel**
  - Manage zones and traffic lights.
  - Add new admins & traffic officers.
  - View statistics (number of users, violations, averages…).
  - Generate different traffic reports.
- 👮 **Traffic Officer Panel**
  - Record violations for vehicles inside assigned zones.
  - View and search violations they added.
- 🚗 **Owner Panel**
  - View profile and update password.
  - Add and view vehicles.
  - Receive and view notifications about violations.
- 📊 **Traffic Reports**
  - Most violated zone.
  - Most frequent violation type.
  - High-density zones based on time.
  - Average fine / violations.

---

## 🧭 UML Class Diagram

<p align="center">
  <img " alt="Traffic Management System UML" width="850">
  <br>
  📄 <a href="Traffic Management System UML.pdf" target="_blank">Click here to open UML PDF</a>
</p>

> The diagram shows the relationships between: `Account`, `Admin`, `Owner`, `TrafficOfficer`, `Zone`, `Traffic_Lights`, `Vehicle`, `Traffic_Violation`, `Notification`, `TrafficReport`, `File_Processing`, `Display`, and `Exc`.

---

## 🧱 Object-Oriented Design

- 🧬 **Inheritance**
  - `Admin`, `Owner`, `TrafficOfficer` inherit from `Account`.
- 🧺 **Aggregation / Composition**
  - `Owner` has many `Vehicle` and `Notification`.
  - `Zone` contains a list of `Traffic_Lights`.
  - `Vehicle` contains a list of `Traffic_Violation`.
- 🔗 **Associations**
  - `TrafficOfficer` records `Traffic_Violation` in a specific `Zone`.
  - `TrafficReport` uses data from `Zone` & `Traffic_Violation`.

---
