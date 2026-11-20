# NetBill24 – Internet Café Billing System Prototype

A web-based interface prototype for an Internet Café (Warnet) Billing System, featuring separate interfaces for Members and Administrators.

## Project Overview

NetBill24 is a UI prototype developed as part of a major assignment for the **Human-Computer Interaction (HCI)** course during the third semester.

The project initially focused on designing a wireframe for an Internet Café Billing System. During the final examination, the wireframe was further developed into an HTML and CSS prototype instead of using Figma. This approach also allowed the implementation of concepts learned in the **Basic Web Programming** course.

## Features & Navigation

The prototype provides two different interfaces based on user roles.

### Homepage
- Homepage with a navigation button to proceed to the next page.

### Member Interface
- Member Login Page
- Member Dashboard
- Billing History
- Account Information
- Password Management
- Top-Up Pages

### Administrator Interface
- Administrator Login Page
- Administrator Dashboard
- Computer Status
- Members & Top-Up Management
- Settings
- Reports
- Account Management

## Technologies Used

- HTML
- CSS
- Tailwind CSS

## Project Structure

```text
prototype_netbill24/
│
├── gambar/                 # Image and icon assets
│   ├── changeemail.png
│   ├── changepw.png
│   ├── creditnetbill.png
│   ├── editusn.png
│   ├── icon_search.png
│   ├── logonetbill.png
│   ├── statistics.png
│   └── users.png
│
├── homepage.html
├── loginpage_member.html
├── dashboard_member.html
├── billinghistory_member.html
├── accinfo_member.html
├── loginpage_admin.html
├── dashboard_admin.html
├── comp_status.html
├── members_topup.html
├── settings.html
├── reports.html
└── ...                     # Other supporting HTML pages
```

## How to Run

1. Install [Visual Studio Code](https://code.visualstudio.com/) or another code editor.
2. Download or clone this repository.
3. Open the project folder in your code editor.
4. Open `homepage.html` in a web browser.

Alternatively, you can use the **Live Server** extension in Visual Studio Code to launch the prototype in your browser.

## Project Limitations

- Uses non-semantic HTML elements.
- The layout is not responsive and is primarily designed for desktop viewing.
- This project focuses on the user interface and prototype navigation rather than a fully functional billing system.

## Project Details

- **Project Name:** NetBill24
- **Project Type:** UI / Web Prototype
- **Academic Semester:** Semester 3
- **Primary Course:** Human-Computer Interaction (HCI)
- **Additional Course:** Basic Web Programming

---

*This project was developed for academic purposes as a prototype of an Internet Café Billing System.*