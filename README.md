# pdf-contract-automation
An automated workflow for generating PDF contracts, leveraging AI to process form submissions, execute logic, and deliver results via email.

## Overview
This project streamlines contract creation using an AI-powered automation workflow. It takes user input from a form, processes the data with AI and custom code, sends data to a PDF generation API, and finally emails the resulting PDF back to the user—all visually managed via a no-code workflow interface.


## Workflow Steps:

- On form submission: Triggered when a user submits contract details via a form.
- AI Agent: Processes form inputs, applies logic, and prepares contract details for PDF generation.
- Code: Executes business rules, computations, and data formatting as needed.
- HTTP Request: Sends the processed data to a PDF generation API endpoint.
- Send a Message: Automatically emails the generated PDF contract to the provided email address.


## User Input
The following data gets collected and processed:

Name: Recipient's name
Email: Recipient's email address
Amount: Value or field relevant to the contract
