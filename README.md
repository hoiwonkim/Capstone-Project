# RoomFree Capstone Project

This capstone project focuses on developing a web application similar to Airbnb. It's an online marketplace for users to search, save, book accommodations, and leave reviews. The property owners can upload images, add property details, and manage listings via a convenient dashboard.

## Table of Contents
1. [Project Objectives](#project-objectives)
2. [Technologies](#technologies)
3. [User Features](#user-features)
4. [Property Features](#property-owner-features)
5. [Project Flowchart](#project-flowchart)
6. [User Flow Diagram](#user-flow-diagram)

<a name="project-objectives"></a>
## Project Objectives
- Create a web-based platform that allows users to search for and book accommodations
- Provide a simple and responsive user interface
- Implement property management features for property owners

<a name="technologies"></a>
## Technologies
- Backend: Python, Django, Django REST Framework, Strawberry GraphQL
- Frontend: ReactJS

<a name="user-features"></a>
## User Features
- Search for accommodations by location, check-in, check-out dates, and number of guests
- Save their favorite listings for future reference
- Book accommodations and manage bookings
- Leave reviews and read others' feedback about accommodations

<a name="property-owner-features"></a>
## Property Owner Features
- Upload multiple images to showcase the property
- Write detailed information about the property, including amenities, rules, and availabilities
- Manage listings through a dashboard, such as adding, editing, or deleting properties

<a name="project-flowchart"></a>
## Project Flowchart

```mermaid
flowchart TD
    A[start project] --> B[requirements analysis]
    B --> C[backend development]
    C --> D[frontend development]
    D --> E[test]
    E --> F[distribution]
    F --> G[Maintenance]
    G --> H[Complete Project]

    C --> I[Implement Marketplace Features]
    I --> J[Search Accommodation]
    I --> K[Favorite function]
    I --> L[Reservation function]
    I --> M[write a review]
    I --> N[check dashboard]
![Project Flowchart]("C:\Users\GGPC\Desktop\Capstone-project")

User Flow Diagram
Run -> Login -> Search -> Listings -> Select listings -> Listing details -> Bookmarks -> Book -> Book Success/Failure -> Write a review -> Submit a review -> Complete review -> Dash Board -> Booking History -> Favorites List -> Review History -> Account Settings -> Sign Out This User Flow Diagram provides a detailed representation of Airbnb web application's user experience (UX) design illustrating the interactions and pathways taken by users. The sequence includes logging in, searching for accommodations, choosing from a list of accommodations, viewing property details, saving to favorites, booking, writing reviews, and accessing the dashboard to manage bookings, favorite properties, review history
