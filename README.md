Simple-Inquiry-Form

This project is a simple Contact/Inquiry Form developed as part of the assignment task.
It uses EmailJS to send form submissions directly to email without requiring a backend server.
After submission, users are greeted with a Thank You message and a smooth success tick animation ✅.

Features

Responsive Contact/Inquiry Form

Integration with EmailJS (3rd party service for sending form data via email)

Animated Success Tick using SVG + CSS

Clean, modern UI design with colorful and attractive bubble-style elements

Works without backend setup

Technologies Used

HTML5 – Structure of form & thank-you section

CSS3 – Styling, animations, and layout

JavaScript (ES6) – Form handling and EmailJS integration

EmailJS – Third-party service for email delivery

Project Structure
├── index.html       # Main file with form and thank-you message
├── style.css        # Styling + animations
├── script.js        # Handles EmailJS integration & form submission
├── README.md        # Documentation

How It Works

User fills out the form (Name, Email, Message).

On submit, the data is sent via EmailJS API.

If successful:

The form hides.

The success tick animation appears.

A confirmation message is displayed.

If failed:

An error alert is shown.

Demo Preview
Success Tick Animation

When submission is successful, the circle and tick animate smoothly:

<img src="https://user-images.githubusercontent.com/placeholder/success.gif" alt="Success Animation" width="300"/>
Assignment Notes

This project demonstrates:

Use of third-party service (EmailJS) to handle email submissions.

Application of UI/UX principles (bubble-style design, color themes).

CSS animations for interactive feedback.

Backend is not required because EmailJS handles the email sending.

Future Enhancements

Add confetti animation  after success.

Form validation with custom error messages.

Store form submissions in a database.

Author
Shreeja Sarkar
