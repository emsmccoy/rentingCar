# Renting Car Application

## Overview

This document serves as a guide and log for the frontend development of the **Renting Car Application** project. This project involves creating a full-stack application for managing car rentals, with a focus on the frontend development using React (via Hilla TSX) and integrating with a Spring Boot backend.

---

## PR Submission Checklist

## **Completed Tasks**:

- [ ] Design Data Models for Cars

- [ ] Select Optimal Data Model for Cars

- [ ] Implement Backend Endpoint to List Cars

- [ ] Create Admin Feature for Car Availability Calendar

- [ ] Build Calendar Interface for User Date Selection

- [ ] Implement Query for Available Cars by Date/Delegation

- [ ] Develop Booking Creation Feature

- [ ] Update Car Availability Post-Booking

- [ ] Create User Booking List View

- [ ] Build Admin Dashboard for Booking and Fleet Management

- [ ] Develop User Profile Management Interface

- [ ] Implement Java-Based Authentication (Backend)

## **Testing**:

- [ ] Use JUnit with Spring Boot's `@SpringBootTest` for integration testing

---

## Estimated Time for Tasks

| Task Name                               | Description                                                                                                                                                                                                      | Estimated Time | Deadline     | Notes |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | ------------ | ----- |
| Design Data Models for Cars             | Create 5 different data models for representing available cars. Document advantages and disadvantages of each (e.g., scalability, query ease). Focus on attributes like ID, type, availability, price, location. | 2 hours        | May 20, 2025 |       |
| Select Optimal Data Model for Cars      | Choose the best data model from the 5 options. Write a short justification (50 words) explaining why it fits the app's needs (e.g., backend integration, frontend display).                                      | 1 hour         | May 21, 2025 |       |
| Implement Backend Endpoint to List Cars | Build a backend endpoint (`listCars`) to fetch car data based on the selected model. Reference commit **9e88199** from v1.1.1 for initial setup.                                                                 | 3 hours        | May 22, 2025 |       |

## Week 2: Core Renting Feature (May 25 - May 31, 2025)

| Task Name                                             | Description                                                                                                                       | Estimated Time | Deadline     | Notes |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | -------------- | ------------ | ----- |
| Create Admin Feature for Car Availability Calendar    | Implement a backend function (`createAvailabilityCalendarByCar`, v1.1.2) for admins to set availability calendars per car.        | 3 hours        | May 26, 2025 |       |
| Build Calendar Interface for User Date Selection      | Develop a frontend calendar interface (using Hilla TSX) for users to select rental dates and specify delegation details (v1.1.3). | 3 hours        | May 27, 2025 |       |
| Implement Query for Available Cars by Date/Delegation | Create a backend query and frontend integration to show available cars based on selected dates and delegation (v1.1.3).           | 3 hours        | May 29, 2025 |       |
| Develop Booking Creation Feature                      | Build a feature (v1.2) for users to make a booking for a specific car, date range, and delegation. Ensure backend confirmation.   | 3 hours        | May 30, 2025 |       |
| Update Car Availability Post-Booking                  | Implement logic (v1.3) to update car availability in the backend after a booking is confirmed. Reflect changes in frontend.       | 2 hours        | May 31, 2025 |       |

## Week 3: User and Admin Views (June 1 - June 5, 2025)

| Task Name                                              | Description                                                                                                                            | Estimated Time | Deadline     | Notes |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | -------------- | ------------ | ----- |
| Create User Booking List View                          | Develop a frontend page to display a user's past and upcoming bookings with details like car, dates, and status.                       | 3 hours        | June 2, 2025 |       |
| Build Admin Dashboard for Booking and Fleet Management | Create an admin dashboard to monitor bookings, view stats (e.g., car utilization), and manage fleet (add/remove cars).                 | 5 hours        | June 4, 2025 |       |
| Develop User Profile Management Interface              | Build a frontend system for users to update personal info (name, contact), view booking history, and set preferences (e.g., car type). | 4 hours        | June 5, 2025 |       |

## Week 4: Security (June 6 - June 9, 2025)

| Task Name                                     | Description                                                                                               | Estimated Time | Deadline     | Notes |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------------- | -------------- | ------------ | ----- |
| Implement Java-Based Authentication (Backend) | Set up backend authentication using Java (Spring Security, JWT) to secure user access and admin features. | 6 hours        | June 9, 2025 |       |

## Estimated Time Summary

### Common Part (Core Tasks)

| Task Group          | Estimated Time |
| ------------------- | -------------- |
| Data Models & Setup | 6 hours        |
| Renting Feature     | 14 hours       |
| User & Admin Views  | 12 hours       |
| **Total**           | **32 hours**   |

### Optional Part

| Task Group     | Estimated Time |
| -------------- | -------------- |
| Authentication | 6 hours        |
| **Total**      | **6 hours**    |



---

## Future Improvements

- **Real-time Updates**: Implement WebSocket for real-time updates on booking status changes.

- **Advanced Filtering**: Add complex search criteria, sorting, and filtering options for cars and bookings.

- **Reporting**: Develop features to generate booking statistics and export data to PDF or Excel.

- **Library Leaflet Map for Locations**: Integrate maps to show car locations and rental agency branches.

- **User Experience Enhancements**: Improve UI/UX with animations, better error handling, and user feedback mechanisms.

- **Performance Optimization**: Optimize frontend performance by implementing lazy loading, code splitting, and reducing bundle size.

- **Accessibility**: Ensure the application meets accessibility standards to cater to a broader audience.

- **Internationalization**: Add support for multiple languages to make the application globally accessible.

- **Security Enhancements**: Implement additional security measures like CSRF protection, secure headers, and regular security audits.

- **Automated Testing**: Expand test coverage with end-to-end testing using tools like Cypress or Playwright.

### Citations:

1. https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46163886/ea80021c-d724-4884-8edf-5f050166b548/paste.txt

---

Answer from Perplexity: [pplx.ai/share](https://www.perplexity.ai/search/pplx.ai/share)
