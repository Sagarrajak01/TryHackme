## Components
Application: The code, images, styles, and icons that dictate how the website looks and functions.
Web Server: This component hosts the application. It listens for requests and returns a response to the user.
Host Machine: The underlying operating system, Linux or Windows, that runs the web server and the application.

## Web Servers
Apache: The most popular web server to host simple websites and blogs, most commonly WordPress.
Nginx: An industry standard for high-performance web apps. Used by companies like Netflix, Airbnb, and GitHub.
Internet Information Services (IIS): A Microsoft-developed web server commonly used in enterprise environments

## Protecting the Web

Protecting the Application

# Secure Coding: Avoid insecure functions, ensure proper handling of errors, and remove sensitive information.
Input Validation & Sanitization: Validate and sanitize user input to prevent injection attacks.
# Access Control: Restrict access based on user roles.

Protecting the Web Server

# Logging: Keep a detailed record of all web requests with access logs.
# Web Application Firewall (WAF): Filter and block harmful traffic based on defined rules.
# Content Delivery Network (CDN): Reduce direct exposure to your server and use integrated WAFs.

Protecting the Host Machine

# Least Privilege: Use low-privilege users for services.
# System Hardening: Disable unnecessary services and close unused ports.
# Antivirus: Add endpoint-level protection that blocks known malware.

Security Tips for All Three Components

# Strong Authentication: Don't just let anyone access your code, admin panels, or host machine.
# Patch Management: Ensure your app dependencies, web server, and host machine are up to date.