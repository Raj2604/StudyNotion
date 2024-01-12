# StudyNotion - Empowering Education with Technology
🚀 [Visit StudyNotion Website]([https://studynotion-frontend.vercel.app/](https://study-notion-edtech.netlify.app/))

![StudyNotion Main Page](images/mainpage.png)

StudyNotion stands as a robust EdTech platform, seamlessly bridging the gap between creators and consumers of educational content. Developed on the MERN stack—leveraging ReactJS, NodeJS, MongoDB, and ExpressJS—it offers a dynamic and interactive learning experience.

## Table of Contents

- [Introduction](#introduction)
- [System Architecture](#system-architecture)
  - [Front-end](#front-end)
  - [Back-end](#back-end)
  - [Database](#database)
  - [Architecture Diagram](#architecture-diagram)
- [API Design](#api-design)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Introduction

StudyNotion is a mission-driven platform, dedicated to enhancing accessibility and engagement in education. It serves as a global stage for instructors to showcase expertise and connect with learners, fostering a vibrant community of knowledge exchange.

This documentation delves into the technical intricacies, covering system architecture, API design, installation guidelines, usage instructions, and future enhancement possibilities.

## System Architecture

The StudyNotion EdTech platform comprises three core elements: the front-end, the back-end, and the database. The platform adopts a client-server architecture, with the front-end acting as the client and the back-end and database as the server.

### Front-end

Built on ReactJS, the front-end ensures a dynamic and responsive user interface—a cornerstone for an engaging learning experience. Seamless communication with the back-end is achieved through RESTful API calls.

#### Front End Pages

**For Students:**

- **Homepage:** Introduction to the platform with links to the course list and user details.
- **Course List:** Comprehensive list of available courses with descriptions and ratings.
- **Wishlist:** Displays courses added to a student's wishlist.
- **Cart Checkout:** Facilitates course purchases.
- **Course Content:** Presents course content, including videos and related material.
- **User Details:** Displays account details.
- **User Edit Details:** Allows students to edit account details.

**For Instructors:**

- **Dashboard:** Overview of the instructor's courses, along with ratings and feedback.
- **Insights:** Detailed metrics for instructor's courses, such as views and clicks.
- **Course Management Pages:** Facilitates course creation, updates, and deletion, along with content and pricing management.
- **View and Edit Profile Details:** Allows instructors to manage account details.

#### Front-end Tools and Libraries

The front-end employs ReactJS, CSS, and Tailwind for styling, with state management handled by Redux.

