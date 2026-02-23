# Online / Offline Employee Form

This project is a web form used to collect employee information.
It also detects whether the user is **online or offline** and saves data locally if there is no internet connection.

---

## Project Objective

The goal of this project is to:

* Check if the user's network connection is available.
* Allow the user to fill out a form.
* Save form data locally when the device is offline.

---

## Features

* Network status detection (Online / Offline)
* Employee data collection form
* Offline data saving using Local Storage
* Simple and clean user interface
* Form validation
* Responsive layout

---

## Form Fields

The form collects the following information:

* Full Name
* Email Address
* Phone Number
* Department
* Employee ID
* Address

---

## Technologies Used

* HTML5
* CSS (Internal Styling)
* JavaScript
* Browser LocalStorage API

---

## How It Works

1. The website checks the network status using JavaScript.
2. If the user is **online**, the form can be processed normally.
3. If the user is **offline**, the data entered in the form is saved locally in the browser using LocalStorage.

---

## Folder Structure

```id="81264"}
03-office-form
│
├── index.html
└── README.md
```

---

## How to Run

1. Open the project folder.
2. Double-click **index.html**.
3. Fill the form and submit.

To test offline saving:

* Turn off WiFi
* Submit the form
* The data will be stored locally in the browser.

---

## Author

Bhaumikk Keer
B.Tech Computer Science Engineering
ITM Skills University

---
