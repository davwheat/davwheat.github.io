# Tuitionn<!-- omit in TOC -->

## Contents

- [Contents](#contents)
- [Sign in page](#sign-in-page)
- [User Interface](#user-interface)
  - [Material Design](#material-design)
- [Javascript Libraries](#javascript-libraries)

---

Tuitionn was programmed in **PHP**, **HTML,** **CSS** and **JavaScript**. It also used **[Material Design](https://material.io/develop/web/)** and **[reCAPTCHA](https://developers.google.com/recaptcha/)**.

It focused on providing a free, accurate experience for UK students to help them study for their end of school exams. It was used by most of my school year and helped many of us achieve greater grades than what we could've done without it.

## Sign in page

I used **[Material Design](https://material.io/develop/web/)** to keep a consistent theme which also would allow porting to a web app or Android in the future. I also used **[reCAPTCHA](https://developers.google.com/recaptcha/)** to filter real users from bots and spam.

This login page, when submitted, would check if the user was a robot or not, then it would check the database of users for an account with a username or e-mail equal to what the user entered. It would then use PHP's `password_verify()` function to test the password against the hashed version in the database. If it matched, it would store a sessions cookie and allow the user access to the members section of the site.

![Login Page](/assets/img/tuitionn/login.png)

## User Interface

### Material Design

I used Material Design for its clean looks. It also saves time because you do not need to spend time designing and implementing a custom user interface and you can sidestep common design pitfalls.

However, my main choice for Material Design was more subtle than that.

I chose Material Design because users would subconciously link a high level of trust and security to my website because they would instinctively link my website with Google.

## Javascript Libraries

I used a few different public libraries in this project. These include:

- [gauge.js](https://github.com/bernii/gauge.js)
- [Material Design](https://github.com/material-components/material-components-web)

The gauges were used to display a user's progress through a subject on the site.

![Gauges](/assets/img/tuitionn/gauges.gif)
