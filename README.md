# SITE Capstone Project: Nomadia

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution](#solution)
- [Market Context & Differentiation](#market-context--differentiation)
- [User Personas](#user-personas)
- [Core Features](#core-features)
- [Technical Architecture](#technical-architecture)
- [User Capabilities](#user-capabilities)
- [User Guide](#user-guide)
- [Slides & Documentation](#slides--documentation)
- [How to Run Locally](#how-to-run-locally)
- [Tech Stack](#tech-stack)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

---

## Overview
Nomadia is an intuitive, all-in-one travel planning platform that enables users to build an itinerary by selecting flights, hotels, and activities from a single interface. The platform reduces the mental load of traditional trip planning and helps users create streamlined, personalized travel experiences.

---

## Problem Statement
Traditional travel planning requires users to:
- Check multiple sites
- Manually compare results
- Copy details between tabs
- Repeat searches
- Navigate complex interfaces

This fragmented process often results in confusion, frustration, and poorly structured itineraries.

---

## Solution
Nomadia consolidates the entire trip-planning process into one platform. Users can:
- Search for and compare flights, hotels, and activities
- Add items to a personalized itinerary
- Save itineraries (authenticated users)
- Complete checkout in a structured flow

Nomadia emphasizes clarity and simplicity to reduce decision fatigue and streamline the planning experience.

---

## Market Context & Differentiation
Competitors include Expedia, Booking.com, TripAdvisor, and Kayak.

Nomadia differentiates itself through its commitment to simplicity. Unlike traditional travel platforms that often present dense, information-heavy pages, Nomadia prioritizes a clean interface and a clear, guided flow from search to saved itinerary.

---

## User Personas

### 1. Simplicity Seeker (User Story 1)
A frequent traveler with limited technical experience who often feels overwhelmed by existing travel platforms.  
**Needs:** A guided, intuitive experience with clear navigation and simple filtering options.  
**Goal:** Build trips confidently without being overloaded by information or options.

### 2. Time-Conscious Business Traveler (User Story 2)
A busy professional who needs a fast, structured system to plan business trips efficiently.  
**Needs:** Speed, reliability, and the ability to save itineraries for reuse.  
**Goal:** Create a complete and organized work-travel plan in minutes.

---

## Core Features

### Filtering
Users can start crafting their itinerary by selecting flights, hotels, or activities based on their preference.

### Hotel Cards
- Displays hotel name, rating, and total price
- Users may add one hotel to their itinerary

### Activity Cards
- Shows category, address, and rating
- Activity modal available for additional details
- Users can add multiple activities to their itinerary

### Flight Cards
- Presents multiple flight packages based on selected dates
- Users can add selected flights to their itinerary

### Checkout
Provides a guided flow for finalizing bookings.

### Favorites
Authenticated users may save complete itineraries and access them later.

---

## Technical Architecture

### Backend Endpoints

| Category | Description |
|----------|-------------|
| User Endpoints | Register, Login, Add User, Find User, Delete User |
| API Endpoints | Hotels Search, Flight Offers, Activities |
| Saving Item Endpoints | Save, Delete, and Retrieve itineraries and favorites |

---

## User Capabilities

### Unauthenticated Users (User Story 1)
- Browse hotels, flights, and activities
- Add items to itinerary
- Continue through checkout

### Authenticated Users (User Story 2)
Includes all unauthenticated capabilities plus:
- Access Account Page
- Save itineraries
- View saved itineraries

---
## Slides & Documentation
Add your files to the repository and update the links below.

- [Project Presentation Slides](docs/Codepath_Capstone_Project.pdf)  
- [User Guide](docs/Nomadia_User_Guide.pdf)

---


## How to Run Locally
Adjust commands based on your actual file structure.

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/Nomadia.git

# Navigate into the project directory
cd Nomadia

# Install dependencies
npm install

# Start the development server
npm start
```
## Tech Stack
### Frontend
- React.js
- CSS

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### External APIs
- Foursquare API (activities and POIs)
- Booking.com API (hotels and accommodations)
- Duffel API (flight offers and airline bookings)

## Future Improvements
- Add user authentication and secure session management
- Improve mobile responsiveness across all pages
- Integrate more filtering options for activities and hotels
- Add caching or rate-limit handling for external APIs
- Expand itinerary features such as drag-and-drop reordering
- Add automated tests for backend routes and database logic

## Contributors

- Emily
- Leena
- Gregory


