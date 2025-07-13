# Automated-Appointment-confirmation-via-Gmail
This project is a simple yet powerful automation built using n8n, designed to send personalized confirmation emails automatically whenever a form is submitted.

It showcases how no-code tools can be integrated with real-world workflows using dynamic data fields and minimal setup.

✅ What It Does
Captures form submissions in real-time

Checks if a valid email address is provided

Sends a customized Gmail message to the user

Skips gracefully if the form data is incomplete

💡 Use Cases
Interview or appointment confirmations

Client or customer follow-ups

Admin task automation for HR or operations

Event or service booking notifications

🔧 Tools & Technologies
n8n: Workflow automation platform (self-hosted or cloud)

Gmail API: OAuth2 authenticated email sending

Dynamic Expressions: Used {{ $json.Email }} and {{ $json.submittedAt }} for personalization

📁 Files Included
Workflow JSON (importable into n8n)

Sample input data

Screenshots of the workflow setup
