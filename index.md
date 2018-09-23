---
layout: default
---

# Contents <!-- omit in toc -->

- [About me](#about-me)
  - [Qualifications](#qualifications)
  - [Language Experience](#language-experience)
  - [Software Experience](#software-experience)
- [Previous Projects](#previous-projects)
  - [Tuitionn](#tuitionn)
    - [Log in screen](#log-in-screen)
    - [Javascript Libraries](#javascript-libraries)

# About me

I am **David Wheatley** ([davwheat](https://www.github.com/davwheat)). I am an enthusiastic programmer and enjoy personal projects too.

## Qualifications

| Course                | Grade |
| :-------------------- | :---: |
| GCSE Computing        | 9     |
| GCSE Maths            | 8     |
| GCSE English Language | 8     |
| GCSE Spanish          | 7     |

## Language Experience

| Language             | Rating |
| :------------------- | :----: |
| HTML                 | 9/10   |
| PHP                  | 8/10   |
| C# (WinForms)        | 8/10   |
| CSS3                 | 7/10   |
| JavaScript           | 7/10   |
| C# (WPF)             | 6/10   |
| C# (Xamarin Android) | 6/10   |
| ASP.NET              | 3/10   |

## Software Experience

| Language                          | Rating |
| :-------------------------------- | :----: |
| Visual Studio                     | 9/10   |
| [Paint.NET](https://getpaint.net) | 9/10   |
| Visual Studio Code                | 8/10   |
| GitHub                            | 8/10   |
| Microsoft Excel                   | 8/10   |
| Microsoft Word                    | 8/10   |
| PHPStorm                          | 7/10   |
| Git (Command Line)                | 7/10   |

# Previous Projects

## Tuitionn

**Tuitionn** was a free GCSE revision website I began working on while I was in Year 10 (age 14).

It was programmed in **PHP**, **HTML,** **CSS** and **JavaScript**. It also used **[Material Design](https://material.io/develop/web/)** and **[reCAPTCHA](https://developers.google.com/recaptcha/)**.

It focused on providing a free, accurate experience for UK students to help them study for their end of school exams. It was used by most of my school year and helped many of us achieve greater grades than what we could've done without it.

### Log in screen

I used **[Material Design](https://material.io/develop/web/)** to keep a consistent theme which also would allow porting to a web app or Android in the future. I also used **[reCAPTCHA](https://developers.google.com/recaptcha/)** to filter real users from bots and spam.

This login page, when submitted, would check if the user was a robot or not, then it would check the database of users for an account with a username or e-mail equal to what the user entered. It would then use PHP's `password_verify()` function to test the password against the hashed version in the database. If it matched, it would store a sessions cookie and allow the user access to the members section of the site.

![Login Page](/assets/img/tuitionn/login.png)

### Javascript Libraries

I used a few different public libraries in this endeavour. These include:

- [gauge.js](https://github.com/bernii/gauge.js)
- [Material Design](https://github.com/material-components/material-components-web)

![Gauges](/assets/img/tuitionn/gauges.gif)