# Simple sign-in UI

A small, static login/sign-up interface built with HTML, CSS, and inline JavaScript. The buttons toggle between sign-up and sign-in layouts; the "Lost Password" link opens a separate playful page (`funny1.htm`). Images and styling are local, while the page also loads Google Fonts and Font Awesome.

## Run

Open `index.html` in a browser, or serve this directory with `python3 -m http.server 8000` and visit `http://localhost:8000`. There are no dependencies to install or build. `code.html` is a second copy of the login page.

**Demo only:** the form does not create accounts, verify passwords, send a reset email, or call a server. Do not use it to collect real credentials or describe it as an authentication system. A production sign-in flow would need a backend, secure session handling, and proper validation.
