# HomeEase — Home Services Booking Platform

A modern, full-stack home services booking platform designed to connect customers with professional service providers for plumbing, electrical repairs, cleaning, AC maintenance, carpentry, and other home maintenance services.

HomeEase provides a centralized platform where customers can explore services, manage bookings, and connect with service professionals through a simple and professional user interface.

## Live Demo

**Live Website:** https://home-services-booking-platform-blush.vercel.app/

Explore the deployed prototype and experience the HomeEase interface.

## Project Screenshots

### 1. Home Page

<!-- Replace the filename below with your actual screenshot filename -->

<img width="1900" height="918" alt="Screenshot 2026-10-09 203756" src="https://github.com/user-attachments/assets/526b8d7a-b449-4486-ac70-ec4d2eb19db4" />


### 2. Available Services

<!-- Add your services page screenshot -->

<img width="1915" height="906" alt="Screenshot 2026-10-09 203822" src="https://github.com/user-attachments/assets/58ed9400-b11c-4c7f-84ac-8aeed18fae9a" />




> **Note:** Add your actual screenshots to the `screenshots` folder and ensure that the filenames match the paths above. Remove any sections that do not have corresponding screenshots.

## Problem Statement

Finding reliable home service professionals can be difficult. Customers often face challenges with service discovery, appointment scheduling, pricing transparency, and booking management.

HomeEase aims to simplify this process by providing a centralized digital platform for discovering home services and managing service bookings.

## Key Features

### Customer Features

* Explore available home maintenance services.
* Search for services based on customer requirements.
* View service information and pricing.
* Select preferred service dates and time slots.
* Manage service bookings and booking details.
* Access a responsive and user-friendly interface.

### Service Provider Features

* Dedicated service provider interface.
* Manage service-related information.
* Access booking information and service requests.
* Support a structured workflow for managing assigned services.

### Admin Features

* Dedicated administrative interface.
* Manage platform information and service records.
* Support role-based access to platform functionality.
* View operational information through an administrative dashboard.

### Platform Features

* Modern and responsive user interface.
* Customer, provider, and administrator roles.
* Structured booking workflow.
* Service discovery and search interface.
* Full-stack application architecture.
* Deployment through Vercel.

**Implementation note:** Features such as authentication, booking persistence, payments, and role-based authorization should be considered functional only after they have been implemented and tested end to end.

## Technology Stack

| Technology   | Purpose                                    |
| ------------ | ------------------------------------------ |
| Next.js      | Application framework and routing          |
| React        | User interface development                 |
| TypeScript   | Type-safe application development          |
| Tailwind CSS | Responsive styling and UI design           |
| PostgreSQL   | Relational database                        |
| Drizzle ORM  | Database queries and schema management     |
| Recharts     | Dashboard analytics and data visualization |
| Vercel       | Application deployment                     |
| Git & GitHub | Version control and project collaboration  |

## Application Architecture

The platform follows a full-stack application architecture.

```text
                    HomeEase Platform
                           |
                           v
                  Next.js Application
                           |
             +-------------+-------------+
             |             |             |
             v             v             v
          Customer       Provider       Admin
          Interface      Interface     Dashboard
             |             |             |
             +-------------+-------------+
                           |
                           v
                  Application Logic
                           |
                           v
                   Drizzle ORM
                           |
                           v
                    PostgreSQL
```

The fron
