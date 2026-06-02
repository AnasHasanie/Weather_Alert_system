# Weather_Alert_system

# Weather Alert System (n8n)

This project is an automated Weather Alert System built using **n8n**. The workflow checks the current weather conditions in Lahore every day at a scheduled time using the OpenWeatherMap API. If the temperature exceeds a predefined threshold (38°C), the system automatically sends an email alert to the user via Gmail.

## Features

* Automated daily weather monitoring
* Real-time weather data from OpenWeatherMap API
* Temperature threshold detection
* Automatic email notifications
* No manual intervention required
* Built entirely using n8n's no-code/low-code workflow automation

## Workflow

1. Schedule Trigger runs daily at 12:00 PM.
2. HTTP Request fetches current weather data for Lahore.
3. IF Node checks whether the temperature is greater than 38°C.
4. Gmail Node sends a weather alert email if the condition is met.

## Technologies Used

* n8n
* OpenWeatherMap API
* Gmail API

## Use Case

This workflow helps users stay informed about extreme weather conditions by automatically sending alerts when temperatures become unusually high.

⚠️ **Note:** Before publishing the workflow, remove or replace any exposed API keys, email addresses, and credentials with placeholders for security reasons.
