# isom452-group1-khidmati
Group 1: Khidmati
# Khidmati (خدمتي): Home Services Booking Platform for Kuwait

> **Stage 1: HTML & CSS implementation.** This stage covers page structure, navigation, styling, layout and forms. There is no JavaScript or backend yet.

## About the Project

Khidmati is a service marketplace website where residents of Kuwait can find, compare and book trusted home service providers such as AC technicians, cleaners, plumbers, electricians, movers and painters. Providers manage their jobs from their own dashboard, and an admin verifies providers and handles complaints.

**Type of website:** Service marketplace platform (customers, providers and admin).

### Problem it solves
- People in Kuwait usually find technicians through word of mouth, WhatsApp groups or Instagram, with no way to verify quality or compare prices.
- In the summer, an AC failure is urgent and reliable technicians are hard to reach.
- Prices are inconsistent and there is little accountability when a job goes wrong.

### Target users
- **Customers:** families, tenants and expats who want quick, reliable service.
- **Service providers:** independent technicians and small companies.
- **Admin:** platform staff who verify providers and resolve complaints.


## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero search, popular services, how it works, top-rated providers |
| Services | `pages/services.html` | All service categories with starting prices |
| Providers | `pages/providers.html` | Provider list with a filter form (service, area, price, rating) |
| Provider Profile | `pages/provider-profile.html` | Provider details, price list, reviews and a Book Now button |
| Booking | `pages/booking.html` | Booking form: service, date, time, address, payment method |
| Order Confirmation | `pages/confirmation.html` | Booking summary and order status tracker |
| Login | `pages/login.html` | Login form for customers, providers and admins |
| Register | `pages/register.html` | Account creation form |
| Become a Provider | `pages/become-provider.html` | Provider application form with document upload |
| Customer Dashboard | `pages/customer-dashboard.html` | Upcoming bookings, history and saved addresses |
| Provider Dashboard | `pages/provider-dashboard.html` | Job requests, schedule, earnings and profile form |
| Admin Dashboard | `pages/admin-dashboard.html` | Provider verification, bookings, complaints and categories |
| About Us | `pages/about.html` | Mission, values and users |
| Contact & Help | `pages/contact.html` | Contact form, details and FAQ |



## How the Requirements Are Met

| Requirement | How it is implemented |
|---|---|
| **Website structure** | Semantic HTML5 on every page: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, one `h1` per page |
| **Navigation** | The same header and footer on all pages, with relative links and an `active` state for the current page |
| **Styling** | A single external stylesheet (`css/style.css`) with CSS variables for colors, spacing and fonts |
| **Layout** | CSS Grid for card grids, dashboards and page columns; Flexbox for navigation, filters and form actions |
| **Forms** | Structured with `form`, `fieldset`, `legend`, `label` and the correct input types (text, email, tel, password, date, number, file, radio, checkbox, select, textarea). No JavaScript validation |
| **Responsive design** | Media queries at 900px, 820px and 600px; the mobile menu is CSS-only |
| **Accessibility** | Every input has a label, images have `alt` text, and focus outlines are visible |


## Design Notes

- **Colors:** deep teal `#0f4c5c` (trust), gold `#e8a33d` (accent) and warm sand `#fbf6ec` (background sections).
- **Language:** the interface is in English at this stage, with the brand name in Arabic. A full Arabic (right-to-left) version is planned for a later stage.
- **Sample data:** all names, prices, ratings and booking numbers are placeholders for demonstration.
- **Contact details:** the email and phone number on the Contact page are examples, not real.

## Planned Next Stages

1. JavaScript for form validation and interactivity.
2. Arabic and English language switching with RTL layout.
3. Backend (Node.js and Express) with a database for users, providers and bookings.

## Notes

- All form buttons link to the next logical page, so the website can be walked through without a backend.
- Pages and sample data are for educational purposes only.

---

&copy; 2026 Khidmati. Course project.
