<img src="https://chinook.coderfoundry.com/images/chinook_brand_3.png" alt="Chinook Challenges Logo" width="200">

# Chinook Database Coding Challenges

Welcome to the **Chinook Database Coding Challenges** repository! This project is designed to help students in our coding bootcamp practice their SQL and C# skills by solving real-world problems based on the Chinook database.

## Table of Contents
- [Overview](#overview)
- [YouTube Tutorial](#youtube-tutorial)
- [Challenges](#challenges)
  - [Challenge 1: Warm-up](#challenge-1-warm-up)
  - [Challenge 2: Artists, Albums, and Tracks](#challenge-2-artists-albums-and-tracks)
  - [Challenge 3: Invoices and Line Items](#challenge-3-invoices-and-line-items)
  - [Challenge 4: Advanced Query](#challenge-4-advanced-query)
- [Getting Started](#getting-started)
- [Additional Resources](#additional-resources)
  
---

## Overview

The Chinook Database Coding Challenges are designed to test your skills in SQL and C#. The challenges are based on the **Chinook sample database**, which contains data related to a digital media store, such as artists, albums, tracks, invoices, and customers.

This repository includes several challenges of varying difficulty levels to help you prepare for technical interviews. Each challenge focuses on a different aspect of querying the Chinook database.

Visit the challenge website for more details: [Chinook Challenges](https://chinook.coderfoundry.com) _(Ctrl+Click to open in a new tab)_

---
## YouTube Tutorial
[![Watch the tutorial](https://img.youtube.com/vi/wf6GbP5IL_I/0.jpg)](https://youtu.be/wf6GbP5IL_I)

Check out our [YouTube tutorial](https://youtu.be/wf6GbP5IL_I) for a step-by-step guide on how to get started with the Chinook Database Coding Challenges.

## Challenges

### Challenge 1: Warm-up

- **Objective**: Get familiar with the Chinook database by writing a simple SQL query that retrieves a list of all artists.
- **Requirements**:
  - Write an SQL query to fetch the artist names.
  - Order the result by artist name in ascending order.
  
### Challenge 2: Artists, Albums, and Tracks

- **Objective**: Write an SQL query to retrieve all artists, their albums, and the corresponding tracks.
- **Requirements**:
  - Output should include:
    - Artist’s name
    - Album title
    - Track title
  - **Order**: The result should be ordered by artist name, album title, and track title.

### Challenge 3: Invoices and Line Items

- **Objective**: Retrieve all customers and their invoices, along with invoice line items.
- **Requirements**:
  - Output should include:
    - Customer's full name
    - Invoice details (date, total amount)
    - Line items (track title, unit price, quantity)
  - **Extra Credit**:
    - Add a dropdown filter to select a customer and view their invoices.
    - Implement collapsible invoice rows that toggle the visibility of line items.
    - Automatically calculate and display the total invoice amount.

### Challenge 4: Advanced Query

- **Objective**: Solve a more advanced SQL challenge that involves joining multiple tables and performing aggregations on the Chinook database.
- **Requirements**:
  - Write an SQL query to get the total sales per genre.
  - Include the genre name and the total amount spent for each genre.
  - **Order**: Sort the results by the total sales amount in descending order.

---

## Getting Started

### Prerequisites

To complete these challenges, you'll need:
- SQL Server or PostgreSQL (depending on which database engine is being used)
- C# development environment (Visual Studio, .NET Core)
- A basic understanding of SQL and Entity Framework

### Setup Instructions

For detailed setup instructions, including database configuration, project setup, and troubleshooting tips, visit the **Chinook Challenges website**:  
[Chinook Challenges Setup Instructions](https://chinook.coderfoundry.com/SetupGuide) _(Ctrl+Click to open in a new tab)_

This website contains all the information you need to get your environment ready to solve the challenges, including how to:
- Install necessary dependencies
- Set up the Chinook database
- Configure your project with the correct connection strings
- Test your setup

---

### Option 1: Clone the Repository

To get started, you can clone this repository to your local machine by using the `git clone` command. 

### Option 2: Use the Project Template

If this repository is set up as a template, you can create your own repository using the project template:

1. Navigate to the repository on GitHub: [Chinook Database Challenges](https://github.com/CoderFoundry/ChinookInterviewYT).
2. Click the **"Use this template"** button.
3. Follow the prompts to create a new repository based on this template.
4. After creating your new repository, clone it to your local machine and follow the steps in the **Project Setup** section to configure your environment.

## Additional Resources

- [Chinook Database Documentation](https://github.com/lerocha/chinook-database)
