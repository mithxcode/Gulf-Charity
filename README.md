# Golf Charity Subscription Platform

**Project Overview:**
This is a sample assignment project for Digital Heroes Full-Stack Development selection. The platform is a subscription-based golf application allowing users to:

* Enter and track their last 5 golf scores.
* Participate in monthly draw-based rewards.
* Support a charity with a portion of their subscription.

The project includes a **User Dashboard** and an **Admin Panel**, implemented as a single-page web application using **HTML, CSS, and JavaScript**. It is fully responsive and interactive.

---

## Features

### User Dashboard

* Subscription status display
* Enter golf scores (1-45) with rolling logic for last 5 scores
* Charity contribution selection using a slider
* View next draw date
* Dynamic total winnings update

### Admin Panel

* View total users, prize pool, and charity contribution totals
* Run monthly draw (generates 5 random numbers)
* Display winners of the draw

### General

* Responsive layout for desktop and mobile
* Modern UI with glassmorphism cards and hover animations
* Interactive elements powered by JavaScript

---

## Project Structure

```
index.html        # Main HTML file
README.md         # Project documentation
```

All styles and scripts are included inline for simplicity.

---

## Deployment

This project is hosted on **Netlify**:

* Live Website: [https://gulfcharity.netlify.app](https://gulfcharity.netlify.app)
* User Dashboard: [https://gulfcharity.netlify.app/#dashboard](https://gulfcharity.netlify.app/#dashboard)
* Admin Panel: [https://gulfcharity.netlify.app/#admin](https://gulfcharity.netlify.app/#admin)

### Admin Panel Credentials

* **Email:** [admin@example.com](mailto:admin@example.com)
* **Password:** Admin@123

---

## How to Use

1. Open the live website.
2. Navigate using the top navigation buttons: Home / Dashboard / Admin.
3. On **Dashboard**:

   * Enter scores and dates.
   * Adjust charity contribution with the slider.
   * View total winnings dynamically.
4. On **Admin Panel**:

   * View total users, prize pool, charity contributions.
   * Run monthly draw and see winners.

---

## Notes

* This is a front-end only project; all data is stored in memory (JavaScript objects) and will reset on page reload.
* No backend, database, or real payment gateway integration is included.

---

## AI Tools Used

* ChatGPT was used to generate the HTML, CSS, and JavaScript structure of the project.

---

