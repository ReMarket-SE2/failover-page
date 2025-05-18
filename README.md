# Failover Pages for University Project

This project contains static HTML files designed to be served when the main application is offline or a requested page is not found. It provides a user-friendly message explaining the situation.

## Purpose

The primary goal of these pages is to inform users that the website is a university project and, as such, is not intended for constant online availability. It manages user expectations by clarifying that the site may be offline periodically.

## Files

The `public` directory contains the following HTML files:

*   `public/index.html`: This is the main landing page that should be displayed if the primary application is down or taken offline. It informs users that the site is a university project and might not be currently active.
*   `public/404.html`: This page is served when a user tries to access a URL that does not exist on the server. It provides a similar message about the nature of the project.

## Customization

The HTML files (`index.html`, `404.html`) and their inline CSS can be modified to change the appearance or the specific message conveyed to the users. These files are standard HTML and can be edited with any text editor.
