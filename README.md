# Exercise 10: Cookies and Sessions

## About This Lab

This lab helped me understand how cookies and sessions work in PHP and how websites remember information between requests. I created PHP pages to observe cookies, test a login process, and control access to a protected page.

## What I Learned

- **Cookies:** I learned how cookies store small pieces of information in the browser and send them back to the server on later requests.
- **First and Last Visit:** I used cookies to keep track of the first time a user visits the page and the most recent visit.
- **Visit Counter:** I learned how a cookie can store a visit count and how deleting that cookie affects the displayed count.
- **Random Number Cookie:** I added a `random_number` cookie that generates a random number from 1 to 100 and sets an expiration time of 30 days.
- **Login and Sessions:** I tested how PHP handles login information and how a protected page checks whether a user is authorized.
- **Logout:** I tested the logout process and confirmed that protected access should be denied after the login state is cleared.

## Project Files

- `session-cookies-1.php` — Displays visit information and demonstrates cookie behavior.
- `session-cookies-2.php` — Handles the login test.
- `session-cookies-3.php` — Demonstrates access to a protected page.
- `logout.php` — Handles logging out of the lab.

## How to Test the Lab

1. Open Lab 1 and observe the visit information.
2. Reload the page and check how the cookie values change.
3. Open Chrome DevTools and go to **Application → Cookies** to inspect the cookies.
4. Submit the test password provided in the assignment.
5. Open Lab 3 and check the protected-page behavior.
6. Use the logout link and try opening Lab 3 again.
7. Inspect the `random_number` cookie and its expiration details.

## Live CODD Link

Lab 1: https://codd.cs.gsu.edu/~tpalaniappa1/inclass10/session-cookies-1.php

## Conclusion

This exercise gave me practical experience with PHP cookies, sessions, and basic access control. I learned how information can persist between requests, how cookies can be inspected in the browser, and why a protected page must check the user's authorization before displaying its content.
